# 2-tri-2
index:
<!DOCTYPE html>
<html lang="pt+br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>blog</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>blog tech</h1>
        <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
    </header>
    <main>
        <article>

            <img src="imagem-blog.png"
                alt="Logotipo oficial do blog de tecnologia e educação, exibindo símbolos de aprendizado e inovação digital em tons de azul e branco.">
    
            <div>
    
            </div>
            <h2>meu primeiro post</h2>
            <p class="artigo-autor">Por: Emanueli Muniz</p>
            <p>boas-vindas ao meu novo blog! aqui vou compartilhar dicas de programação e curiosiodades da área de
                tecnologia.</p>
            <button> 💙 <span>0</span></button>
            <button> 👍<span>0</span></button>
            </div>
            
            <div>


            <img src="imagem-blog.png"
            alt="Logotipo oficial do blog de tecnologia e educação, exibindo símbolos de aprendizado e inovação digital em tons de azul e branco.">

        <div>

        </div>
        <h2>meu primeiro post</h2>
        <p class="artigo-autor">Por: Emanueli Muniz</p>
        <p>boas-vindas ao meu novo blog! aqui vou compartilhar dicas de programação e curiosiodades da área de
            tecnologia.</p>
        <button> 💙 <span>0</span></button>
        <button> 👍<span>0</span></button>
        </div>
        
        <div>
        </article>
        <article>

            <img src="imagem-blog.png"
                    alt="Logotipo oficial do blog de tecnologia e educação, exibindo símbolos de aprendizado e inovação digital em tons de azul e branco.">
                </div>
            <h2>meu segundo post</h2>
            <p class="artigo-autor">Por: Emanueli Muniz</p>
            <p>boas-vindas ao meu novo blog! aqui vou compartilhar dicas de programação e curiosiodades da área de
                tecnologia.</p>
            <button> 💙 <span>0</span></button>
            <button> 👍<span>0</span></button>
            </div>
        </article>

    </main>

<script src="script.js"></script>
</body>

</html>

stlye.css:
header {
    background-color: #183C63;
    color: #FFFFFF;
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
    padding: 16px;
}

main {
    background-color: #FFFFFF;
    color: #183C63;
    max-width: 800px;
    margin: 0 auto;22142214
    padding: 16px;

    
}
 article{
    display: flex;
    
 }
img {
    width: 80px;
    height: 80px;
}

.artigo-autor {
    font-weight: bold;
}

script.js:
const botoes = document.querySelectorAll("button");
botoes.forEach(function (botao) {
    function botaoClicado() {
        console.log("fui clicado")
        let texto = botao.querySelector("span");
        texto.textContent++;

    }
})
