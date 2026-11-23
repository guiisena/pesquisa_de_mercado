# Contexto

Esta pasta é o ambiente de trabalho de pesquisa e inteligência de mercado. Aqui
se estuda um nicho por vez: quem são os clientes, quem são os concorrentes,
quanto custa, quanto se cobra, como o mercado está crescendo ou encolhendo, o
que mudou nos últimos anos e onde existe espaço para entrar.

O nicho muda a cada estudo e vem no pedido. Enquanto ele não for dito, não
assuma nenhum.

## Como o trabalho é entregue

Cada estudo gera dois arquivos.

O primeiro é um painel em HTML, numa página só, para ler na tela e mostrar para
outras pessoas. Ele responde o essencial em poucos segundos de leitura:
gráficos, comparações, números grandes, pouca palavra. É o que alguém olha
antes de uma reunião.

O segundo é o relatório completo, com a profundidade que o painel não comporta:
como o mercado está estruturado, os concorrentes um a um, a faixa de preço
praticada e o que justifica cada faixa, o perfil e o comportamento do cliente,
as barreiras de entrada, o que está mudando e por quê, os riscos, e as
conclusões que se sustentam no que foi encontrado. Texto corrido, raciocínio
explicado, sem enfeite.

Abra os arquivos com o comando do sistema quando terminar (`start` no Windows,
`open` no macOS, `xdg-open` no Linux).

## Sobre os dados

Os números vêm de fontes verificáveis, com a fonte e a data ao lado de cada um.
Dado de 2019 citado como se fosse de hoje é erro grave, e número inventado para
completar um gráfico é pior ainda.

Quando a informação não existir publicamente, o certo é dizer que não existe.
Quando for estimativa, deixar claro que é estimativa e mostrar de onde ela sai.
Um estudo honesto com três lacunas declaradas vale mais do que um estudo
completo onde parte foi preenchida por conta própria.

Fontes originais antes de agregadores: dados oficiais, associações do setor,
relatórios das próprias empresas, pesquisa setorial. Quando duas fontes
discordam, mostre as duas e diga qual parece mais confiável.

Mercado brasileiro por padrão, com recorte regional quando o nicho for local.
Valores em reais.

## Postura

A pesquisa serve para decidir, então evite o tom de folheto. Diga o que o
mercado tem de ruim, onde a margem é apertada, quem já domina o espaço e por
que uma entrada pode dar errado. Uma conclusão desconfortável bem fundamentada
é o resultado mais útil que este trabalho pode produzir.

## O visual do painel

O painel precisa parecer trabalho de consultoria, não slide de palestra
motivacional. Tema claro, muito espaço em branco, pouca cor, nada de efeito.
Seriedade vem de alinhamento e tipografia, não de enfeite.

Fundo branco ou quase branco, texto quase preto, cinza médio para o que é
secundário. Uma única cor de destaque, sóbria, usada com parcimônia em pontos
que realmente merecem atenção. Vermelho e âmbar ficam reservados para risco e
alerta, e perdem o sentido se aparecerem em tudo.

Tipografia sem serifa, em poucos pesos, com números alinhados em colunas.
Títulos discretos, sem tamanhos exagerados. Conteúdo centralizado numa coluna
de no máximo 1100px. Blocos separados por linhas finas ou bordas de 1px, em vez
de sombras pesadas. Cantos levemente arredondados. Espaçamento generoso e
constante entre as seções.

Gráficos limpos, em SVG ou canvas desenhado à mão, sem depender de biblioteca
externa sempre que der. Eixos discretos, sem grade pesada, sem 3D, sem pizza de
muitas fatias, sem animação de entrada. Cada gráfico traz título, unidade, e a
fonte com a data logo abaixo, em corpo pequeno.

Números grandes ganham destaque com rótulo curto embaixo, e só quando o número
importa de verdade. Nada de gradiente, emoji, ícone decorativo ou sombra
colorida. O painel será projetado, então nada de texto em corpo minúsculo nem
cinza claro demais para ler de longe.
