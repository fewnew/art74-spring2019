void setup(){
    size(800,800);
    background(255);
    
}

void draw(){
  fill(255, 223, 142);
  noStroke();
  ellipse(width/2, height/2, 550,550);
  triangle(150, 300, 70, 50, 290, 150);
  triangle(150, 300, 70, 50, 290, 150);
  fill(255);
  stroke(153);
  
  fill(255, 204, 250);
  noStroke();
  triangle(170, 300, 120, 90, 300, 160);
  triangle(350, 475, 378, 420, 406, 475);
  fill(255);
  stroke(153);
  
  fill(0, 0, 0);
  noStroke();
  circle(250, 350, 55);
  fill(255);
  stroke(153);
  
  fill(255, 255, 255);
  noStroke();
  circle(260, 345, 20);
  fill(255);
  stroke(153);
  

line(130, 320, 185, 375);
line(130, 500, 185, 475);
line(125, 415, 190, 415);

fill(255, 204, 250);
  noStroke();
  arc(400, 550, 100, 100, 0, PI+QUARTER_PI, CHORD);
  fill(255);
  stroke(153);
  
}
