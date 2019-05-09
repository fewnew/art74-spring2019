void setup (){
  size(600,600);
  
}


void draw(){
  background(255);
  fill(255,100, 100);
  rect(0, 0, 600, 600);
  fill(240, 232, 104);
  rect(240, 80, 120, 440);
  fill(240, 232, 104);
  rect(275, 520, 45, 200);
  fill(255, 210, 20);
  ellipse(width/2, height/2, 100, 100);
  fill(255, 0, 0);
  ellipse(width/2, height/4, 100, 100);
   fill(0, 255, 0);
  ellipse(width/2, height/1.33, 100, 100);
  fill(0);
  triangle(40,40,120,40,mouseX,120);
}
