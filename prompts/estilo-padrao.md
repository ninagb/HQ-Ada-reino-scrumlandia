# Estilo visual e texto padrão de estilo

## Ferramentas de IA generativa

As ilustrações são geradas no ChatGPT e no Gemini, alternando entre as duas ferramentas.

## Estilo escolhido

Ilustração digital de livro infantil, em estilo fofo e arredondado, com contornos marcados, cores vivas e saturadas e sombras suaves. O estilo foi escolhido por ser alegre, encantador e adequado ao público infantil, além de manter os personagens bem definidos mesmo em cenas pequenas, como as de metade dividida.

## Texto padrão de estilo

Todos os prompts das ilustrações usam o texto abaixo:

> Ilustração digital de livro infantil, estilo fofo e arredondado, com contornos marcados, cores vivas e saturadas e sombras suaves. Clima alegre e encantador.

E terminam com a orientação de formato correspondente ao tipo de quadro (conforme `paginas/formato.md`):

- **metade inteira:** "Imagem vertical, proporção 2:3. Sem textos, letras ou balões na imagem."
- **parte de cima ou de baixo de uma metade dividida:** "Imagem horizontal, proporção 3:2. Sem textos, letras ou balões na imagem."
- **página inteira:** "Imagem horizontal, proporção 3:2. Sem textos, letras ou balões na imagem."

A exceção são os elementos que fazem parte da própria cena, como o holograma do quadro Kanban, em que a IA pode gerar os textos, sem necessidade de que fiquem totalmente nítidos.

## Orientações de composição

### Até o capítulo 2

Os prompts pediam um espaço livre no céu, na parte de cima da imagem, para os balões de fala. Na montagem, os balões acabaram distribuídos perto de cada personagem que fala, e esse espaço central ficou sobrando em várias cenas. As imagens dos capítulos 1 e 2 foram mantidas, porque os balões couberam bem.

### A partir do capítulo 3

- **composição natural:** a cena ocupa a imagem toda, sem um grande espaço vazio reservado aos balões. O prompt pede apenas um pouco de espaço acima da cabeça de cada personagem que fala.
- **posição pela ordem das falas:** os personagens ficam posicionados da esquerda para a direita na ordem em que falam, seguindo a posição fixa definida no roteiro de cada capítulo.
- **sinais de movimento:** as cenas podem usar recursos típicos de HQ, como fumacinhas de corrida, linhas de giro, linhas de velocidade e brilhos, para dar mais vida e movimento às ilustrações.
- **quadros com narração:** como a moldura fica mais baixa por causa da barra de narração, o prompt pede que os personagens fiquem um pouco mais acima na cena.

## Testes realizados

Para escolher o estilo, a mesma cena foi gerada em três estilos diferentes: Ada e Kernel no gramado, olhando para a casinha na árvore. As imagens estão na pasta `ilustracoes`.

### Estilo A: aquarela suave

Ilustração de livro infantil em aquarela suave, com traços delicados, contornos finos e cores vivas e alegres. Clima aconchegante e acolhedor, com luz quente de fim de tarde.

### Estilo B: ilustração digital fofa (escolhido)

Ilustração digital de livro infantil, estilo fofo e arredondado, com contornos marcados, cores vivas e saturadas e sombras suaves. Clima alegre e encantador.

### Estilo C: lápis de cor e guache

Ilustração de livro infantil feita com lápis de cor e guache, com textura de papel visível, traços suaves à mão e cores vivas. Clima aconchegante e nostálgico.

### Descrição da cena usada nos testes

Uma menina de 8 anos, com cabelo castanho ondulado na altura dos ombros e uma fita branca no cabelo, usando vestido azul-celeste, meias brancas e sapatos pretos estilo boneca, em visual retrô. Ao lado dela, um cachorrinho pequeno de pelo caramelo com manchas brancas, orelhas caídas e coleira vermelha. Os dois estão no gramado, olhando para uma casinha de madeira no alto de uma grande árvore, com uma escada de corda.
