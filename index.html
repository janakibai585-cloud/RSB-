<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RSB Konkani Learning</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f2f2f2;
}

header{
background:#ff6600;
color:white;
text-align:center;
padding:15px;
}

nav{
background:#222;
text-align:center;
padding:10px;
}

nav button{
margin:5px;
padding:10px;
border:none;
border-radius:6px;
cursor:pointer;
color:white;
background:#444;
}

nav button:hover{
background:#666;
}

section{
display:none;
padding:20px;
}

.active{
display:block;
}

/* TABLE */
table{
width:100%;
border-collapse:collapse;
background:white;
margin-top:10px;
}

th,td{
border:1px solid #ddd;
padding:10px;
text-align:center;
}

th{
background:#ff6600;
color:white;
}

input,textarea{
width:100%;
padding:10px;
margin:5px 0;
border-radius:6px;
border:1px solid #ccc;
}

button.action{
padding:8px 12px;
border:none;
border-radius:6px;
cursor:pointer;
}

.add{background:green;color:white;}
.del{background:red;color:white;}

.card{
background:white;
padding:15px;
margin:10px 0;
border-radius:10px;
box-shadow:0 0 8px #ccc;
}

</style>

</head>

<body>

<header>
<h1>📖 RSB KONKANI LEARNING</h1>
<p>Konkani (RSB) • English • Kannada • Devanagari</p>
</header>

<nav>

<button onclick="show('home')">Home</button>
<button onclick="show('dict')">Dictionary</button>
<button onclick="show('sent')">Sentences</button>
<button onclick="show('hist')">History</button>

</nav>

<!-- HOME -->
<section id="home" class="active">
<div class="card">
<h2>🏠 Welcome</h2>
<p>Learn Konkani (RSB) in simple way</p>
</div>
</section>

<!-- DICTIONARY -->
<section id="dict">

<h2>📖 Dictionary</h2>

<input id="eng" placeholder="English">
<input id="kan" placeholder="Konkani (RSB) - Kannada">
<input id="dev" placeholder="Konkani (RSB) - Devanagari">

<button class="action add" onclick="addWord()">Add Word</button>

<table id="dictTable">

<tr>
<th>Konkani (RSB) - English</th>
<th>Konkani (RSB) - Kannada</th>
<th>Konkani (RSB) - Devanagari</th>
<th>Action</th>
</tr>

</table>

</section>

<!-- SENTENCES -->
<section id="sent">

<h2>💬 Sentences</h2>

<input id="seng" placeholder="English sentence">
<input id="skan" placeholder="Konkani (RSB) - Kannada sentence">
<input id="sdev" placeholder="Konkani (RSB) - Devanagari sentence">

<button class="action add" onclick="addSentence()">Add Sentence</button>

<table id="sentTable">

<tr>
<th>Konkani (RSB) - English</th>
<th>Konkani (RSB) - Kannada</th>
<th>Konkani (RSB) - Devanagari</th>
<th>Action</th>
</tr>

</table>

</section>

<!-- HISTORY -->
<section id="hist">

<h2>📜 History</h2>

<input id="title" placeholder="Title">
<textarea id="content" placeholder="Write history..."></textarea>

<button class="action add" onclick="addHistory()">Add History</button>

<div id="histList"></div>

</section>

<script>

/* NAVIGATION */
function show(id){
document.querySelectorAll("section").forEach(s=>s.classList.remove("active"));
document.getElementById(id).classList.add("active");
}

/* DATA */
let dict = JSON.parse(localStorage.getItem("dict")) || [];
let sent = JSON.parse(localStorage.getItem("sent")) || [];
let hist = JSON.parse(localStorage.getItem("hist")) || [];

/* RENDER */
function renderDict(){
let t = document.getElementById("dictTable");

t.innerHTML = `
<tr>
<th>Konkani (RSB) - English</th>
<th>Konkani (RSB) - Kannada</th>
<th>Konkani (RSB) - Devanagari</th>
<th>Action</th>
</tr>`;

dict.forEach((w,i)=>{
t.innerHTML += `
<tr>
<td>${w.eng}</td>
<td>${w.kan}</td>
<td>${w.dev}</td>
<td><button class="del" onclick="delWord(${i})">Delete</button></td>
</tr>`;
});
}

function renderSent(){
let t = document.getElementById("sentTable");

t.innerHTML = `
<tr>
<th>Konkani (RSB) - English</th>
<th>Konkani (RSB) - Kannada</th>
<th>Konkani (RSB) - Devanagari</th>
<th>Action</th>
</tr>`;

sent.forEach((s,i)=>{
t.innerHTML += `
<tr>
<td>${s.eng}</td>
<td>${s.kan}</td>
<td>${s.dev}</td>
<td><button class="del" onclick="delSent(${i})">Delete</button></td>
</tr>`;
});
}

function renderHist(){
let box = document.getElementById("histList");
box.innerHTML = "";

hist.forEach((h,i)=>{
box.innerHTML += `
<div class="card">
<h3>${h.title}</h3>
<p>${h.content}</p>
<button class="del" onclick="delHist(${i})">Delete</button>
</div>`;
});
}

/* ADD */
function addWord(){
dict.push({
eng:eng.value,
kan:kan.value,
dev:dev.value
});
localStorage.setItem("dict",JSON.stringify(dict));
renderDict();
}

function addSentence(){
sent.push({
eng:seng.value,
kan:skan.value,
dev:sdev.value
});
localStorage.setItem("sent",JSON.stringify(sent));
renderSent();
}

function addHistory(){
hist.push({
title:title.value,
content:content.value
});
localStorage.setItem("hist",JSON.stringify(hist));
renderHist();
}

/* DELETE */
function delWord(i){
dict.splice(i,1);
localStorage.setItem("dict",JSON.stringify(dict));
renderDict();
}

function delSent(i){
sent.splice(i,1);
localStorage.setItem("sent",JSON.stringify(sent));
renderSent();
}

function delHist(i){
hist.splice(i,1);
localStorage.setItem("hist",JSON.stringify(hist));
renderHist();
}

/* INIT */
renderDict();
renderSent();
renderHist();

</script>

</body>
</html>
