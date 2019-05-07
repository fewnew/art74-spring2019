void setup() {
  size(800, 800);
   background(255);

}

void draw() {
  fill(255, 255, 0);
  noStroke();
  ellipse(width/2, height/2, 550, 550);
  fill(255);
  stroke(153);
  strokeWeight(2);
  ellipse(300, 300, 100, 150);
  ellipse(500, 300, 100, 150);
  noStroke();
  fill(0, 0, 255);
  ellipse(300, 330, 80, 80);
  ellipse(500, 330, 80, 80);
  fill(255,0,0);
  arc(400, 500, 200, 200, 0, PI+QUARTER_PI, CHORD);
  fill(255, 155, 150);
  ellipse(200,400, 50,50);
  ellipse(600,400, 50,50);
  stroke(0);
  strokeWeight(5);
  line(300, 225, 300, 200);
  line(270, 200, 280, 230);
  line(500, 225, 500, 200);
  line(470, 200, 480, 230);
}
