var y1
var ctl
var obj
var rock1
var rock2
var rock3
var xr1 = 580
var xr2 = 580
var xr3 = 580
var call
var start



function setup() {
  createCanvas(600, 300);
}

y1 = 240
ctl = 0
rock1 = 0
rock2 = 0
rock3 = 0
call = 1
start = 0


function keyPressed() {
  
 if (keyCode === UP_ARROW) {
 ctl = 1
 }
  
}

function mouseReleased(){
  if(dist(mouseX, mouseY, 300, 80) < 50){

    start = 1
    if (call == 0) {
    call = 1
    }
    
  
  }
}

function draw() {
  background(220);
  
  fill(50)
  rect(0, 280, 600, 20)
  
  fill(0)
  rect(280, y1, 20, 40)
  
 
  if (ctl == 1) {
  y1 = y1 - 7
  }
  
  if (y1 <= 180) {
  ctl = 2
  }
  
  if (ctl == 2) {
    y1 = y1 + 7 
}

  if (y1 >= 240)
    ctl = 0

  if (start == 1) {
 obj = random (0, 100)}
  
 //shitou1 kongzhi
 
  if (obj >= 70 && rock1 == 0) {
    
    rock1 = 1
  
  }
   
    if (rock1 == 1) {
        
      rect (xr1, 260, 20, 20)
      
      if (call == 1){
      xr1 = xr1 - 10}
    }
  
   if (xr1 <= 0) {
   rock1 = 0
     xr1 = 580
   }
  
  
  //shitou2 kongzhi
  
  if (obj >= 89 && rock1 == 1 && rock2 == 0) {
    
    rock2 = 1
  
  }
   
    if (rock2 == 1) {
        
      rect (xr2, 260, 20, 20)
       if (call == 1) {
      xr2 = xr2 - 10 }
    }
  
   if (xr2 <= 0) {
   rock2 = 0
     xr2 = 580
   }
  
  //shitou3 kongzhi
  if (obj >= 99 && rock1 == 1 && rock2 == 1 && rock3 == 0) {
    
    rock3 = 1
  
  }
   
    if (rock3 == 1) {
        
      rect (xr3, 260, 20, 20)
      if (call == 1) {
      xr3 = xr3 - 10 }
    }
  
   if (xr3 <= 0) {
   rock3 = 0
     xr3 = 580
   }
  
  
  if (y1 + 40 >= 240 && xr1 == 300) {
    
   call = 0
    start = 0
    
  }
    
if (start == 0) {
  fill(255)
  ellipse (300, 80, 50)
}

}

