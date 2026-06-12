# projeto-agrinho<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agrinho - Agronegócio e Meio Ambiente</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background: linear-gradient(to bottom, #87CEEB 0%, #BFEFFF 50%, #7CFC00 100%);
    min-height:100vh;
    overflow-x:hidden;
}

/* Céu */
.ceu{
    position:relative;
    height:300px;
}

/* Nuvens */
.nuvem{
    position:absolute;
    background:white;
    width:120px;
    height:60px;
    border-radius:50px;
    opacity:0.9;
    animation:mover 25s linear infinite;
}

.nuvem::before,
.nuvem::after{
    content:"";
    position:absolute;
    background:white;
    border-radius:50%;
}

.nuvem::before{
    width:60px;
    height:60px;
    top:-25px;
    left:20px;
}

.nuvem::after{
    width:70px;
    height:70px;
    top:-30px;
    right:15px;
}

.n1{
    top:50px;
    left:-150px;
}

.n2{
    top:120px;
    left:-300px;
    animation-duration:35s;
}

@keyframes mover{
    from{
        transform:translateX(0);
    }
    to{
        transform:translateX(150vw);
    }
}

/* Campo */
.campo{
    position:relative;
    height:200px;
    background:#3CB043;
}

/* Árvores */
.arvore{
    position:absolute;
    bottom:20px;
}

.tronco{
    width:25px;
    height:80px;
    background:#8B4513;
    margin:auto;
}

.copa{
    width:90px;
    height:90px;
    background:#228B22;
    border-radius:50%;
    margin-left:-32px;
}

.a1{ left:10%; }
.a2{ left:35%; }
.a3{ left:60%; }
.a4{ left:85%; }

/* Conteúdo */
.conteudo{
    background:rgba(255,255,255,0.95);
    max-width:1000px;
    margin:40px auto;
    padding:30px;
    border-radius:20px;
    box-shadow:0 0 15px rgba(0,0,0,0.2);
}

h1{
    color:#2E8B57;
    text-align:center;
    margin-bottom:20px;
}

h2{
    color:#228B22;
    margin-top:20px;
}

p{
    line-height:1.8;
    color:#333;
}

footer{
    text-align:center;
    padding:20px;
    color:white;
    font-weight:bold;
}
</style>
</head>

<body>

<div class="ceu">
    <div class="nuvem n1"></div>
    <div class="nuvem n2"></div>
</div>

<div class="campo">

    <div class="arvore a1">
        <div class="copa"></div>
        <div class="tronco"></div>
    </div>

    <div class="arvore a2">
        <div class="copa"></div>
        <div class="tronco"></div>
    </div>

    <div class="arvore a3">
        <div class="copa"></div>
        <div class="tronco"></div>
    </div>

    <div class="arvore a4">
        <div class="copa"></div>
        <div class="tronco"></div>
    </div>

</div>

<section class="conteudo">

    <h1>🌱 Agrinho: Agronegócio e Meio Ambiente 🌱</h1>

    <p>
        O agronegócio é uma das atividades mais importantes para a economia,
        sendo responsável pela produção de alimentos, fibras e matérias-primas.
        Ao mesmo tempo, é fundamental que a produção agrícola aconteça de forma
        sustentável, preservando a natureza para as futuras gerações.
    </p>

    <h2>🌳 Preservação Ambiental</h2>

    <p>
        A conservação das florestas, dos rios e da biodiversidade ajuda a manter
        o equilíbrio dos ecossistemas. Árvores são essenciais para a produção de
        oxigênio, proteção do solo e regulação do clima.
    </p>

    <h2>🚜 Tecnologia no Campo</h2>

    <p>
        O uso de tecnologias modernas permite aumentar a produtividade e reduzir
        impactos ambientais. Sistemas de irrigação inteligentes, drones e monitoramento
        por satélite ajudam os produtores a utilizar os recursos naturais de forma
        mais eficiente.
    </p>

    <h2>🌎 Sustentabilidade</h2>

    <p>
        Produzir alimentos respeitando o meio ambiente é um compromisso de todos.
        A agricultura sustentável promove o desenvolvimento econômico sem comprometer
        os recursos naturais necessários para as próximas gerações.
    </p>

</section>

<footer>
    Projeto Agrinho 2025 - Agronegócio e Meio Ambiente
</footer>

</body>
</html>
