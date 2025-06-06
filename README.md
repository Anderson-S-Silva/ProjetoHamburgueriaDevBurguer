
# 📄 README - Projeto DevBurguer

## 🧾 Informações do Projeto

**Professor:**  
Luciano Tadeu Pereira  

**Projeto:**  
**DevBurguer** – Site de uma hamburgueria com temática voltada ao universo Dev, trazendo um visual moderno e uma estrutura funcional com HTML, CSS, JavaScript, Bootstrap e PHP. O projeto foi desenvolvido como trabalho acadêmico com o objetivo de aplicar os conhecimentos adquiridos em desenvolvimento web e banco de dados.

---

## 📌 Descrição do Projeto

O **DevBurguer** é um site de hamburgueria inspirado no universo da programação. Ele apresenta um layout moderno, responsivo e funcional, com páginas que incluem:

- **Página Inicial (index.html)** com introdução à marca.
- **Cardápio (Cardapio.html)** com categorias de lanches, bebidas e sobremesas.
- **Pedidos (Pedidos.html)** com um formulário funcional para simular um pedido.
- **Sobre (Sobre.html)** com apresentação da equipe e missão da marca.
- **Contato (Contato.html)** com formulário que envia dados via PHP (process_contact.php) para simular envio de mensagem.

---

## 🛠️ Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript  
- Bootstrap 5  
- PHP  
- Banco de Dados SQL (via XAMPP/MySQL)

> Ferramentas utilizadas:
- XAMPP para hospedar localmente o servidor Apache e o banco de dados MySQL.

---

## 👥 Integrantes do Projeto

| Nome                         | RA       |
|------------------------------|----------|
| Bruno da Silva Santos        | 2995788  |
| Anderson dos Santos Silva    | 3017945  |
| Luis Miguel da Silva         | 2994319  |
| Euller Vilela Gonçalves      | 2965849  |
| Vitor Yudi Augusto           | 3224265  |
| Cleyton Braga Costa          | 2995774  |

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

- Ter o XAMPP instalado no computador.
- Ter um navegador atualizado (ex: Google Chrome).
- Ter um editor de código (opcional, ex: VSCode).

---

### Passo a Passo

1. **Instale o XAMPP**
   - Link para download: https://www.apachefriends.org/pt_br/index.html

2. **Abra o XAMPP e inicie os serviços:**
   - Apache
   - MySQL (se for necessário utilizar banco de dados no futuro)

3. **Copie a pasta do projeto**
   - Extraia o conteúdo do `.zip` e copie a pasta `ProjetoFaculdadeHamburgueria` para o diretório:
     ```
     C:\xampp\htdocs\
     ```

4. **Acesse o site pelo navegador**
   - Abra o navegador e digite na barra de endereços:
     ```
     http://localhost/ProjetoFaculdadeHamburgueria/index.html
     ```

5. **Testar funcionalidades**
   - Navegue entre as páginas: Cardápio, Sobre, Pedidos e Contato.
   - Preencha o formulário de contato para testar o envio com PHP (simulado).

> Obs: o formulário `process_contact.php` não grava em banco, mas simula o envio de dados usando PHP. A base está pronta para expansão com SQL se necessário.

---

ou clique aqui para visualizar o projeto: https://projeto-hamburgueria-dev-burguer.vercel.app/

### 📂 Estrutura de Arquivos

```
ProjetoFaculdadeHamburgueria/
├── index.html
├── Cardapio.html
├── Contato.html
├── Pedidos.html
├── Sobre.html
├── JavaScript.js
├── process_contact.php
├── style.css (se houver)
└── Imagens/ (caso incluídas)
```
