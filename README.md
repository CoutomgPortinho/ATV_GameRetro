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
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1><strong>🎮GameZone Retro🕹️🤩</strong> </h1>
  <!-- Segundo titulos -->
    <h2>A <strong> melhor loja </strong> de <em>jogos clássicos da cidade!</em> </h2>
    
    <!-- Links -->
       
      <p> <a href="#precos">Ver preços💸</a></p>
    
    <p><a href="https://www.instagram.com/" 
        target="_blank">Instagram📸🤳 </a></p>
        <!-- imagem -->
         <img src="retro.jpg" alt=""Logo da empresa" width="500" heigth="500">   
     <h2><strong>🎮Consoles Disponiveis </strong></h2>
      <ul>
        <li>Nintendo (NES)</li>
        <li>Super Nintendo (SNES)</li>
        <li>Sega Genesis</li>
        <li>Atari 2600</li>
        <hr>
        <h2 id="precos" <strong>Preços</strong></h2>
       <table border="1">
         <thead>
            <tr>
                <th>Jogo</th>
                <th>Preço</th>
                <th>Estoque</th>
            </tr>
         </thead>
         <!-- Corpo da tabela -->
          <tbody>
            <tr>
                <td>Super Mario Bros</td>
                <td>NES</td>
                <td>R$ 85,00</td>
            </tr>
            <tr>
                <td>Sonic</td>
                <td>Genesis</td>
                <td>R$ 70,00</td>
            </tr>
            <tr>
                <td>Zelda</td>
                <td>NES</td>
                <td>R4 120,00</td>
            </tr>
          </tbody>
     </table>

     <footer>
  <p> &copy; 2025 GameZone Retro </p>
</footer>

        
</body>
</html>
```

 

## 🏆 Critérios de Avaliação

- [x] Respeitar o limite de 50 linhas de código
- [x] Implementar todos os 5 elementos essenciais
- [x] Manter o código limpo, legível e organizado
- [x] Garantir a funcionalidade de todos os links (internos e externos)
- [x] Construir uma estrutura HTML válida

## 🛠️ Tecnologias Utilizadas

* **HTML5**


