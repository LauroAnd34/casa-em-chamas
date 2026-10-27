# Herói das Chamas - Casa Virtual

Mini jogo feito somente com HTML (sem CSS e sem JavaScript) para o desafio "Casa em Chamas" da trilha de desenvolvimento web.

Você é um bombeiro e precisa encontrar o cômodo da casa em chamas onde ainda há uma pessoa. O jogo começa na rua e termina quando o jogador entra no cômodo certo.

## Como jogar

- Online: https://lauroand34.github.io/casa-em-chamas/
- No computador: baixe o repositório e abra o arquivo `index.html` no navegador.

## Como funciona

Cada cômodo da casa é uma página HTML e a navegação é feita com links (`<a href>`), seguindo a planta da casa:

| Cômodo | Saídas |
|---|---|
| Rua | Porta (sala), Janela (quarto) |
| Sala | Porta da frente (rua), Porta lateral (quarto), Corredor |
| Corredor | Sala, Cozinha |
| Cozinha | Corredor, Primeira porta (quarto), Segunda porta (banheiro) |
| Banheiro | Cozinha |
| Quarto da frente | Porta (sala), Janela (rua) |
| Quarto dos fundos | Destino final |
