# animationblocks-pixil-art-
Function makefullcirclefireworks(fire) {
let color = randcolor();
let velocity = Mathath.random() * 8+8;
let max = fireworks * 3;
for (let i = < max; i++) {
let rad = (i * Math.PI * 2) / max;
let firework = {
x: fire.x, y : fire.y,
size: Math.random() = 1.5,
fill: color,
vx: math.cos(rad) * veloocity + (Math.random() - 0.5) * 0.5,
vy: math.sin(rad) * veloocity + (Math.random() - 0.5) * 0.5,
ay: 0.06, alpha: 1,
life: math,round((Math,random() * range) / 2) + range / 1.5
};
