#WeatherApp
####Aplicativo que pega a previsao do tempo para a próxima semana e popula uma Grid tkinter

![Foto do App rodando](https://github.com/guidolingip1/weatherApp/desktop.png) 


Criei este aplicativo por vontade de aprimorar meus conhecimentos em python.

O aplicativo foi desenvolvido da seguinte forma:

1 - Encontrei um website de previsão do tempo

2 - Instalei as bibliotecas de Web Scraping: requests e bs4

3 - Após eu pesquisei pela minha cidade/estado e copiei o html resultante
ou seja, sempre que eu entrar o link eu terei a previsao para a minha cidade

4 - Após isso eu inspecionei os elementos html da página escolhinda e utilizei a biblioteca BeautifulSoup (bs4 instalada anteriormente) para pegar as informações
Primeiro criei uma lista e adicionei todas as datas retornadas, lembrando que a cada dia a página muda e as datas se atualizam, porém como a página tem sempre o mesmo layout as informações retornadas serão as mesmas.
Depois uma lista para os dias da semana, uma para as temperaturas máximas e uma para as temperaturas mínimas.

5 - Já com todas as informações coletadas eu trabalhei nas impressões corrigindo strings defeituosas

6 - Quando toda parte de código estava feita, comecei a implementação de uma GUI utilizando a biblioteca tkinter do python.

Criei uma window = TK(), com as seguintes dimensoes (900x100)
Após adicionei 7 labels e 7 grids e posicionei os labels em suas respectivas grids

Por último apenas modifiquei o background color e as cores das labels, para deixar o app um pouco mais bonitinho aos olhos.
Para encontrar cores bonitas apenas pesquisei no google por tkinter colors palette.

Muito obrigado se você leu até aqui e se quiser o código me envie um email para guidolingip1@gmail.com
