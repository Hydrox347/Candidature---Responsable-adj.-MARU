Fais ça :

Dans index.html, remplace TOUT par ça :

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">

<style>

body{
margin:0;
padding:40px;
font-family:Arial;
background:linear-gradient(to bottom,#351700,#000);
color:white;
}

.card{
max-width:1100px;
margin:auto;
background:#0d0d0d;
padding:30px;
border-radius:30px;
box-shadow:0 0 40px rgba(255,120,0,.3);
}

.header{
text-align:center;
margin-bottom:30px;
}

.header h1{
font-size:60px;
margin:10px;
}

.orange{
color:#ff9500;
}

.grid{
display:flex;
gap:30px;
}

.left{
width:30%;
}

.left img{
width:100%;
border-radius:20px;
border:2px solid #ff9500;
}

.right{
flex:1;
}

.box{
background:#1a1008;
padding:15px;
border-radius:12px;
margin-bottom:12px;
display:flex;
justify-content:space-between;
}

.badge{
display:inline-block;
background:#7a4b00;
padding:8px 14px;
border-radius:999px;
margin:5px;
}

</style>
</head>

<body>

<div class="card">

<div class="header">

<img src="NOM-EXACT-DU-LOGO.png" width="100">

<h1>ANDREW SCOTT</h1>

<div class="orange">
Candidature — Adjoint Responsable M.A.R.U 🏔️🚑
</div>

</div>

<div class="grid">

<div class="left">

<img src="TA-PHOTO-MARU.png">

</div>

<div class="right">

<h2 class="orange">INFORMATIONS</h2>

Nom : Scott<br>
Prénom : Andrew<br>
Âge : 26 ans<br>
Ville : Los Santos

<br><br>

<h2 class="orange">COMPÉTENCES</h2>

<div class="badge">Gestion d'équipe</div>
<div class="badge">Leadership</div>
<div class="badge">Communication</div>
<div class="badge">Organisation</div>
<div class="badge">Sang-froid</div>

</div>

</div>

</div>

</body>
</html>
