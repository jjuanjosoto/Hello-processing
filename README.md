# Hello-processing
void setup() {
size(500, 500);
background(10, 80, 100);
}

void draw(){
background(10, 80, 100);
if(mousePressed) {

stroke(255, 255, 255);
fill(150, 220, 90);
ellipse(mouseX, mouseY, 300, 300);
ellipse(mouseX, 120, 50, 20);
ellipse(mouseX, 140, 80, 100);

fill(160, 210, 230);
rect(mouseY, 40, 10, 240);

rect(mouseY, mouseX, 20, 70);
rect(220, mouseX, 15, 220);
rect(mouseX, 130, 30, 80);

fill(255, 90, 70);
ellipse(90, 100, 10, 90);
ellipse(mouseX, mouseY, 70, 70);
ellipse(mouseX, 180, 70, 30);

ellipse(190, mouseY, 20, 90);
ellipse(170, 60, 10, mouseX);
ellipse(200, mouseY, 90, 20);
ellipse(mouseX, mouseY, 80, 10);
}
}
