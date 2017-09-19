# for문

int y1 = 60;
int y2 = 300;




void setup(){
  size(600, 400);
  background(255);
  
  for(int i = 0; i <width; i = i + 10){
  line(i, y1, i, y2);
  }
}

void draw() {
}
