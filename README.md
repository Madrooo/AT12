# Atividades de Programação Web

Repositório com 10 atividades práticas de **HTML e CSS**, desenvolvidas na disciplina de Programação Web. Cada atividade explora um grupo de tags e propriedades, e o `index.html` reúne tudo em uma página inicial com prévia, descrição e link para cada uma.

## Sobre o projeto

A página inicial lista as atividades em ordem, e cada bloco contém:

- Título da atividade
- Prévia em imagem (print da página)
- Descrição das tags e do CSS utilizados
- Botão com link para abrir a atividade
- Caixa de seleção para marcar as atividades já visitadas

## Tecnologias

- HTML5
- CSS3 (estilos inline e no `<style>`)

Não há JavaScript, frameworks ou dependências externas.

## Estrutura de pastas

```
AT12/
├── index.html          # Página inicial com o índice das atividades
├── README.md
└── view/
    ├── ATV1.html
    ├── ...
    ├── ATV10.html
    └── Img/
        ├── ATV1.png    # Prévias exibidas no index.html
        ├── ...
        ├── ATV10.png
        └── Diagrama1.jpeg
```

## Atividades

| # | Tema | Principais tags e recursos |
|---|------|----------------------------|
| 1 | Primeiros testes com tags | `<title>`, `<h1>` a `<h6>`, `<br>`, `<p>`, `<hr>`, comentários |
| 2 | Formatação de texto e estilos inline | `<sub>`, `<sup>`, `<b>`, `<strong>`, `<i>`, `<em>`, `<u>`, `<mark>`, `<small>`, `<del>`, atributos `style` e `title` |
| 3 | Página de notícia (Canal-Texugo) | `<header>`, `<article>`, `<footer>`, `<meta charset>`, `<meta viewport>`, `lang`, `&nbsp;` |
| 4 | Notícia com estilização | `color`, `font-family` e `font-size` com `style` inline |
| 5 | Galeria de imagens | `<fieldset>`, `<legend>`, `<img>`, `height` e `width`, CSS no `<style>` |
| 6 | Repetição da galeria | Mesma estrutura da atividade 5 |
| 7 | Coleção de botões | `<button>`, classes, gradiente, `border-radius`, `box-shadow`, `transition`, `:hover`, `:active` |
| 8 | Formulário de login | `<form>`, `<label>`, `<input>` (email e password), `required`, `placeholder`, `display: flex` |
| 9 | Login com links | Formulário da atividade 8 com seis links `<a href>` |
| 10 | Cadastro de produto | `<input>` dos tipos `file`, `text`, `number` e `date`, `rgba`, gradiente, botão animado |

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Madrooo/NOME-DO-REPOSITORIO.git
   ```
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` no navegador (duplo clique ou extensão *Live Server* do VS Code).

## Observações para a correção

- As caixas de seleção ao lado de cada atividade servem apenas para **marcação manual**. Elas não são marcadas automaticamente ao clicar no link e não salvam o estado, então voltam a ficar desmarcadas ao recarregar a página.
- Para abrir uma atividade em uma nova aba sem sair do índice, use o **botão do meio do mouse** (a bolinha de rolagem) sobre o link ou **Ctrl + clique**.

## Autor

**Matheus Oliveira Silva**
Estudante de Ciência da Computação no IFCE

- GitHub: [Madrooo](https://github.com/Madrooo)
- LinkedIn: [Matheus Silva](https://www.linkedin.com/in/matheus-silva-2299a330a/)
