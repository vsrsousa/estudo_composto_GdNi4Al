# Estudo do composto GdNi4Al (em desenvolvimento)


O efeito magnetocalórico consiste no aumento da temperatura do material ao se
aplicar um campo magnético externo, e quando o campo é retirado o material
tende a resfriar rapidamente. Sendo assim, estudo e desenvolvo aspectos teoricos
que descrevem esses tipos de materiais, sobretudo o composto GdNi4Al e futuramente pretendo 
estudar o composto GdNi2 e GdAl2. Nessa primeira abordagem foi incluso somente
a interação de troca e de Zeeman.

Assim, utilizo a linguagem Python para fazer cálculos numéricos (baseados
no método da autoconsciência) acerca de propriedades termodinâmicas do
sistema e comparar com resultados experimentais.

As propriedaeds termodinâmicas que mais interessam nesse caso é a variação
de entropia magnética e variação da temperatura adiabática, que caracterizam
o efeito magnetocalórico e seu regime de temperatura de funcionamento.

Na ultima versão do programa implementada adicionei a variação de temperatura
adiabática onde foi necessário incluir novos pacotes afim de conseguir fazer
a interpolação dos dados de maneira correta, além de adicionar a entropia da rede.
