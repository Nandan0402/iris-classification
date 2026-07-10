<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Iris Dataset Classification</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:linear-gradient(-45deg,#0f172a,#1e293b,#312e81,#0f766e);
background-size:400% 400%;
animation:bg 12s ease infinite;
color:white;
overflow-x:hidden;
}

@keyframes bg{
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}

.container{
width:90%;
max-width:1200px;
margin:auto;
padding:40px 0;
}

h1{
text-align:center;
font-size:50px;
margin-bottom:20px;
text-shadow:0 0 20px cyan;
}

.subtitle{
text-align:center;
font-size:20px;
margin-bottom:40px;
color:#ddd;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{

background:rgba(255,255,255,.08);
backdrop-filter:blur(15px);
padding:25px;
border-radius:20px;
transition:.5s;
transform-style:preserve-3d;
box-shadow:0 15px 35px rgba(0,0,0,.4);

}

.card:hover{

transform:rotateY(12deg) rotateX(8deg) translateY(-10px);
box-shadow:0 30px 60px rgba(0,255,255,.4);

}

.card h2{

margin-bottom:15px;
color:#00ffff;

}

.card ul{
padding-left:20px;
line-height:1.8;
}

.card p{
line-height:1.8;
}

.author{

margin-top:60px;
text-align:center;

}

.author img{

width:140px;
height:140px;
border-radius:50%;
border:5px solid cyan;
box-shadow:0 0 30px cyan;
transition:.5s;

}

.author img:hover{

transform:rotateY(360deg);

}

.author h2{

margin-top:20px;

}

.buttons{

margin-top:25px;

}

.btn{

display:inline-block;
padding:14px 28px;
margin:10px;
border-radius:40px;
background:cyan;
color:#000;
text-decoration:none;
font-weight:bold;
transition:.4s;

}

.btn:hover{

transform:scale(1.1);
background:white;

}

footer{

margin-top:50px;
padding:20px;
text-align:center;
color:#bbb;

}

</style>

</head>

<body>

<div class="container">

<h1>🌸 Iris Dataset Classification</h1>

<p class="subtitle">
Machine Learning Classification Project using Python & Scikit-Learn
</p>

<div class="grid">

<div class="card">

<h2>📌 Overview</h2>

<p>
This project demonstrates a machine learning classification workflow using the famous Iris dataset. The goal is to classify iris flowers into three species using their physical measurements.
</p>

</div>

<div class="card">

<h2>🧰 Technologies</h2>

<ul>

<li>Python</li>

<li>Pandas</li>

<li>NumPy</li>

<li>Matplotlib</li>

<li>Seaborn</li>

<li>Scikit-learn</li>

</ul>

</div>

<div class="card">

<h2>📂 Dataset</h2>

<ul>

<li>Dataset : Iris Dataset</li>

<li>Source : Scikit-Learn</li>

<li>Target : Iris Species</li>

<li>Classes : Setosa, Versicolor, Virginica</li>

</ul>

</div>

<div class="card">

<h2>🔑 Features</h2>

<ul>

<li>Sepal Length</li>

<li>Sepal Width</li>

<li>Petal Length</li>

<li>Petal Width</li>

</ul>

</div>

<div class="card">

<h2>🔄 Workflow</h2>

<ul>

<li>Import Libraries</li>

<li>Load Dataset</li>

<li>EDA</li>

<li>Train Test Split</li>

<li>Train Logistic Regression</li>

<li>Evaluate Model</li>

<li>Visualization</li>

</ul>

</div>

<div class="card">

<h2>🧠 Models</h2>

<ul>

<li>Logistic Regression</li>

<li>KNN</li>

<li>SVM</li>

<li>Decision Tree</li>

</ul>

</div>

<div class="card">

<h2>📊 Results</h2>

<p>

✔ High Accuracy Classification<br><br>

✔ Clear Class Separation<br><br>

✔ Beginner Friendly Machine Learning Project

</p>

</div>

<div class="card">

<h2>🚀 Conclusion</h2>

<p>

This project provides a strong foundation for understanding supervised machine learning classification problems and can easily be extended using more advanced algorithms.

</p>

</div>

</div>

<div class="author">

<img src="https://github.com/Nandan0402.png">

<h2>Nandan</h2>

<p>AI | Machine Learning | Full Stack Developer</p>

<div class="buttons">

<a class="btn" href="https://github.com/Nandan0402" target="_blank">GitHub</a>

<a class="btn" href="https://www.linkedin.com/in/nandan0402" target="_blank">LinkedIn</a>

</div>

</div>

<footer>

© 2026 Nandan | Iris Dataset Classification

</footer>

</div>

<script>

const cards=document.querySelectorAll(".card");

cards.forEach(card=>{

card.addEventListener("mousemove",e=>{

const x=e.offsetX/card.offsetWidth-.5;

const y=e.offsetY/card.offsetHeight-.5;

card.style.transform=

`perspective(800px)
rotateY(${x*25}deg)
rotateX(${-y*25}deg)
translateY(-10px)`;

});

card.addEventListener("mouseleave",()=>{

card.style.transform="perspective(800px) rotateY(0deg) rotateX(0deg)";

});

});

</script>

</body>
</html>
