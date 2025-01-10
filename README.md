# Desafio Front-End - Galeria de Fotos

Este projeto é uma **Galeria de Fotos Interativas** que utiliza a API **TMDb** para exibir filmes de diferentes estúdios (Disney, Pixar, Marvel). A galeria oferece uma interface onde o usuário pode pesquisar filmes e visualizar imagens e informações sobre eles.

## Tecnologias Utilizadas

- **HTML5**: Estrutura básica da página web.
- **CSS3**: Estilização da página.
- **JavaScript**: Lógica de funcionamento da aplicação e interações com a API.
- **API The Movie Database (TMDb)**: API para buscar informações e imagens sobre filmes.
- **GitHub**: Plataforma de hospedagem e versionamento do código-fonte.

## Funcionalidades

- Exibição de filmes de **Disney**, **Pixar** e **Marvel**.
- Capacidade de realizar buscas por nome de filme.
- Exibição de mensagens de erro caso nenhum filme seja encontrado ou se houver problemas na comunicação com a API.

## Como Rodar a Aplicação Localmente

Para rodar o projeto localmente e visualizar a aplicação no seu computador, siga os passos abaixo:

### 1. Clone o repositório

Primeiro, faça o clone do repositório para o seu computador local. Abra o terminal ou prompt de comando e execute o seguinte comando:

```bash
git clone https://github.com/MariliaA1403/Desafio-Front-end-Galeria-de-Fotos.git
Nota: Substitua MariliaA1403 pelo seu nome de usuário no GitHub, se necessário.

2. Obtenha uma chave de API do TMDb
A aplicação utiliza a API do TMDb para buscar informações sobre filmes. Para que a aplicação funcione corretamente, você precisa de uma chave de API pessoal. Para obter a chave, siga os passos abaixo:

Acesse o site do TMDb e crie uma conta, caso ainda não tenha.
Após criar a conta, acesse as configurações de API e gere uma chave de API.
Salve a chave gerada, pois você precisará dela para configurar a aplicação.
3. Configure a chave da API no código
Agora, insira a chave da API no código para que a aplicação funcione corretamente.

Abra o projeto clonado no seu editor de código preferido.
Localize o arquivo JavaScript (normalmente chamado script.js ou app.js).
Substitua a chave da API pela sua chave pessoal. No código, procure pela linha onde a chave é utilizada e substitua por:
javascript
Copiar código
const apiKey = 'sua-chave-da-api-aqui'; // Substitua pela sua chave da API
4. Abra o projeto no navegador
Agora que você configurou a chave da API, pode abrir o projeto no seu navegador:

Navegue até a pasta onde o projeto foi clonado.
Abra o arquivo index.html no seu navegador preferido (basta clicar com o botão direito sobre o arquivo e escolher "Abrir com" ou "Open with" e selecionar o navegador).
A aplicação será carregada e você verá a interface para pesquisar filmes de Disney, Pixar e Marvel.

5. Teste a funcionalidade de busca
Digite o nome de um filme na barra de pesquisa para visualizar as informações e imagens sobre ele. Caso o filme não seja encontrado, será exibida uma mensagem de erro, como "Nenhum filme encontrado".

Estrutura do Projeto
O projeto é composto pelos seguintes arquivos principais:

index.html: A estrutura da página web onde o conteúdo é exibido.
style.css: A estilização da página (cores, fontes, layout, etc.).
script.js: O arquivo JavaScript que contém a lógica da aplicação, incluindo a interação com a API e manipulação dos dados recebidos.
.
