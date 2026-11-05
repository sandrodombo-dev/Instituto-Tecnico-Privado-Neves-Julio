<!DOCTYPE html>
<htmllang="pt-AO">
<head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Admin - Neves Júlio</title>
<style>
*{box-sizing:border-box;font-family:Poppins,Arial}body{margin:0;background:#f4f6fb;display:flex}
.sidebar{width:260px;background:#0a1931;color:#fff;min-height:100vh;padding:20px;position:fixed}
.sidebar img{width:80px;background:#fff;border-radius:12px;padding:5px}
.sidebar h2{font-size:15px;margin:10px 0}.sidebar a{display:block;color:#fff;text-decoration:none;padding:12px;border-radius:8px;margin:6px 0}
.sidebar a:hover,.active{background:#185adb}.main{margin-left:260px;flex:1;padding:25px;width:100%}
.card{background:#fff;border-radius:15px;padding:20px;box-shadow:0 5px 20px rgba(0,0,0,.07);margin-bottom:20px}
input,select,button{padding:11px;border-radius:8px;border:1px solid #ddd;width:100%;margin:6px 0}
button{background:#0a1931;color:#fff;font-weight:700;cursor:pointer;border:none}
button:hover{background:#185adb}.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:15px}
table{width:100%;border-collapse:collapse}th,td{padding:10px;border:1px solid #e5e8f0;text-align:center;font-size:13px}
.tag{padding:4px 8px;border-radius:15px;color:#fff;font-size:11px}.aprov{background:#1ca65e}.reprov{background:#d92d2d}
</style></head>
<body>
<div class="sidebar">
<img src="logo.jpg"><h2>NEVES JÚLIO<br>Admin Panel</h2>
<a class="active" href="#">Dashboard</a><a href="#alunos">Alunos</a><a href="#notas">Notas</a><a href="#horario">Horário 13H-18H05</a>
<p style="margin-top:40px;font-size:12px">Desenvolvido por<br><b style="color:#f1c40f">Sandro Orlando - 12GSI</b></p>
</div>
<div class="main">
<div class="grid">
<div class="card"><h3>Total Alunos</h3><h1 id="totalAlunos">0</h1><small>Capacidade: 5.000+</small></div>
<div class="card"><h3>Taxa Aprovação</h3><h1 id="taxaAprov">0%</h1></div>
<div class="card"><h3>Turma Ativa</h3><h1>12GSI - Tarde</h1></div>
</div>

<div class="card">
<h3>Adicionar / Excluir Aluno</h3>
<input id="nomeAluno" placeholder="Nome completo do aluno">
<input id="processo" placeholder="Nº Processo ex: 2027/001">
<button onclick="addAluno()">Adicionar Aluno</button>
<table id="tabelaAlunos"><tr><th>ID</th><th>Nome</th><th>Processo</th><th>Ação</th></tr></table>
</div>

<div class="card">
<h3>Lançar Notas e Desempenho Automático</h3>
<select id="selAluno"></select>
<select id="selDisc">
<option>RED.INF</option><option>MATEM</option><option>INGLÊS</option><option>PRO.TEC</option><option>FIS</option><option>T.L.P.</option><option>EMPREEN</option><option>TIC</option><option>OGI</option><option>TREI</option>
</select>
<div style="display:flex;gap:10px">
<input id="n1" type="number" min="0" max="20" placeholder="Nota 1">
<input id="n2" type="number" min="0" max="20" placeholder="Nota 2">
<input id="n3" type="number" min="0" max="20" placeholder="Nota 3">
</div>
<button onclick="lancarNota()">Lançar Nota</button>
<table id="tabelaNotas"><tr><th>Aluno</th><th>Disciplina</th><th>Média</th><th>Estado</th></tr></table>
</div>

<div class="card">
<h3>Horário Escolar - 12GSI - 13H00 às 18H05</h3>
<table>
<tr><th>HORA</th><th>2ª</th><th>3ª</th><th>4ª</th><th>5ª</th><th>6ª</th></tr>
<tr><td>13H00-13H45</td><td>RED.INF</td><td>MATEM</td><td>INGLÊS</td><td>RED.INF</td><td>PRO.TEC</td></tr>
<tr><td>13H50-14H35</td><td>RED.INF</td><td>MATEM</td><td>INGLÊS</td><td>RED.INF</td><td>PRO.TEC</td></tr>
<tr><td>14H40-15H25</td><td>FIS</td><td>PRO.TEC</td><td>T.L.P.</td><td>EMPREEN</td><td>MATEM</td></tr>
<tr style="background:#fff3b0"><td colspan="6">15H25-15H40 INTERVALO</td></tr>
<tr><td>15H40-16H25</td><td>FIS</td><td>PRO.TEC</td><td>T.L.P.</td><td>EMPREEN</td><td>MATEM</td></tr>
<tr><td>16H30-17H15</td><td>TIC</td><td>OGI</td><td>TREI</td><td>TIC</td><td>T.L.P.</td></tr>
<tr><td>17H20-18H05</td><td>TIC</td><td>OGI</td><td>TREI</td><td>TIC</td><td>T.L.P.</td></tr>
</table>
</div>
</div>

<script>
let alunos = JSON.parse(localStorage.getItem('alunosNJ')||'[]');
let notas = JSON.parse(localStorage.getItem('notasNJ')||'[]');
function save(){localStorage.setItem('alunosNJ',JSON.stringify(alunos));localStorage.setItem('notasNJ',JSON.stringify(notas)); render();}
function addAluno(){
 if(!nomeAluno.value||!processo.value) return alert('Preencha nome e processo');
 alunos.push({id:Date.now(), nome:nomeAluno.value, proc:processo.value}); nomeAluno.value=''; processo.value=''; save();
}
function delAluno(id){ alunos=alunos.filter(a=>a.id!=id); notas=notas.filter(n=>n.alunoId!=id); save();}
function lancarNota(){
 let m = ((+n1.value + +n2.value + +n3.value)/3).toFixed(1);
 let est = m>=10?'APROVADO':'REPROVADO';
 notas.push({alunoId:selAluno.value, alunoNome:selAluno.options[selAluno.selectedIndex].text, disc:selDisc.value, media:m, estado:est});
 save();
}
function render(){
 totalAlunos.textContent=alunos.length;
 tabelaAlunos.innerHTML='<tr><th>ID</th><th>Nome</th><th>Processo</th><th>Ação</th></tr>'+alunos.map(a=>`<tr><td>${a.id.toString().slice(-4)}</td><td>${a.nome}</td><td>${a.proc}</td><td><button onclick="delAluno(${a.id})" style="background:#d92d2d">Excluir</button></td></tr>`).join('');
 selAluno.innerHTML=alunos.map(a=>`<option value="${a.id}">${a.nome}</option>`).join('');
 tabelaNotas.innerHTML='<tr><th>Aluno</th><th>Disciplina</th><th>Média</th><th>Estado</th></tr>'+notas.map(n=>`<tr><td>${n.alunoNome}</td><td>${n.disc}</td><td>${n.media}</td><td><span class="tag ${n.estado=='APROVADO'?'aprov':'reprov'}">${n.estado}</span></td></tr>`).join('');
 let aprov = notas.filter(n=>n.estado=='APROVADO').length;
 taxaAprov.textContent = notas.length? Math.round(aprov/notas.length*100)+'%' : '0%';
}
render();
</script>
</body></html>

