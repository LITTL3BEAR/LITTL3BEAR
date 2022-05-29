
### Hi there 👋
Frameworks
![Angular](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/frameworks/angular.svg)
![Bootstrap](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/master/svg/dev/frameworks/bootstrap.svg)
![Node.js](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/master/svg/dev/frameworks/nodejs_larger.svg)

Languages
![CSS3](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/languages/css3.svg)
![HTML](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/languages/html.svg)
![JS](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/languages/js.svg)
![SCSS](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/languages/sass.svg)

Services
![GCP](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/services/google_cloud_platform.svg)
![NPM](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/services/npm.svg)

Tools
![Bash](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/tools/bash.svg)
![Docker](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/tools/docker.svg)
![VSCode](https://raw.githubusercontent.com/MikeCodesDotNET/ColoredBadges/4a38660afb7be89a6032218589b4454a1285c7f8/svg/dev/tools/visualstudio_code.svg)

- uses: LITTL3BEAR/Gith.5856
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
