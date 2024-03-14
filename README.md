# 10.3.6-WASD-show-and-tell

```
let x, y; // Initial position of the block
let vroom = 5; // Speed of movement

function setup() {
  createCanvas(400, 400);
  x = width / 2;
  y = height / 2;
}

function draw() {
  background(220);
  // Draw the block
  rectMode(CENTER);
  rect(x, y, 50, 50);
  // how do we move the square using grade 1 math?
  


  
  // lets make an if() here
}


function keyPressed() {
// Check for key presses and update the block's position
if (key === 'w') { // W key
  y -= vroom;
}// end W
// if () { // S key
//   y += vroom;
// }
// if () { // A key
//   x -= vroom;
// }
// if () { // D key
//   x += vroom;
// }

}// end key pressed
```
