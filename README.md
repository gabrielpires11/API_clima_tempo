#Api_Clima_Tempo

# Explicação do app.js

##Nas setes primeiras linhas, criando const para fazer as importações dos módulos necessários, como o axios para fazer requisições http no código e express.js para criação do servidor web.
##O const app faz a criação da aplicação Express, isso aconetece na nona linha.
##Na linha 12, definimos a porta que vai rodar o código (a porta que definimos é a porta 3000).
##Nas linhas de 15 e 18, configuramos os minddlewares(intermediária).
##Na linha 21, criamos uma const para traduzir as descrições do clima de inglês para português.
##Nas linhas 80 e 83, criamos uma rota para requisições de dados metereológicos e extraimos a cidadade dos parâmetros da requisição.
##Na linha 86, fizemos a requisição do link da API para acesso aos dados metereológicos.
##Nas linhas 91 e 107, criamos uma condição que se a resposta for 200 ele vai enviar a resposta obtendo os dados metereológicos e se a resposta não for 200 ele não vai envair a resposta com os dados metereológicos.
##Na linha 109, criamos um catch error para caso de erro de requisição, aparecer "Erro ao obter dados metereológicos", error"".

# Explicação script.js

##Da 1 até a linha 54, criamos várias funções as imagens do fundo do front-end, nessa função selecionasmos a tag body, definimos a imagem de fundo, ajustamos o tamanho da imagem e criamos no final uma condição para que a imagem evite repetir.
##Depois definimos As descrições de cada coisa do tempo, por exemplo clima com "ºC".
##Nas linhas 99 a 103, definimos qual imagem vai aparecer em todos os tipos de clima, por exemplo juntamos dois climas para aparecer uma imagem que represente o que está acontecendo.

# Explicação do style.css

##.forminteiro: Estiliza o contêiner do formulário, definindo transparência, borda, tamanho, alinhamento e sombra, além de aplicar uma transição suave.
##h1: Estiliza o título do formulário, definindo cor, fonte, tamanho e centralizando horizontalmente.
##formclima: Estiliza o formulário de consulta de clima, definindo preenchimento interno e alinhamento central.
##body: Estiliza o corpo da página, definindo cor de texto e imagem de fundo, além de ajustar sua altura e adicionar uma transição.
##.kdam-thmor pro-regular: Define a fonte para o texto.
##button: Estiliza o botão do formulário, definindo tamanho, borda, cor de fundo, sombra e cursor, além de adicionar uma transição.
##climaResult: Estiliza a exibição dos resultados do clima, definindo sua posição, tamanho e alinhamento.
##.icons e #descricaoIcon: Estiliza os ícones e a descrição dos resultados do clima.
##.lupa: Estiliza o ícone de lupa para pesquisa.
##Media queries: Ajustam o layout para telas menores, modificando principalmente tamanhos e posições de elementos para garantir uma melhor experiência em dispositivos móveis.

# Explicação do index.html

##Este código HTML cria uma página web para consultar o clima de uma cidade. Ele inclui um formulário para inserir o nome da cidade e um botão para enviar a consulta. Os resultados da consulta são exibidos na página, incluindo informações sobre temperatura, umidade e vento. Além disso, há um ícone de lupa para retornar à página inicial.
