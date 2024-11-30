<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercício de CSS</title>
    <style>
        /* Estilo para links */
        a {
            color: red; /* Cor padrão do link */
            text-decoration: none; /* Remove o sublinhado */
        }

        a:hover {
            color: lemonchiffon; /* Cor do link quando o mouse passa por cima */
        }

        /* Estilo para parágrafos */
        p {
            font-family: Arial, sans-serif; /* Fonte padrão para todos os parágrafos */
        }

        h1 + p {
            font-weight: bold; /* Parágrafo logo após h1 ficará em negrito */
        }

        /* Estilo para a classe destaque */
        .destaque {
            font-family: Arial, sans-serif; /* Fonte padrão Arial */
        }

        .destaque p {
            font-weight: bold; /* Parágrafos com a classe destaque ficarão em negrito */
        }

        .destaque strong {
            color: red; /* Elementos <strong> dentro da classe destaque terão cor vermelha */
        }
    </style>
</head>
<body>
    <h1>Aprendendo CSS</h1>

    <p>Este é um exemplo básico para praticar estilos com CSS.</p>
    <p>
        Veja um exemplo de <a href="#">link</a>. Passe o mouse para ver a cor mudar!
    </p>

    <h1>Seção Especial</h1>
    <p>Este parágrafo ficará em negrito por estar logo após um h1.</p>

    <div class="destaque">
        <p>Este é um parágrafo especial com a classe <strong>destaque</strong>. Ele está em negrito.</p>
        <p>Se você usar um <strong>elemento strong</strong> dentro da classe destaque, ele ficará vermelho.</p>
    </div>
</body>
</html>
