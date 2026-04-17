<style>

body{
background:#05070d;
color:#d9ffe9;
font-family:sans-serif;
margin:40px;
}

.tab input{
display:none;
}

.tab-buttons{
display:flex;
gap:15px;
margin-bottom:25px;
}

.tab-buttons label{
padding:12px 26px;
background:#07140c;
border:2px solid #22c55e;
border-radius:8px;
cursor:pointer;
color:#86efac;
font-weight:bold;
transition:0.2s;
}

.tab-buttons label:hover{
background:#14532d;
color:white;
box-shadow:0 0 10px #22c55e;
}

.content{
margin-top:20px;
}

.tab-content{
display:none;
}

#profile:checked ~ .content #profile-content{
display:block;
}

#project:checked ~ .content #project-content{
display:block;
}

.card{
background:#07140c;
border-radius:14px;
padding:22px;
margin-bottom:25px;
border:1px solid #22c55e;
box-shadow:0 0 15px rgba(34,197,94,0.3);
}

.project-container{
display:flex;
gap:25px;
flex-wrap:wrap;
}

.project-card{
background:#07140c;
padding:18px;
border-radius:12px;
width:260px;
border:1px solid #22c55e;
transition:0.25s;
box-shadow:0 0 10px rgba(34,197,94,0.25);
}

.project-card:hover{
transform:translateY(-6px);
box-shadow:0 0 20px rgba(34,197,94,0.6);
}

.skill-container{
display:flex;
gap:12px;
margin-top:10px;
}

.skill{
padding:8px 18px;
background:#07140c;
border:1px solid #22c55e;
border-radius:8px;
color:#86efac;
font-weight:bold;
box-shadow:0 0 8px rgba(34,197,94,0.4);
}

.github-btn{
display:inline-block;
margin-top:10px;
padding:6px 14px;
background:#07140c;
border:1px solid #22c55e;
border-radius:6px;
color:#86efac;
text-decoration:none;
font-size:13px;
}

.github-btn:hover{
background:#14532d;
box-shadow:0 0 8px #22c55e;
}

h1{
color:#4ade80;
}

h2{
color:#86efac;
margin-top:30px;
}

h3{
color:#bbf7d0;
}

p{
color:#d1fae5;
font-size:14px;
}

</style>


<div class="tab">

<input type="radio" name="tab" id="profile" checked>
<input type="radio" name="tab" id="project">

<div class="tab-buttons">
<label for="profile">프로필</label>
<label for="project">프로젝트</label>
</div>


<div class="content">


<div id="profile-content" class="tab-content">

<div class="card">
<h1>김재원</h1>
<p>경북소프트웨어마이스터고등학교 | Game Developer</p>
<p>
Unity 엔진을 활용한 게임을 만드는 공부를 하고있습니다.
</p>
</div>

<div class="card">
<h2>기술 스택</h2>

<div class="skill-container">
<span class="skill">C</span>
<span class="skill">C#</span>
<span class="skill">Python</span>
</div>

</div>

</div>



<div id="project-content" class="tab-content">

<h2>개인 프로젝트</h2>

<div class="project-container">

<div class="project-card">
<h3>SenseSurvival</h3>
<p>2026-03-01 ~ 2026-06-01</p>
<p>생존 상황에서 눈치껏 행동하는 게임</p>

<a href="https://github.com/dashboard" target="_blank" class="github-btn">
GitHub
</a>

</div>

</div>


<h2>팀 프로젝트</h2>

<div class="project-container">

<div class="project-card">
<h3>Golss</h3>
<p>2025-12-01 ~ 2026-01-01</p>
<p>보스와 싸우는 게임</p>

<a href="https://github.com/kimu3chan/Golss" target="_blank" class="github-btn">
GitHub
</a>

</div>

<div class="project-card">
<h3>Swine's Forest</h3>
<p>2026-01-01 ~ 2026-02-01</p>
<p>플레이어의 행동이 보스에게 영향을 끼치는 게임</p>

<a href="https://github.com/dashboard" target="_blank" class="github-btn">
GitHub
</a>

</div>

<div class="project-card">
<h3>사두용미</h3>
<p>2026-09-01 ~ 2026-12-01</p>
<p>2D 보스러쉬게임</p>

<a href="https://github.com/dashboard" target="_blank" class="github-btn">
GitHub
</a>

</div>

</div>

</div>


</div>
</div>
