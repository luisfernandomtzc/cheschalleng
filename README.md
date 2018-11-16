# cheschalleng

void setup(){
	size(500,500);
	background (255);
}

void draw(){
	fill(0);
	for(int y = 0; y < 500; y = y +100) {
		for(int x = 0;x < 500; x = x +100){
  	rect (x,y,50,50);
	
		for(int y2 = 50; y2 < 500; y2 = y2 +100){
		for(int x2 = 50;x2 < 500; x2 = x2 +100){
  	rect (x2,y2,50,50);
		}
		}
	}
}
}
