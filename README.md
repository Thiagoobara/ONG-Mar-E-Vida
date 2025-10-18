# Instituto Mar e Vida

Site institucional com foco em **acessibilidade** e **boas práticas web**.  
Desenvolvido para o projeto final da disciplina de Desenvolvimento Web.

---

## 💡 Sobre o Projeto

Este projeto simula o site oficial do Instituto Mar e Vida, ONG fictícia dedicada à preservação das tartarugas marinhas.  
O site facilita o engajamento de voluntários, a divulgação de ações ambientais e abre oportunidades para doações.  
Tudo foi pensado respeitando os princípios de **acessibilidade digital** (WCAG 2.1 AA).

---

## 🚀 Funcionalidades

- **Carrossel de imagens** acessível na página inicial e nos banners
- **Formulário de cadastro de voluntário** completo, com máscaras para CPF, telefone e CEP
- **Navegação por teclado** garantida em todos os componentes (links, botões, inputs)
- **Modo escuro e alto contraste**
- **HTML semântico** (`main`, `nav`, `header`, `footer`, `section`, etc)
- **Imagens otimizadas** (com texto alternativo e compressão)
- **Design responsivo** (funciona em computador e celular)
- **Compatível com leitores de tela**

---

## 🛠️ Estrutura de Branches – GitFlow

Utilizo o fluxo **GitFlow** para organizar o versionamento do projeto:

- **main:** versão de produção (site publicado)
- **develop:** versão de desenvolvimento (novas funções e testes)
- **feature/nome-da-feature:** desenvolvimento de novas funções
- **release/x.y.z:** preparação para releases
- **hotfix/x.y.z:** correções urgentes


## ▶️ Como rodar o projeto localmente

1. Baixe ou clone este repositório:
git clone https://github.com/Thiagoobara/ONG-Mar-E-Vida

yaml
Copiar código
2. Abra a pasta no VSCode ou outro editor.
3. Clique no arquivo `index.html` para abrir no navegador.

O site funciona direto, sem instalação.

---

## 🌐 Deploy

O site pode ser aberto localmente pelo arquivo `index.html`.  
Se publicado, acessar:
https://github.com/Thiagoobara/ONG-Mar-E-Vida

---

## ♿️ Acessibilidade (WCAG 2.1 AA)

- Navegação por teclado (Tab e Shift+Tab por todos links/botões/inputs)
- Foco visível nos elementos interativos
- Contraste mínimo de 4.5:1 verificado ([WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/))
- HTML semântico (`header`, `main`, `nav` etc)
- Imagens com atributo `alt` e textos descritivos
- Suporte a leitores de tela
- Modo escuro e alto contraste

---

## 📁 Organização de Arquivos

- `index.html`, `projetos.html`, `cadastro.html`
- `/css/style.css`
- `/js/mascaras.js`, `/js/carrossel.js`
- `/assets/imagens/`

---

## 📅 Changelog

- **v1.0.0:** Primeira entrega – site inicial com todas as funcionalidades
- **v1.1.0:** Acessibilidade, máscaras e otimização das imagens
- **v1.2.0:** Minificação dos arquivos e melhorias finais

---

## ✅ Checklist da entrega

- [x] Controle de versão com GitFlow
- [x] Commits semânticos e organizados
- [x] Releases usando versionamento semântico
- [x] Pull Requests, Issues e Milestones criadas
- [x] Acessibilidade WCAG 2.1 AA implementada
- [x] Otimização/minificação de arquivos
- [x] README profissional completo
