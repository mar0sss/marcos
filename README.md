
:root{
--branco-principal: #FFFFFF;
--cinza-secundario: #C0C0C0;
--botao-azul: #167BF7;
--cor-de-fundo: #00030C;
--fonte-principal: 'Inter';
}
body{
    background-color: var(--cor-de-fundo);
    color: var(--branco-principal);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}
* {
    margin: 0;
    padding: 0;
    }
    .principal {
        background-image: url(img/Background.png);
        background-repeat: no-repeat;
        background-size: contain;
        align-items: center;
        text-align: center;
    }
    .container {
        height: 100vh;
        display: grid;
        grid-template-columns: 30% 50%;
    }
    .container_aviso {
        font-size:12px;
        color: var(--cinza-secundario);
    }
    .container_botao {
        background-color: var(--botao-azul);
        border-radius: 5px;
        padding: 1em;
        color: var(--branco-principal);
        display: block;
        text-decoration: none;
        margin-bottom: 1em;
    }
    .container_titulo {
        font-size:28px;
        font-weight: 700;
    }
    .container_imagem {
        margin: 1em 0 2em 0;
    }
    .container_caixa {
        margin: 0 6em;
    }
    .botao_secundario {
        background-color: transparent;
        border: 2px solid var(--branco-principal);
    }            
    .secundario_imagem {
        width: 80%;
    }
    .secundario {
            align-items: center;
            margin:0 10em;
    }
    .descricao_titulo {
        font-weight: 700;
        font-size:48px;
        color:var(--branco-principal);
        margin-bottom: 0.1em;
    }
    .descricao_texto {
        color: var(--cinza-secundario);
    }
    .secundario_botao {
            display: inline-block;
            margin-top: 1em;
    }
    .container_descricao {
        padding: 2em;
    }
