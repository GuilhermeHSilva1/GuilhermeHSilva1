<h1 align="center">Guilherme Hillesheim da Silva</h1> <br></br>

<div align="center">
  <a href="https://github.com/GuilhermeHSilva1">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=GuilhermeHSilva1&theme=dark"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GuilhermeHSilva1&layout=compact&langs_count=7&theme=dark"/>
</div>

<div>
  <script type="application/processing">

void setup() {
size(1349,450);
} 

var speed = -5;
var BolaKame = 1005;
var Barra = 1150;
var BarraBranca = 1140;


draw = function(){

background(41, 14, 77);

fill(17, 83, 237);
ellipse(1300,200,200,200);
rect(Barra,173,10000,60);
fill(118, 217, 245);
rect(BarraBranca,183,10000,40);

fill(118, 217, 245)
ellipse(1300,200,150,150);

fill(17, 83, 237);
ellipse(BolaKame,200,300,300);


fill(118, 217, 245)
ellipse(BolaKame,200,200,200);

if(BolaKame < 100){
    speed = 1000;
}
if(Barra < 100){
    speed = 1000;
}
if(BarraBranca < 100){
    speed = 1000;
}
if(BolaKame > 1005){
    speed = -5;
}
if(Barra > 1150){
    speed = -5;
}
if(BarraBranca > 1140){
    speed = -5;
}
    Barra = Barra + speed;
    BarraBranca = BarraBranca + speed;
    BolaKame = BolaKame + speed;
}


</script> 
</div>

![Snake animation](https://github.com/GuilhermeHSilva1/GuilhermeHSilva1/blob/output/github-contribution-grid-snake.svg)
