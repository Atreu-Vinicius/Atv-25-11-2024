Neste exercício, o objetivo principal é aprender como adicionar e utilizar componentes no seu aplicativo React, além de como usar JSX para estruturar a visualização do seu componente. Ao final deste exercício, você será capaz de:

Adicionar componentes ao seu aplicativo React.
Usar JSX para definir as exibições de um componente.
Além disso, você irá praticar a criação de componentes reutilizáveis e dinâmicos, utilizando dados armazenados em estado e renderizando informações de maneira eficiente.

Estrutura do Exercício
1. Configuração Inicial
Primeiramente, é necessário fazer a configuração do projeto para que ele tenha todos os recursos que você vai utilizar ao longo do exercício. Isso envolve:

Baixar um arquivo ZIP fornecido, contendo imagens que serão usadas no projeto.
Criar uma estrutura de pastas dentro do seu projeto React para organizar as imagens e os componentes.
O arquivo de imagens será extraído e movido para a pasta public/assets, onde ficará acessível para uso no aplicativo. Essas imagens serão usadas para ilustrar os itens do menu em nosso componente.

2. Criação da Estrutura de Componentes
Dentro do seu projeto, você irá criar uma pasta chamada components dentro de src, onde os componentes React serão armazenados. Em seguida, será criado um novo componente denominado MenuComponent.js.

Este componente será responsável por renderizar uma lista de pratos, mostrando suas imagens, descrições, preços e outros detalhes. Ele utilizará o hook useState do React para armazenar os dados dos pratos e renderizar a lista dinamicamente.

3. Definição do Componente Menu
Dentro do arquivo MenuComponent.js, você irá definir o componente Menu, que realiza as seguintes ações:

Armazenamento de dados: A lista de pratos (dishes) é armazenada no estado do componente, utilizando o hook useState. Cada prato contém informações como nome, imagem, descrição, categoria e preço.

Renderização dinâmica: Usando o método map(), os dados de cada prato são iterados para gerar os elementos JSX correspondentes. Para cada prato, um item de menu com uma imagem, título e descrição é exibido.

Uso do Media do reactstrap: O componente Media do reactstrap é utilizado para criar uma estrutura de layout onde a imagem do prato é exibida ao lado do seu nome e descrição, criando um formato limpo e responsivo.

4. Atualização do Componente Principal (App.js)
Após criar o componente Menu, você deverá fazer a atualização no arquivo App.js para incluí-lo na renderização da aplicação.

No arquivo App.js, o componente Menu será importado e usado dentro da estrutura principal do aplicativo. Isso garante que o menu será exibido na tela principal quando o aplicativo for iniciado.

5. Limpeza do Arquivo CSS
Você também irá limpar o conteúdo do arquivo App.css, removendo estilos antigos, para que possa criar uma base limpa para os seus próprios estilos no futuro. Isso não é obrigatório, mas é uma boa prática para evitar conflitos de estilo.

6. Commit das Alterações
Após realizar todas as alterações no código, o exercício será finalizado com um commit no Git para registrar as modificações. A mensagem do commit será "Components Part 1", indicando que você completou a primeira parte do exercício de componentes.