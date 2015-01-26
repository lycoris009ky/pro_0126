# pro_0126
void setup(){
  size(600,600);
}

float pos_x[] = {0,51,102,153,204,255};
float pos_y[] = {0,0,0,0,0,0};
float sikaku = 50;
float mv;
  

void draw(){
  
  for(int i = 0; i < 6; i++){
  rect(pos_x[i] + mv,pos_y[i],
  50,50);
  if(pos_x[i]  < 1){mv++;}
  if(pos_x[i] + mv > 600){mv--;}
  
  }
  
 
}
