<h1 align="center">Jogo da Forca em Python</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/forca?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/forca?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/forca?color=56BEB8">
</p>

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execução">Execução</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/seuusuario" target="_blank">Autor</a>
</p>

<br>

## :dart: Sobre

Este projeto é uma implementação do famoso jogo da Forca em Python. O objetivo é adivinhar a palavra secreta, letra por letra, antes de ser "enforcado".

## :rocket: Tecnologias

Este jogo foi desenvolvido utilizando:

- [Python](https://www.python.org/)
- [Jupyter](https://jupyter.org/)
- [Anaconda](https://www.anaconda.com/)

## :white_check_mark: Requerimentos

Antes de começar :checkered_flag:, você precisa ter o [Git](https://git-scm.com) e o [Python](https://www.python.org/) instalado.

## :checkered_flag: Execução

```bash
# Clone do projeto
git clone https://github.com/gsoaresdz/forca.git

# Execute o jogo
python forca.py
```

## **:video_game: Como jogar**

1. Inicie o jogo executando o arquivo **`forca.py`**.
2. Digite a letra que você acredita fazer parte da palavra secreta.
3. Continue adivinhando as letras até acertar a palavra ou até esgotar suas tentativas.

## **:memo: Funcionalidades**

- **`imprime_mensagem_abertura()`**: Mensagem de boas-vindas.
- **`carrega_palavra_secreta()`**: Carrega uma palavra aleatória.
- **`inicializa_letras_acertadas(palavra)`**: Prepara o display das letras.
- **`pede_chute()`**: Solicita o chute do jogador.
- **`marca_chute_correto(chute, letras_acertadas, palavra_secreta)`**: Atualiza letras acertadas.
- **`desenha_forca(erros)`**: Atualiza o estado da forca.
- **`imprime_mensagem_vencedor()`**: Mensagem de vitória.
- **`imprime_mensagem_perdedor(palavra_secreta)`**: Mensagem de derrota e revela a palavra.

## :memo: Licença

Este projeto está sob licença do MIT. Para obter mais detalhes, consulte o arquivo [LICENSE](LICENSE).

Feito com :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

&#xa0;

<a href="#top">De volta ao topo</a>


