## Erick Sanches

<ul dir="auto">
<li><g-emoji class="g-emoji" alias="mortar_board" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f393.png">🎓</g-emoji> Formação: Cursando bacharel em Física pela UFRN.</li>
<li><g-emoji class="g-emoji" alias="woman_technologist" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f469-1f4bb.png">👩‍💻</g-emoji> Acadêmico: Técnico em Mecânica pelo IFRN.</li>
<li><g-emoji class="g-emoji" alias="books" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4da.png">📚</g-emoji> <g-emoji class="g-emoji" alias="pencil2" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/270f.png">✏️</g-emoji> <g-emoji class="g-emoji" alias="rocket" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f680.png">🚀</g-emoji> Início da jornada em programação: Março/2022.</li>
<li><g-emoji class="g-emoji" alias="mag_right" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f50e.png">🔎</g-emoji> Curiosidade: Sou monitor de Cálculo II e gosto de estudar Física Quântica e Relativística, espero aprofundar <br> meus conhecimentos em programação web para criar projetos pessoais e profissionais na área.</li>
</ul>
        
 <div>
  <a href="https://github.com/Ericksla7">

  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=Ericksla7&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ericksla7&layout=compact&langs_count=6&theme=tokyonight"/>
</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>
 
 <br>
 
  ## Para entrar em contato segue as redes abaixo!
 
<div> 
  <a href="https://www.instagram.com/erickkkslla7/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:ericksla1998@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
 
 
  name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: Ericksla7
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

</div>
