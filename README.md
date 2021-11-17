# Detecção de Libras :hand: :call_me_hand:

## Sobre o projeto
O projeto O Libras utilizará uma rede neural para traduzir como libras em tempo real, o grupo para pessoas aprenderem a fazer e reconhecer libras. <br>
A IA foi treinada do zero por nós, desde as fotos (como quais associados para aplicar o Euclidiano e gerar o Conjunto de dados a partir do valor gerado pelo modelo matemático), até seu treinamento. Utilizamos apenas uma função pronta do mediapipe a qual cria um esqueleto quando uma mão é detectada, neste esqueleto possui pontos (os quais seriam articulações das mãos (que serão utilizados na aplicação do Euclidian)).

#### Como funciona      
Através de uma câmera, o usuário faz uma letra em libras com a mão, em que deseja que um IA identifique. <br>
A partir da letra em libras feito na câmera, um IA irá aplicar o que foi feito em seu treinamento e através das distâncias dos pontos (o ponto central (palma da mão) com as extremidades de cada dedo (a ponta dos dedos)) irá retornar a letra que ela reconheceu e o usuário irá perceber se a letra que o mesmo está fazendo corresponde ao que ele queria.

<hr>  
      
## Tecnologias utilizadas 
##### :snake: Python
##### :iphone: Android
<hr>  


## Objetivos
### IA
- [X] criação do DataSet
- [X] Aplicação de modelo matemático
- [X] Estudo dos dados
- [X] Treino e salvamento do modelo
- [X] Diferenciar letras a partir do modelo matemático
- [X] Printar na Tela a letra identificada
- [ ] Acréscimo de frases

### Servidor web
- [ ] Execução da Rede Neural


## Parte executada por mim
- [X] Criação das Imagens
- [X] Criação do Conjunto de Dados
- [X] Treinamento do Modelo
- [X] Printar a letra identificada
- [X] Exportação do Modelo (com Pickle)


## Próximos objetivos
- [ ] Treinar a IA para detectar frases

## Autores
- Victor Matheus Silva Lima (https://github.com/Victor-Silva98)
- Higor Frade (https://github.com/higorfrade)
- Jose Siqueira (https://github.com/js-siqueira)

## Orientador e Professor
Vandeir Aniceto Pinheiro @ UNIFAJ
