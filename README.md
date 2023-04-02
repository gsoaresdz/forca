# **Jogo da Forca**

Este projeto é uma implementação do famoso jogo da Forca em Python. O objetivo do jogo é adivinhar a palavra secreta, letra por letra, antes de ser enforcado.

## **Instalação**

Clone este repositório e execute o arquivo principal:

```bash
git clone https://github.com/seuusuario/jogo-da-forca.git
cd jogo-da-forca
python forca.py
```

## **Como jogar**

1. Inicie o jogo executando o arquivo **`forca.py`**.
2. Digite a letra que você acredita fazer parte da palavra secreta.
3. Continue adivinhando as letras até acertar a palavra ou até esgotar suas tentativas.

## **Funcionalidades**

O código inclui as seguintes funções:

- **`imprime_mensagem_abertura()`**: Imprime a mensagem de boas-vindas ao jogo da Forca.
- **`carrega_palavra_secreta()`**: Carrega uma palavra secreta aleatória de um arquivo de texto chamado **`palavras.txt`**.
- **`inicializa_letras_acertadas(palavra)`**: Inicializa uma lista com espaços vazios representando as letras da palavra secreta.
- **`pede_chute()`**: Pede ao jogador para digitar uma letra.
- **`marca_chute_correto(chute, letras_acertadas, palavra_secreta)`**: Atualiza a lista de letras acertadas com a letra correta, caso o jogador acerte o chute.
- **`desenha_forca(erros)`**: Desenha a forca de acordo com a quantidade de erros.
- **`imprime_mensagem_vencedor()`**: Imprime a mensagem de vitória.
- **`imprime_mensagem_perdedor(palavra_secreta)`**: Imprime a mensagem de derrota e revela a palavra secreta.
