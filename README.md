<h1 align="center">Hangman Game in Python</h1>
<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/forca?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/forca?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/forca?color=56BEB8">
</p>
<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execution">Execution</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/seuusuario" target="_blank">Author</a>
</p>
<br>

## :dart: About

This project is an implementation of the classic Hangman game in Python. The objective is to guess the secret word, letter by letter, before being "hanged."

## :rocket: Technologies

This game was developed using:

- [Python](https://www.python.org/)
- [Jupyter](https://jupyter.org/)
- [Anaconda](https://www.anaconda.com/)

## :white_check_mark: Requirements

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com/) and [Python](https://www.python.org/) installed.

## :checkered_flag: Execution

```bash
bash
CopyEdit
# Clone the project
git clone https://github.com/gsoaresdz/forca.git

# Run the game
python forca.py

```

## **:video_game: How to Play**

1. Start the game by running the **`forca.py`** file.
2. Enter the letter you believe is part of the secret word.
3. Keep guessing letters until you either guess the word correctly or run out of attempts.

## **:memo: Functionalities**

- **`imprime_mensagem_abertura()`**: Displays a welcome message.
- **`carrega_palavra_secreta()`**: Loads a random secret word.
- **`inicializa_letras_acertadas(palavra)`**: Prepares the display for guessed letters.
- **`pede_chute()`**: Prompts the player for a guess.
- **`marca_chute_correto(chute, letras_acertadas, palavra_secreta)`**: Updates correctly guessed letters.
- **`desenha_forca(erros)`**: Updates the hangman drawing based on errors.
- **`imprime_mensagem_vencedor()`**: Displays a victory message.
- **`imprime_mensagem_perdedor(palavra_secreta)`**: Displays a defeat message and reveals the secret word.

## :memo: License

This project is under the MIT license. For more details, see the [LICENSE](LICENSE) file.

Made with :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

<a href="#top">Back to top</a>
