const cols = process.stdout.columns;
const rows = process.stdout.rows;
const drops = Array(cols).fill(0);

setInterval(() => {
  let output = "";
  for (let i = 0; i < cols; i++) {
    const char = String.fromCharCode(0x30A0 + Math.random() * 96);
    output += drops[i] > rows ? " " : char;
    drops[i] = drops[i] > rows ? 0 : drops[i] + 1;
  }
  console.clear();
  console.log(output);
}, 50);
