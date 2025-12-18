# Agência de Viagens

repositório com avaliação para certificação no curso DEVStart Senai - Trilha 2, Projeto 1: Agência de Viagens

# Descrição do Projeto

O Projeto está disposto em 2 arquivos, sendo eles:

index.html => contém todo o 'esqueleto' do projeto,
Style.css => contém todo o estilo e formatações da landing page

Dos requisitos do projeto, estão incluidas:

| Requisito                       | Implementação no código                                                                        |
| :------------------------------ | :--------------------------------------------------------------------------------------------- |
| Banner dentro do `<main>`       | `<section class="banner">` está aninhada dentro de `<main id="home">`.                         |
| Navegação Minima ( `<nav>` )    | Presente no `<header>` com a classe `navegacao-principal`.                                     |
| Imagem de passeio no Banner     | Usado `background-image: url('https://picsum.photos/seed/europevilage/1600/800')` no CSS.      |
| Três seções nomeadas            | Seções com `id="minhaviagem"`, `id="nosencontre"`, `id="conselhos"`.                           |
| Navegação interna (Âncoras)     | Os links de navegação interno usam `href="#id"` (ex: `<a href="#minhaviagem">`).               |
| Navegação de volta ao topo/home | Cada seção tem um link de volta ao topo: `<a href="#home" class="voltar-topo">`.               |
| Mudar aparência no `:hover`     | Aplicado em todos os links (`<nav>`) e nos botões(`.botao-cta`, `voltar-topo`) no `style.css`. |
| Uso de `transition`             | Usado `transition: background-color 0.3s ease;` para suavizar o `:hover`                       |
| tags semânticas                 | Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.                    |
