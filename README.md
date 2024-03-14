<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Loja de Games Backend</title>
</head>

<body>
    <h1>Loja de Games Backend</h1>

    <p>Este é um projeto de backend para uma loja de games, desenvolvido utilizando o framework Spring, seguindo as melhores práticas recomendadas.</p>

    <h2>Configuração do Banco de Dados</h2>

    <p>O banco de dados da aplicação pode ser configurado no arquivo <code>application.properties</code>. Certifique-se de configurar corretamente o banco de dados de acordo com o ambiente de desenvolvimento.</p>

    <h2>Funcionalidades</h2>

    <h3>Produto</h3>

    <p>O recurso Produto oferece operações CRUD completas (Create, Read, Update, Delete) para manipular os dados dos produtos da loja. Além disso, os produtos estão classificados por categoria.</p>

    <h3>Categoria</h3>

    <p>O recurso Categoria também oferece operações CRUD completas para manipular os dados das categorias dos produtos da loja.</p>

    <h3>Relacionamento</h3>

    <p>Foi implementado um relacionamento do tipo One to Many entre as classes Categoria e Produto, garantindo que um produto pertence a uma única categoria.</p>

    <h2>Estrutura do Projeto</h2>

    <p>O projeto segue a estrutura padrão do Spring, dividido em camadas: Model, Repository e Controller.</p>

    <ul>
        <li><strong>Model:</strong> Responsável pela definição das entidades Produto e Categoria.</li>
        <li><strong>Repository:</strong> Responsável pelo acesso aos dados, com métodos para operações no banco de dados.</li>
        <li><strong>Controller:</strong> Responsável pela exposição dos endpoints da API e pelo tratamento das requisições.</li>
    </ul>

    <h2>Testes</h2>

    <p>A API foi testada utilizando a ferramenta Insomnia para garantir o correto funcionamento de todas as operações CRUD.</p>

    <h2>Repositório Remoto</h2>

    <p>O projeto está disponível em um repositório remoto no GitHub para facilitar o compartilhamento e colaboração. Certifique-se de clonar o repositório para ter acesso ao código-fonte.</p>

    <h2>Validação</h2>

    <p>Na entrega das atividades na Plataforma, verifique se as seguintes classes e interface foram desenvolvidas e validadas nas camadas especificadas:</p>

    <ul>
        <li>Produto: Camada model</li>
        <li>ProdutoRepository: Camada repository</li>
        <li>ProdutoController: Camada controller</li>
    </ul>

    <p>Se houver alguma dúvida, não hesite em consultar os instrutores da turma pelo Discord.</p>

    <p>Para mais detalhes sobre a implementação, consulte o código-fonte no repositório.</p>

    <hr>

    <p><em>Este README foi criado para fornecer uma visão geral do projeto e orientações básicas. Certifique-se de manter o README atualizado à medida que o projeto evolui.</em></p>
</body>

</html>

