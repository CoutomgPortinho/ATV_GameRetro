# 🕹️ Loja de Games Retro — Landing Page HTML

Este projeto consiste no desenvolvimento de uma página web simples e funcional em **HTML puro**, criada para apresentar uma loja temática de **games retro**. O desafio principal do projeto foi construir uma estrutura completa e acessível utilizando no máximo **50 linhas de código**.

## 🎯 Objetivo

Criar uma página HTML de **no máximo 50 linhas** que apresente a loja de games retro de forma clara, funcional e organizada.

## 📝 Requisitos do Projeto

### ✅ Elementos Essenciais

* **Estrutura básica:** Título e parágrafos contendo formatações de texto em **negrito** e *itálico*.
* **Lista:** Lista ordenada (`<ol>`) ou não ordenada (`<ul>`) contendo itens como consoles ou jogos.
* **Navegação:** Pelo menos um link interno (âncora `<a href="#...">`) e um link externo (`<a href="http...">`).
* **Imagem:** Uma imagem (`<img>`) relacionada ao tema de jogos retro.
* **Tabela:** Uma tabela (`<table>`) simples exibindo produtos e preços (mínimo de 3 itens).

## 💻 Código HTML (`index.html`)

Abaixo está a implementação completa da solução, estruturada em **28 linhas** (respeitando o limite máximo de 50 linhas):

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Loja Retro Games</title>
</head>
<body>
  <h1>Loja Retro Games</h1>
  <p>Bem-vindo! Encontre os <strong>melhores clássicos</strong> e consoles <em>inesquecíveis</em>.</p>
  
  <nav>
    <a href="#produtos">Ver Produtos</a> | 
    <a href="https://pt.wikipedia.org/wiki/Jogo_eletr%C3%B4nico" target="_blank">História dos Games</a>
  </nav>

  <h2>Consoles em Destaque</h2>
  <ul>
    <li>Super Nintendo (SNES)</li>
    <li>Sega Genesis / Mega Drive</li>
    <li>PlayStation 1</li>
  </ul>

  <img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?w=300" alt="Console Retro">

  <h2 id="produtos">Tabela de Preços</h2>
  <table border="1">
    <tr><th>Produto</th><th>Preço</th></tr>
    <tr><td>Super Mario World</td><td>R$ 150,00</td></tr>
    <tr><td>Sonic the Hedgehog</td><td>R$ 120,00</td></tr>
    <tr><td>Castlevania: Symphony of the Night</td><td>R$ 250,00</td></tr>
  </table>
</body>
</html>
```

## 🔧 Especificações Técnicas

| Item | Especificação | 
| :--- | :--- |
| **Limite de Código** | Máximo de 50 linhas de HTML | 
| **Tecnologia** | HTML5 puro (sem CSS/JS externo) | 
| **Tema** | Loja de Games Retro | 
| **Foco** | Funcionalidade e estrutura sintática em vez de estilo visual | 

## 🏆 Critérios de Avaliação

- [x] Respeitar o limite de 50 linhas de código
- [x] Implementar todos os 5 elementos essenciais
- [x] Manter o código limpo, legível e organizado
- [x] Garantir a funcionalidade de todos os links (internos e externos)
- [x] Construir uma estrutura HTML válida

## 🛠️ Tecnologias Utilizadas

* **HTML5**
* **Markdown** (Documentação)

## 🚀 Como Executar o Projeto

1. Clone este repositório para a sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abra a pasta do projeto.
3. Clique duas vezes no arquivo `index.html` para abri-lo no seu navegador web preferido.
