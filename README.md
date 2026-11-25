# Portfólio Profissional - Edson Nunes

**Aluno:** Edson Nunes

## 📋 Descrição do Portfólio
Este projeto é um portfólio pessoal responsivo desenvolvido para apresentar meu perfil profissional, minha formação acadêmica, as tecnologias que domino e os principais projetos práticos desenvolvidos durante o curso de Desenvolvimento de Sistemas.

## 🚀 Tecnologias Utilizadas
* **HTML5:** Estruturação semântica das seções da página.
* **CSS3:** Estilização personalizada, controle de proporção de imagens e animações interativas.
* **Bootstrap 5.3.3:** Construção do layout responsivo, sistema de grid, barra de navegação, carrossel de slides e cartões.
* **Devicon:** Biblioteca de ícones para representação visual das linguagens e ferramentas.

## 🌐 Link do Site Publicado
Acesse o portfólio online através do GitHub Pages:
https://dinho12165-cyber.github.io/portifolio/

## ⚙️ Funcionamento do Projeto
O site foi desenvolvido no formato de página única (*One Page*) com navegação fluida entre as seguintes seções:
1. **Menu de Navegação:** Fixo no topo (`sticky-top`) e adaptável para dispositivos móveis, permitindo acesso rápido a todas as seções.
2. **Carrossel (Slides):** Apresentação visual no topo da página com transição suave (`carousel-fade`) e controles de navegação.
3. **Perfil Profissional:** Exibe minha foto, resumo profissional, localização, área de interesse, objetivo e os ícones das tecnologias utilizadas.
4. **Formação Acadêmica:** Apresenta minha trajetória educacional e o curso técnico em andamento.
5. **Projetos:** Destaca três atividades práticas desenvolvidas no curso: **Cálculo de Notas**, **Controle de Níveis de Água** e **Portal de Entretenimento Digital**.
6. **Contato e Rodapé:** Disponibiliza botões diretos para envio de e-mail e acesso ao meu perfil no GitHub.

## ✨ Recursos Novos Adicionados
Para evoluir o projeto além do modelo base apresentado em aula, foram implementados dois recursos novos:
1. **Animações Interativas (Hover e Transições):** Efeito visual de elevação e sombra dinâmica ao passar o cursor sobre os cartões do site.
2. **Nova Seção de Formação Acadêmica:** Adição de uma seção exclusiva para detalhar a formação educacional, integrada ao menu principal de navegação.

### Como os recursos foram implementado:
* **Animações em CSS3:** Na tag `<style>`, foram aplicadas as propriedades `transition` e `transform: translateY(-8px)` associadas à pseudo-classe `:hover` na classe `.card`. Quando o usuário passa o mouse sobre qualquer cartão, ele desliza suavemente para cima e expande sua sombra (`box-shadow`), criando profundidade visual.
* **Seção Formação Acadêmica:** Foi criada uma nova `<section id="formacao">` estilizada com o sistema de grid do Bootstrap (`row` e `col-md-6`) e conectada diretamente à barra de navegação através de um novo link (`href="#formacao"`).
