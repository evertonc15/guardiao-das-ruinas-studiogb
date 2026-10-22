
## Movimentação

O jogador pode movimentar o Prisioneiro horizontalmente utilizando o DPad.

O personagem também pode pular para alcançar plataformas e atravessar
obstáculos.

Em plataformas compatíveis, o jogador poderá pressionar para baixo junto
do botão de pulo para atravessá-las.

## Combate

O Prisioneiro utiliza uma espada como arma principal.

Existem três tipos de ataque:

### Ataque Simples

Golpe rápido realizado com a espada.

Características:

- rápido;
- alcance curto;
- utilizado contra inimigos comuns.

#### Representação visual

![[prisioneiro-ataque-simples.gif|156]]

A animação foi criada com 5 frames para representar um golpe rápido
e de curto alcance.

### Ataque Especial

Ataque realizado utilizando a energia vermelha absorvida pelas ruínas.

A espada recebe um brilho vermelho durante o golpe.

Características:

- maior alcance;
- efeito visual vermelho;
- ataque mais poderoso que o ataque simples.

#### Representação visual

![[prisioneiro-ataque-especial.gif|180]]

A animação utiliza energia vermelha para destacar visualmente o ataque
em relação ao golpe simples.

### Ataque Forte

Ataque carregado utilizando energia azul.

A espada muda visualmente durante a execução do golpe.

Características:

- maior dano;
- execução mais lenta;
- efeito visual azul.

#### Representação visual

![[prisioneiro-ataque-forte.gif|189]]

A animação utiliza energia azul e uma área visual maior para transmitir
a sensação de um golpe mais poderoso.

### Dano

![[prisioneiro-dano.gif|93]]

A animação de dano é utilizada para representar visualmente o momento em
que o Prisioneiro é atingido por um inimigo ou obstáculo.

### Derrota

![[prisioneiro-derrota.gif|88]]

A animação de derrota é utilizada quando a vida do Prisioneiro chega a zero.

## Troca de ataque

O jogador poderá alternar o tipo de ataque utilizando o botão Select.

## Vida

O jogador possuirá uma quantidade limitada de vida.

A vida será representada visualmente por corações exibidos no HUD.

### Coração cheio

![[HUD-coração.png|131]]

Representa um ponto de vida disponível.

### Coração vazio

![[HUD-coração-vazio.png|124]]

Representa um ponto de vida perdido.

Cada coração utiliza um sprite de 8×8 pixels.

Ao receber dano de inimigos ou obstáculos, a quantidade de vida será reduzida.

Quando a vida chegar a zero, o jogador será derrotado.