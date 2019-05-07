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
  ellipse(300, 300, 100, 150);
  ellipse(500, 300, 100, 150);
  noStroke();
  fill(0, 0, 255);
  ellipse(300, 330, 80, 80);
   ellipse(500, 330, 80, 80);
   fill(255,0,0);
   arc(400, 500, 200, 200, 0, PI+QUARTER_PI, CHORD);
}
