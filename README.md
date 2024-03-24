# WebProject
Esse código HTML cria uma página web para um **portfólio pessoal** 

  1.**Estrutura Fundamental**:
    - O início do documento apresenta a declaração `<!DOCTYPE html>`, indicando sua natureza como um documento HTML5.
    - Todo o conteúdo da página é encapsulado pela tag `<html>`.
    - O cabeçalho da página é estabelecido através da tag `<head>`.
    - Com a tag `<meta name="viewport” content="width=device-width, initial-scale=1.0">`, a escala inicial da página é ajustada para se adequar ao dispositivo utilizado.
    - O título é definido pela tag `<title>Documento</title>`.

2. **Estilos em CSS**:
    - A formatação visual da página é especificada dentro da tag `<style>`.
    - A cor de fundo da página é configurada como **amarelo** (`background-color: #ffffcc;`).
    - O alinhamento do texto na página está centralizado (`text-align: center;`).

3. **Conteúdo da Página**:
    - O corpo principal do documento é designado pela tag `<body>`.
    - As seções “Projeto 1” e “Projeto 2” contêm links direcionando para os arquivos denominados “projeto1.html” e “projeto2.html", respectivamente.
    
A seção de “Entre em contato” contém os meios de contato (endereço de e-mail e número de telefone) e links para o GitHub e LinkedIn.

4. **Figura**:
    - A figura é mostrada com a etiqueta `<img>`.
    - O atributo `src` indica o local da figura (na pasta “imagens").
    - O atributo `width` estabelece a largura da figura como 100 pixels.
    - O atributo `alt` oferece um texto alternativo para a figura (se não for exibida).

5. **Tabelas**:
`<style>`: Aqui estão as diretrizes de estilo em CSS para a página. Elas influenciam a aparência dos elementos em HTML.

    - `table`: Define como a tabela será exibida, com bordas, ocupando 100% da largura e tendo uma borda sólida de 1px.
    - `th, td`: Determina o visual das células do cabeçalho e das células normais.
    - `th`: Aplica um fundo cinza ao cabeçalho.
    - `caption`: Indica que a legenda da tabela estará em negrito.

`<body>`: Conteúdo visível na página.
    - `<h2>Projeto 1</h2>`: Título secundário para a seção “Projeto 1".
    - `<table>`: Início da tabela.
        - `<caption>Tabela de Notas e Desempenho Escolar</caption>`: Legenda da tabela.
        - `<tr>`: Começo de uma linha na tabela.
            - `<th>`: Célula do cabeçalho (título da coluna).
            - `<td>`: Célula normal (conteúdo da tabela).
        - As linhas seguintes apresentam os dados das disciplinas (Matemática, Língua Portuguesa, Ciências) e suas respectivas notas.- A informação sobre o rendimento está localizada na última coluna, marcada como “Aprovado".
    - `</table>`: Indica o encerramento da tabela.

No gerral esse código cria uma página simples com informações pessoais e detalhes de contato. Para as tabelas  exibem notas e rendimento escolar para diferentes matérias, assim como na tabela dois mostra superpoderes de alguns personagens. As regras de estilo CSS definem a aparência da tabela. 
