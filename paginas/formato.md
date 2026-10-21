# Formato da HQ

## Página

- **Tamanho:** A4.
- **Orientação:** horizontal (paisagem).
- **Ferramenta de montagem:** Canva.

## Disposição dos quadros

A página é dividida ao meio, na vertical, formando duas metades (esquerda e direita), como um livro aberto. A leitura segue da metade esquerda para a direita e, dentro de cada metade, de cima para baixo. Cada metade pode ser usada de duas formas:

- **metade inteira:** uma única cena ocupa toda a metade;
- **metade dividida:** a metade é dividida em duas partes, uma em cima e outra embaixo, com uma cena em cada.

Em momentos de destaque da história (como a chegada a ScrumLândia ou o encontro com a bruxa boa Ruby), uma única cena pode ocupar a página inteira.

Assim, cada página tem no mínimo uma e no máximo quatro cenas.

## Proporção das imagens

| Tipo de quadro | Proporção da imagem |
|---|---|
| Metade inteira | vertical, 2:3 |
| Parte de cima ou de baixo de uma metade dividida | horizontal, 3:2 |
| Página inteira | horizontal, 3:2 |

## Medidas das molduras

Medidas em milímetros, com margem de 5 mm nas bordas da página e espaço de 3 mm entre os quadros.

| Moldura | Largura | Altura | X | Y |
|---|---|---|---|---|
| Metade esquerda, inteira | 142 | 200 | 5 | 5 |
| Metade esquerda, parte de cima | 142 | 98,5 | 5 | 5 |
| Metade esquerda, parte de baixo | 142 | 98,5 | 5 | 106,5 |
| Metade direita, inteira | 142 | 200 | 150 | 5 |
| Metade direita, parte de cima | 142 | 98,5 | 150 | 5 |
| Metade direita, parte de baixo | 142 | 98,5 | 150 | 106,5 |
| Página inteira | 287 | 200 | 5 | 5 |

## Quadros com narração

A narração fica numa barra colada logo abaixo da imagem, dentro do espaço do quadro. Assim, a barra não cobre o desenho e fica claro a qual quadro a narração pertence. A moldura da imagem é reduzida na mesma medida da altura da barra.

Altura da moldura com narração = altura original − altura da barra.

Medidas para narração de uma linha (barra de 15,93 mm de altura):

| Quadro com narração | Moldura (L x A) | Moldura (X, Y) | Barra (L x A) | Barra (X, Y) |
|---|---|---|---|---|
| Metade esquerda, inteira | 142 x 184,07 | 5, 5 | 142 x 15,93 | 5, 189,07 |
| Metade direita, inteira | 142 x 184,07 | 150, 5 | 142 x 15,93 | 150, 189,07 |
| Metade esquerda, parte de cima | 142 x 82,57 | 5, 5 | 142 x 15,93 | 5, 87,57 |
| Metade esquerda, parte de baixo | 142 x 82,57 | 5, 106,5 | 142 x 15,93 | 5, 189,07 |
| Metade direita, parte de cima | 142 x 82,57 | 150, 5 | 142 x 15,93 | 150, 87,57 |
| Metade direita, parte de baixo | 142 x 82,57 | 150, 106,5 | 142 x 15,93 | 150, 189,07 |
| Página inteira | 287 x 184,07 | 5, 5 | 287 x 15,93 | 5, 189,07 |

Como a moldura fica mais baixa, a imagem é enquadrada manualmente para escolher a parte que aparece. Nas próximas ilustrações, os prompts dos quadros com narração devem pedir que os personagens fiquem um pouco mais acima na cena.

## Modelos de página

Para agilizar a montagem, foram criados no Canva seis modelos de página, que são duplicados e preenchidos a cada nova página da HQ:

| Modelo | Layout | Narração |
|---|---|---|
| 1 | metade esquerda inteira e metade direita dividida | sem barras de narração |
| 2 | metade esquerda dividida e metade direita inteira | sem barras de narração |
| 3 | metade esquerda inteira e metade direita dividida | com barra de narração em todos os quadros |
| 4 | metade esquerda dividida e metade direita inteira | com barra de narração em todos os quadros |
| 5 | página inteira | sem barra de narração |
| 6 | página inteira | com barra de narração |

Quando apenas alguns quadros da página têm narração, usa-se o modelo com barras: as barras que não serão usadas são removidas e as molduras desses quadros são estendidas manualmente até a altura original, ocupando o espaço que era da barra.

## Quantidade de páginas

| Parte | Páginas |
|---|---|
| Capa | 1 |
| Capítulo 1 | 3 |
| Capítulo 2 | 3 |
| Capítulo 3 | 3 |
| Capítulo 4 | 5 |
| Capítulo 5 | 4 |
| Página bônus | 1 |
| **Total** | **20** |

O capítulo 4 tem mais páginas por ser o mais longo e cheio de ação. O capítulo 5 tem uma página a mais que os iniciais para acomodar o encontro com Ruby, o desfecho e o retorno de Ada para casa.

## Ferramentas de IA generativa

As ilustrações são geradas no ChatGPT e no Gemini, alternando entre as duas ferramentas. Para manter a coerência visual, todos os prompts começam com o mesmo texto padrão de estilo, usam as imagens oficiais dos personagens como referência e respeitam a proporção de altura definida em `personagens/proporcoes.md`.

## Página de teste

O formato foi testado no Canva com uma página montada a partir das imagens oficiais dos personagens e de um dos testes de estilo, incluindo um balão de fala e uma caixa de narração. O resultado está em `pagina-teste.png`.

Fonte dos balões e da narração: Open Sans, tamanho 13.

O teste mostrou que as molduras do Canva cortam as imagens que não estão na mesma proporção do quadro. Por isso, as ilustrações das cenas devem ser geradas na proporção do quadro em que serão usadas, conforme a tabela de proporção das imagens.

A página de teste foi montada com margem de 10 mm e espaço de 6 mm entre os quadros. Durante a montagem dos capítulos 1 e 2, esses espaços se mostraram grandes demais e foram reduzidos para 5 mm e 3 mm, aumentando a área das ilustrações. Também foi criado o modelo de quadro com barra de narração colada abaixo da imagem, para que a narração não cubra o desenho, e foram definidos seis modelos de página para agilizar a montagem.
