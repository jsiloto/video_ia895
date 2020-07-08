# Line-by-Line Script
- E se eu te dissesse que compressão, 
como o seu jpeg e mp3 é "quase" a mesma coisa que machine learning
- Claro que isso é um exagero, mas veja a intuição

### Compressao
- Vamos pensar na compressão de uma imagem.
- Você transforma a imagem num arquivo, numa sequencia de bits
- e essa sequencia tem um tamanho minimo se a reconstrução for perfeita
- mas por exemplo com jpeg você consegue minimizar mais ainda permitindo um pouco de erro,
contanto que as caracteristicas principais ainda estejam lá

- para quem gosta do matematiquês isso significa que a gente quer minimizar o tamanho médio de l
dado um erro maximo médio.

### ML
- Mas e ML?
- ML é um termo guarda-chuva que significa muuuita coisa
- Mas em geral, o que você está tentando fazer é
 extrair algumas caracteristicas semanticas dos seus dados
 - Continuando com o exemplo da imagem
 - Um exemplo bem tipico seria dizer se existe uma pessoa ou não nela:
 1... tem uma pessoa,  0... não tem.
 - E mesmo que bem extrema, isso é uma forma de compressão, da imagem inteira em 1 bit
 - Continuando
 - A partir dessas informações semanticas, informações de conteudo, 
 a gente pode tentar recostruir a imagem original
 - E podemos ir adicionando mais informação, mais bits... com a cor do cabelo, 
 cor dos olhos, genero, cor da barba, forma do rosto, como um retrato falado
 - E a medida que a gente cresce esse código a nossa reconstrução também melhora
 - Então veja como isso já se parece com nosso problema original de compressão
 
### ML Inferencia
- Mas em ML a gente pode ir além
- A gente pode usar essas caracteristicas para outras coisas, 
outras tarefas como adivinhar a idade da pessoa.
- Algumas dessas caracteristicas podem ser uteis ou não,
 por exemplo, a cor dos olhos é irrelevante para a idade, mas a cor do cabelo é bem relevante
 - Então não é só uma questão de quais caracteristicas você escolhe para o seu código,
 mas também de quais você joga fora
 - Então eu te proponho um problema que é, qual o menor conjunto de caracteristicas (menor l)
 que te permite acertar a sua inferencia da idade?
 - E já da para ver que a gente tem uma cara bem parecida dos dois problemas
 
### Referencias
- Não está no escopo desse video, mas a formalizacao do que eu acabei de explicar
requer o uso de teoria de informação, e foi apresentada no artigo seminal em 1

 
 
 
 