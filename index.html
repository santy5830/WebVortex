<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WebVortex | Desarrollado por Santiago Haquet</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600&display=swap" rel="stylesheet">

<img src="c:\Users\chiky\Downloads\ChatGPT Image 23 abr 2026, 09_41_25 p.m..png" alt="Logo" width="500">
<style>

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Orbitron', sans-serif;}

body{background:#0b1120;color:#e2e8f0;}

canvas{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
z-index:-1;
opacity:0.5;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
display:flex;
align-items:center;
justify-content:center;
padding:15px 30px;
background:#020617cc;
z-index:1000;
}

.logo-fijo{
position:fixed;
top:10px;
left:15px;
height:60px;
z-index:2000;
}

.search-box{position:relative;display:flex;align-items:center;}
.search-icon{position:absolute;left:10px;}

.search-box input{
padding:6px 6px 6px 30px;
border-radius:5px;
border:none;
background:#1e293b;
color:white;
}

.cart-icon{
position:fixed;
right:20px;
top:15px;
cursor:pointer;
font-size:22px;
}

#contador{
position:absolute;
top:-8px;
right:-10px;
background:#ef4444;
color:white;
font-size:12px;
padding:2px 6px;
border-radius:50%;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
}

.card{
background:#1e293b;
margin:15px;
padding:20px;
width:250px;
border-radius:10px;
text-align:center;
transition:0.2s;
}
.card:hover{transform:translateY(-4px);}

button{
background:#22c55e;
border:none;
padding:8px 12px;
cursor:pointer;
margin-top:10px;
border-radius:6px;
}
button:hover{background:#16a34a;}

.section{
padding:120px 20px;
text-align:center;
}

p{color:#94a3b8;}

#carrito{
position:fixed;
right:-300px;
top:0;
width:300px;
height:100%;
background:#020617;
padding:20px;
transition:0.3s;
}
#carrito.active{right:0;}

#toast{
position:fixed;
bottom:20px;
left:50%;
transform:translateX(-50%);
background:#22c55e;
color:white;
padding:10px;
display:none;
}

/* DIAPOSITIVA */
.slide-img{
width:70%;
max-width:900px;
border-radius:10px;
margin-top:20px;
box-shadow:0 0 15px rgba(0,0,0,0.6);
}

.canva{
display:flex;
justify-content:center;
}
</style>
</head>

<body>

<img src="logo.png" class="logo-fijo" alt="" onerror="this.style.display='none'">

<canvas id="matrix"></canvas>

<header>
<div class="search-box">
<span class="search-icon">
<svg width="16" height="16" viewBox="0 0 24 24" fill="none">
<circle cx="11" cy="11" r="7" stroke="#94a3b8" stroke-width="2"/>
<line x1="16.5" y1="16.5" x2="21" y2="21" stroke="#94a3b8" stroke-width="2"/>
</svg>
</span>
<input type="text" placeholder="Buscar plan...">
</div>

<span class="cart-icon" onclick="toggleCarrito()">🛒<span id="contador">0</span></span>
</header>

<section class="section">
<h2>Desarrollado por Santiago Haquet</h2>
<p>Hola soy Santi y les doy la bienvenida a mi pagina web.</p>
<p>Esta pagina web se hizo para un Proyecto final espero y les guste</p>
</section>

<section class="section">
<h2>Planes</h2>

<div class="cards">
<div class="card"><h3>Básico</h3><p>$1200</p><button onclick="agregar('Básico',1200)">Seleccionar</button></div>
<div class="card"><h3>Emprendedor</h3><p>$2000</p><button onclick="agregar('Emprendedor',2000)">Seleccionar</button></div>
<div class="card"><h3>Pro</h3><p>$2800</p><button onclick="agregar('Pro',2800)">Seleccionar</button></div>
<div class="card"><h3>Negocio</h3><p>$4000</p><button onclick="agregar('Negocio',4000)">Seleccionar</button></div>
<div class="card"><h3>Premium</h3><p>$6000</p><button onclick="agregar('Premium',6000)">Seleccionar</button></div>
<div class="card"><h3>Empresarial</h3><p>$9000</p><button onclick="agregar('Empresarial',9000)">Seleccionar</button></div>
</div>

</section>

</section>

<div id="carrito">
<h2>Carrito</h2>
<ul id="lista"></ul>
<h3>Total: $<span id="total">0</span></h3>
<button onclick="comprar()">Enviar pedido</button>
</div>

<div id="toast">Agregado</div>

<script>
let total=0,contador=0;

const lista=document.getElementById("lista");
const totalEl=document.getElementById("total");
const contadorEl=document.getElementById("contador");
const carrito=document.getElementById("carrito");
const toast=document.getElementById("toast");

function agregar(n,p){
let li=document.createElement("li");
li.innerHTML=n+" - $"+p;
lista.appendChild(li);
total+=p;contador++;
totalEl.textContent=total;
contadorEl.textContent=contador;

toast.style.display="block";
setTimeout(()=>toast.style.display="none",1500);
}

function toggleCarrito(){
carrito.classList.toggle("active");
}

function comprar(){
let msg="Pedido:\n"+lista.innerText+"\nTotal $"+total;
let numero="276 107  7938";
window.open("https://wa.me/"+numero+"?text="+encodeURIComponent(msg));
}

/* MATRIX JAPONESA */
const c=document.getElementById("matrix");
const ctx=c.getContext("2d");

c.width=window.innerWidth;
c.height=window.innerHeight;

let letras="サンティアゴ・ハケット・ヘルナンデス";

let fontSize=14;
let columns=Math.floor(c.width/fontSize);
let drops=Array(columns).fill(1);

setInterval(()=>{
ctx.fillStyle="rgba(0,0,0,0.03)";
ctx.fillRect(0,0,c.width,c.height);

ctx.fillStyle="#22ff88";
ctx.font=fontSize+"px monospace";

for(let i=0;i<drops.length;i++){
let text=letras[Math.floor(Math.random()*letras.length)];

ctx.fillText(text,i*fontSize,drops[i]*fontSize);

if(drops[i]*fontSize>c.height && Math.random()>0.97){
drops[i]=0;
}

drops[i]++;
}
},20);
</script>

<section class="section">
<h2>¿De que trata cada plan?</h2>

<div class="presentacion">

<img src="c:\Users\chiky\Downloads\Green Orange White Modern Group Project Presentation.png"width="600">
<img src="c:\Users\chiky\Downloads\Green Orange White Modern Group Project Presentation (1).png"width="600">
<img src="c:\Users\chiky\Downloads\Green Orange White Modern Group Project Presentation (2).png"width="600">
<img src="c:\Users\chiky\Downloads\Green Orange White Modern Group Project Presentation (3).png"width="600">
<img src="c:\Users\chiky\Downloads\Green Orange White Modern Group Project Presentation (4).png"width="600">
<img src="c:\Users\chiky\Downloads\Green Orange White Modern Group Project Presentation (5).png"width="600">

</div>
</section>
</body>
</html>
