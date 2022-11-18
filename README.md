<h1 align="left">Hi 👋, I'm dpy0912</h1>

<h3 align="left">程序员一枚</h3>

<p align="left"> 
  <img src="https://komarev.com/ghpvc/?username=dpy0912&label=Profile%20views&color=0e75b6&style=flat" alt="dpy0912" />
  <a href="https://www.oscs1024.com/project/oscs/dpy0912/SunOfBeacheRN?ref=badge_small" alt="OSCS Status">
    <img src="https://www.oscs1024.com/platform/badge/dpy0912/SunOfBeacheRN.svg?size=small"/>
  </a>
</p>

<p align = "left">
  <img src = "https://github-readme-stats.vercel.app/api?username=dpy0912&count_private=true&show_icons=true&theme=github" width="50%">
  <img src = "https://github-readme-streak-stats.herokuapp.com/?user=dpy0912&theme=vue" width="46%">
</p>

<p align = "left">
 <img src="https://activity-graph.herokuapp.com/graph?username=dpy0912&theme=react-dark">
</p>

<p align = "left" >
  <img src = "https://github-readme-stats.vercel.app/api/top-langs/?username=dpy0912&theme=xcode" width="30%">
  <img src = "https://github-profile-trophy.vercel.app/?username=dpy0912&theme=merko" width="50%" >
</p>

- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.dpy0912 }}

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
