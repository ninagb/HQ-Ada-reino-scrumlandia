# Bloco de referência dos personagens

## Por que este bloco existe

Durante a geração das ilustrações do capítulo 2, a IA foi perdendo a referência das imagens enviadas no início das conversas longas: trocou o espantalho pelo leão, mudou o cinto do PalhaByte e alterou a aparência do IA_go. Para compensar, os prompts precisavam ficar cada vez maiores.

A partir do capítulo 3, o processo passa a ser:

1. abrir uma conversa nova por capítulo (ou antes, se os personagens começarem a mudar);
2. na primeira mensagem, anexar as imagens oficiais dos personagens do capítulo e colar o bloco abaixo, apagando as linhas dos personagens e cenários que não aparecem no capítulo;
3. nas mensagens seguintes, usar prompts de cena curtos, descrevendo apenas cenário, ação, posição dos personagens e formato.

## Bloco para colar na primeira mensagem da conversa

Estou criando uma história em quadrinhos infantil e vou pedir várias ilustrações nesta conversa. Antes de começarmos, guarde estas referências e siga-as em TODAS as cenas. Não gere nenhuma imagem agora, apenas confirme que entendeu.

IMAGENS ANEXADAS: são as imagens oficiais dos personagens. Cada uma mostra um personagem diferente. Mantenha a aparência, as roupas, as cores e os traços de cada um exatamente como nelas, em todas as cenas, sem misturar os traços entre eles.

PERSONAGENS:
- ADA (ada.png): menina de 8 anos, com cabelo castanho ondulado na altura dos ombros e uma fita branca no cabelo. Usa vestido azul-celeste, meias brancas e sapatos pretos estilo boneca, num visual retrô.
- KERNEL (kernel.png): cachorrinho pequeno, de pelo caramelo com manchas brancas, orelhas caídas e coleira vermelha com uma plaquinha dourada.
- IA_GO (ia_go.png): robô pequeno e arredondado, com antena na cabeça com uma luzinha na ponta e uma tela no lugar do rosto, que mostra olhos expressivos. Mantenha o formato do corpo, da cabeça e as cores exatamente como na imagem oficial. Só segura objetos quando a cena pedir.
- PALHABYTE (palhabyte.png): ESPANTALHO robótico com altura de um adulto. Cabeça de saco de pano com olhos de LED azul e uma pequena lente de câmera acima de um dos olhos; chapéu de palha com faixa verde e uma pequena antena; camisa xadrez verde com botões em forma de teclas de teclado e um remendo de placa de circuito; calça marrom com remendos; mãos e joelhos de metal prateado; tufos de palha com fios de fibra óptica coloridos saindo da gola, das mangas e da barra da calça; CINTO DE CABOS ELÉTRICOS COLORIDOS amarrado com um nó, com um PENDRIVE USB pendurado. Ele NÃO é um leão.
- LEONBOT (leonbot.png): LEÃO robótico, de corpo laranja-acobreado com aparência metálica, juba feita de cabos coloridos e pequenas engrenagens nas patas. Anda em quatro patas. É grande como um leão de verdade, mas não gigante. LeonBot e PalhaByte são personagens completamente diferentes.
- BRUXA MÁ BUGBUG (bugbug.png): bruxa adulta e mais velha, alta e magra, mais trapalhona do que assustadora. Rosto fino e alongado, nariz comprido e pontudo, cabelo preto desgrenhado com uma mecha roxa, vestido roxo-escuro com detalhes verdes e chapéu pontudo com duas antenas de inseto. Pode aparecer voando numa vassoura.
- BRUXA BOA RUBY (ruby.png): bruxa adulta, alta e elegante, de pele morena, olhos verdes e cabelos longos, ondulados e acobreados, presos por uma tiara com rubi. Usa vestido vermelho cintilante, sapatinhos de rubi e uma varinha com um rubi na ponta.
- MÃE DE ADA (mae-da-ada.png): mulher adulta, de cabelo castanho preso num coque, com vestido florido e avental, no mesmo visual retrô da filha.
- JOANINHAS ROBÓTICAS: pequenas joaninhas de casco vermelho de metal, com luzinhas nas costas, do tamanho da mão de Ada.

PROPORÇÃO DE ALTURA: Kernel chega à altura do joelho de Ada. IA_go chega à altura do ombro de Ada. LeonBot, em quatro patas, tem as costas na altura do ombro de Ada e a cabeça um pouco acima da cabeça dela. A cabeça de Ada chega à altura do peito de PalhaByte, à altura da cintura de BugBug e à altura do peito de Ruby e da mãe.

CENÁRIOS RECORRENTES:
- REINO DE SCRUMLÂNDIA: árvores com folhas em forma de pixels coloridos, flores que brilham, rios de águas cintilantes e nuvens fofas.
- TERRAS DA BUGBUG: árvores retorcidas, céu acinzentado e joaninhas robóticas voando, mas com um clima ainda infantil, nunca assustador demais.
- ÁRVORE DOM: árvore mágica cujos galhos se dividem como os ramos de um diagrama e cujos frutos são dados coloridos, como os de jogos de tabuleiro.
- PONTE MIDDLEWARE: ponte cinza feita de conectores tecnológicos encaixados uns nos outros, como plugues e tomadas, com as conexões brilhando.
- REINO DA RUBY: campos coloridos e céu ensolarado, com trilhos dourados que levam ao castelo.
- CASTELO FIREWALL: castelo verde-esmeralda brilhante, protegido por um escudo transparente e cintilante, como uma bolha de luz.
- HOLOGRAMA DO QUADRO KANBAN: projeção azul que sai do tablet de IA_go, com três colunas ("A fazer", "Fazendo" e "Feito") e pequenos cartões. Os textos não precisam ficar totalmente nítidos.

ESTILO: ilustração digital de livro infantil, estilo fofo e arredondado, com contornos marcados, cores vivas e saturadas e sombras suaves. Clima alegre e encantador.

REGRAS PARA TODAS AS CENAS:
- inclua somente os personagens que a cena pedir;
- posicione os personagens da esquerda para a direita na ordem indicada em cada cena;
- use uma composição natural, ocupando a imagem toda, sem grandes espaços vazios; deixe apenas um pouco de espaço acima da cabeça dos personagens que falam;
- use sinais de movimento típicos de HQ quando a cena tiver ação, como fumacinhas de corrida, linhas de giro, linhas de velocidade e brilhos;
- não coloque textos, letras ou balões de fala na imagem, exceto em elementos que fazem parte da cena, como o holograma do quadro Kanban;
- respeite a orientação e a proporção pedidas em cada cena (vertical 2:3 ou horizontal 3:2).

## Modelo de prompt de cena

Cena [número] do capítulo [número]. Personagens, da esquerda para a direita: [lista]. Cenário: [descrição]. Ação: [o que acontece com cada personagem]. [Se tiver narração: deixe os personagens um pouco mais acima na cena.] Imagem [vertical, proporção 2:3 | horizontal, proporção 3:2].
