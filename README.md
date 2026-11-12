# Meu Portfólio Profissional

## Nome do Aluno
[Arthur Gabriel de Queiroz Jacomassi]

## Descrição do Portfólio
Este projeto consiste no desenvolvimento e evolução do meu portfólio pessoal profissional. O site foi construído para apresentar minha trajetória, conhecimentos técnicos e principais projetos desenvolvidos ao longo do meu curso de formação, servindo como cartão de visitas digital para o mercado de trabalho.

## Tecnologias Utilizadas
* **HTML5** (Estruturação semântica)
* **CSS3** (Estilização e animações customizadas)
* **Bootstrap 5** (Framework CSS para responsividade e componentes)
* **Git e GitHub** (Controle de versão)
* **GitHub Pages** (Hospedagem e publicação do site)

## Link do Site Publicado
Acesse o portfólio online clicando aqui:  [https://arthur-prog129.github.io/portf-lio/]

## Explicação do Funcionamento do Projeto
O site possui uma estrutura de página única (*Single Page Application*) com navegação fluida através de um menu superior fixo (`navbar`). Ele é dividido nas seguintes seções:
1. **Perfil:** Apresentação pessoal e resumo profissional.
2. **Habilidades:** Destaque para as competências técnicas adquiridas.
3. **Projetos:** Grade de cartões (`cards`) exibindo os trabalhos realizados, com imagens ilustrativas e links.
4. **Contato:** Formulário interativo para envio de mensagens.

## Descrição do Recurso Novo Adicionado
Como recurso novo indo além do modelo base visto em aula, foi implementada uma **Seção de Habilidades dedicada** combinada com **efeitos visuais de transição e hover** (`transform: translateY` e sombras dinâmicas) tanto nos blocos de habilidades quanto nos cartões de projetos.

## Explicação de Como Esse Recurso Foi Implementado
1. **Estrutura HTML:** Foi adicionada uma nova tag `<section id="habilidades">` contendo uma grade (`row` e `col-md-4`) estruturada com classes do Bootstrap e ícones do *Bootstrap Icons*.
2. **Estilização CSS Customizada:** No bloco `<style>` da página, criei regras utilizando a propriedade `transition` combinada com o seletor `:hover`:
   ```css
   .project-card, .skill-box {
       transition: transform 0.3s ease, box-shadow 0.3s ease;
   }
   .project-card:hover, .skill-box:hover {
       transform: translateY(-5px);
       box-shadow: 0 10px 20px rgba(0,0,0,0.15);
   }
