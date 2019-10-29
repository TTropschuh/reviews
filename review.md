## Homework Sketch #1: Function Review
```javascript
function setup() {
    createCanvas(400, 400);
}

function draw() {
    background(255);

    if (mouseIsPressed) {
        drawRedCircle(width / 2, height / 2, 100);
    } else {
        drawBlueCircle(width / 2, height / 2, 100);
    }
}

function drawRedCircle(posX, posY, diameter){
  fill('red')
  circle(posX, posY, diameter);

}

function drawBlueCircle(posX, posY, diameter){
  fill('blue')
  circle(posX, posY, diameter);

}

```

## Homework Sketch #2: Conditionals Review

```javascript

let buttonIsPressed = false;

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(255);
  drawButton(100, 100, 200, 200);

  if (mousePressed &&
    mouseX > 100 && mouseX < 300 &&
    mouseY > 100 && mouseY < 300  ) {
    buttonIsPressed = true;
    fill(0, 255, 0);


  } else {
      buttonIsPressed = false;
    fill(255, 0, 0);
  }
  print(buttonIsPressed);
}

function drawButton(x, y, w, h) {
  rect(x, y, w, h, 10);
}


function mousePressed() {
  buttonIsPressed = true;
}


function mouseRelease() {
  buttonIsPressed = false;
}
```

## Homework Sketch #3: Matrix Math Review

```javascript

function setup() {
    createCanvas(300, 300);
}

function draw() {
    background(180);
    rectMode(CENTER);
    fill("#EE3366");
    angleMode(DEGREES);

  rotate(50);
  rect(0, 0, 50, 50);
    rect(100, 0, 50, 50);
    rect(200, 0, 50, 50);
    rect(300, 0, 50, 50);

}

```

## Homework Sketch #4: Handling user input


working on it!

```javascript

```
