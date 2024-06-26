body {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    background-color: black; /* Define a cor de fundo do body como preto */
}

/*header*/

.container-topo {
    border: 5px solid black; /* Adiciona uma borda preta ao redor do header */
    text-align: center; /* Centraliza o conteúdo dentro do header */
    margin-bottom: 30px; /* Define uma margem inferior de 30px para o header */
}

.container-topo img {
    width: 180px; /* Define a largura da imagem do header como 15% do elemento pai */
    margin-top: 20px; /* Define uma margem superior de 20px para a imagem do header */
}

h1 {
    color: white; /* Define a cor do texto do h1 como branco */
    font-size: 25px; /* Define o tamanho da fonte do h1 como 30px */
    margin-top: 40px; /* Define uma margem superior de 60px para o h1 */
    font-weight: bold; /* Define a fonte do h1 como negrito */
}

/*main*/

.container-perfis {
    border: 5px solid black; /* Adiciona uma borda preta ao redor do container-perfis */
    width: 1000px; /* Define a largura do container-perfis como 1000px */
    margin: 0 auto; /* Centraliza o container-perfis horizontalmente na página */
    padding: 20px; /* Adiciona um preenchimento interno de 20px para o container-perfis */
    margin-bottom: 30px; /* Define uma margem inferior de 40px para o container-perfis */
}

ul {
    display: flex; /* Exibe a lista como um flex container */
    justify-content: center; /* Centraliza os itens da lista horizontalmente */
}

li {
    text-align: center; /* Centraliza o texto dentro dos itens da lista */
}

p {
    color: gray; /* Define a cor do texto do parágrafo como cinza */
    text-align: center; /* Centraliza o texto dentro do parágrafo */
    padding: 10px; /* Adiciona um preenchimento interno de 10px para o parágrafo */
    font-size: 20px; /* Define o tamanho da fonte do parágrafo como 20px */
}

.container-perfis img {
    border-radius: 10px; /* Adiciona um raio de borda de 10px às imagens do container-perfis */
    max-width: 150px; /* Define a largura máxima das imagens do container-perfis como 200px */
    border: 2px solid transparent; /* Adiciona uma borda transparente às imagens */
    transition: border-color 0.3s; /* Adiciona uma transição suave à cor da borda */
    text-align: center; /* Centraliza as imagens horizontalmente dentro do container-perfis */
    margin: 10px; /* Define uma margem de 20px para as imagens */
}

.container-perfis img:hover {
    border: 2px solid white; /* Adiciona uma borda branca ao redor da imagem ao passar o mouse */
}

.container-perfis img:hover + p {
    color: white; /* Muda a cor do texto do parágrafo para branco ao passar o mouse sobre a imagem */
}

/*botão*/

.button-container {
    border: 5px solid black; /* Adiciona uma borda preta ao redor do botão */
    display: flex; /* Exibe o container do botão como flex */
    justify-content: center; /* Centraliza o botão horizontalmente */
  }

button {
    background-color: black; /* Define a cor de fundo do botão como preto */
    color: white; /* Define a cor do texto do botão como branco */
    border-radius: 8px; /* Adiciona um raio de borda de 10px ao botão */
    border-color: white; /* Define a cor da borda do botão como branco */
    font-size: 13px; /* Define o tamanho da fonte do botão como 20px */
    width: 180px; /* Define a largura do botão como 250px */
    height: 45px; /* Define a altura do botão como 70px */
}

button:hover {
    background-color: white; /* Define a cor de fundo do botão como branco ao passar o mouse sobre ele */
    color: black; /* Define a cor do texto do botão como preto ao passar o mouse sobre ele */
    border-color: black; /* Define a cor da borda do botão como preto ao passar o mouse sobre ele */
}
