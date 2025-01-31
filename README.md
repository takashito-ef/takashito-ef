[![Typing SVG](https://readme-typing-svg.demolab.com?font=&pause=1000&color=00F70E&width=435&lines=Ol%C3%A1%2C+sou+Yung+Takashi%2C+ou+takashito;me+chame+como+preferir;sou+um+programador;adoro+fazer+malwares+em+C%2B%2B;estou+me+aventurando+em+C%2B%2B;poucos+ir%C3%A3o+me+entender;mas+isso+%C3%A9+apenas+por+hobbie%2C+XD)](https://git.io/typing-svg)

# Olá, me chamo Takashi! 
## Bem vindo ao meu perfil GitHub 👋

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
