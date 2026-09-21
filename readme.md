Tarefa 33 — Página pessoal com DaisyUI

Componentes DaisyUI utilizados
Navbar:

Foi usado no cabeçalho da página. Ele apresenta o nome e um botão que direciona para a seção de contato.

Hero:

Foi usado na seção de apresentação. Ele o nome, área de interesse e apresenta uma breve descrição.

Badge:

Foram utilizados três badges para destacar habilidades e área de interesse:

HTML
Tailwind CSS
JavaScript

Foram usadas diferentes variações, como badge-primary, badge-outline e badge-secondary.

Card:

Foram criados três cards na seção de projetos. Cada card possui:

título
descrição
botão de ação
card-body

Os projetos apresentados são CopaRacing(um projeto pessoal), Site IFRN e uma representação para o JavaScript.

Button:

Foram usados diferentes estilos de botões,  btn-primary, btn-secondary e btn-outline.

Input:

Na seção de contato foram utilizados dois campos de formulário: nome e e-mail, utilizando o componente input do DaisyUI.

Justificativa de escolha:

Para o cabeçalho, utilizei o componente navbar porque ele é adequado para organizar a identificação da página e uma ação de contato de forma simples e direta.

O hero foi utilizado na seção de apresentação porque permite destacar as principais informações sobre mim logo no início da página, funcionando como uma área de destaque.

Pontos de ajuste com Tailwind:

O DaisyUI foi utilizado como base dos componentes, mas algumas classes do Tailwind foram adicionadas para ajustar o layout.

Um exemplo é a seção de projetos:

<div class="grid grid-cols-1 md:grid-cols-3 gap-6">

Essas classes foram utilizadas para organizar os três cards em grade responsiva. Em telas menores, os cards ficam em uma coluna e, em telas maiores, passam para três colunas.

Outro:

<div class="flex justify-center gap-2 flex-wrap">

Essas classes foram utilizadas para organizar os badges e permitir que eles quebrem de linha quando a tela for menor.

Reflexão sobre os temas:

Testei os temas light e dark através do atributo data-theme.

O tema light ficou melhor com a proposta da página pessoal porque deixa as informações mais claras e facilita a visualização dos projetos, textos e campos do formulário.

Mesmo assim, o tema dark também funciona corretamente e oferece uma aparência diferente para a página.

Para testar os temas, foi alterado o atributo:

<html lang="pt-BR" data-theme="light">

para:

<html lang="pt-BR" data-theme="dark">