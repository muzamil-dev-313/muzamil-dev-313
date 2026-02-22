<div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

<h1 align="center">Hi, I'm Muzamil 👋</h1>

<h3 align="left">👩‍💻  About Me</h3>

💻 Aspiring Web Developer  
🌱 Currently learning HTML, CSS, JavaScript & Python  
🎯 Goal: Become a professional Full-Stack Developer  

🛠 Technologies I'm Learning
- HTML
- CSS
- JavaScript
- Python

📌 Current Focus
Building strong fundamentals and real-world projects.
Consistency over perfection 🚀



###

<div align="left">
  <img src="https://skillicons.dev/icons?i=html" height="60" alt="html logo"  />
  <img width="12" />
  
  <img src="https://skillicons.dev/icons?i=css" height="60" alt="css logo"  />
  <img width="12" />
  
  <img src="https://skillicons.dev/icons?i=javascript" height="60" alt="javascript logo"  />
  <img width="12" />
  
  <img src="https://skillicons.dev/icons?i=py" height="60" alt="python logo"  />
  <img width="12" />
</div>

###

<div align="left">
  <a href="https://www.instagram.com/_.mz4_11__/"><img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  /> </a>

</div>




- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa

  
