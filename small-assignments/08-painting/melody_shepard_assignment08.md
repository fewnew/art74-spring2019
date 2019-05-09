function setup() {
  createCanvas(800, 800);
}

function draw() {
  background(220);
  ellipse(56, 50, 70, 100); fill(255); arc(40, 60, 50, 70, PI, PI + QUARTER_PI); square(50, 50, 10, 10); ellipse(35, 35, 20, 10); ellipse(75, 35, 20, 10);

ellipse(39, 35, 10, 10); //pupil left// ellipse(80, 35, 10, 10); //pupil right// rect(30, 70, 50, 5, 10); //mouth//
ellipse(79, 35, 10, 10);
line(20, 90, 20, 60);
line(30, 90, 20, 60); //hair 
  
line(60, 80, 20, 60);  
stroke(80);
  
}
