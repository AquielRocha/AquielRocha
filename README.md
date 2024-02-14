

<p align="center">Hello! My name is Aquiel, I'm 21 years old and I've been passionate about technology since childhood. I'm always seeking knowledge and constantly improving my skills. I'm a fullstack developer, capable of handling both backend and frontend development.</p>&nbsp;

<div  align="center" style="margin-bottom:100px">
<img width=55% align="center"  src="https://github-readme-streak-stats.herokuapp.com?user=aquielrocha&theme=radical&mode=weekly" />
<img width=40% align="center" src="https://github-readme-stats-git-main-aquielrocha.vercel.app/api/top-langs/?username=rafaelalexandrino&show_icons=true&theme=radical&layout=compact" />
 </div>
 
 &nbsp;
 &nbsp;

## My Skills

#### Main Stack:

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)&nbsp;
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)&nbsp;
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)&nbsp;
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)&nbsp;



#### Studying in this moment:


#### Databases:

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;

#### Workstation Tools:

![VScode](https://img.shields.io/badge/vscode-4285F4?style=for-the-badge&logo=vscode&logoColor=white)&nbsp;

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)&nbsp;

&nbsp;
&nbsp;

## Contacts:

<div> 
<a href="https://www.instagram.com/quielzinnn" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>
<a href = "mailto:aquiel123@gmail.com"> <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/aquielrocha/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"  target="_blank"></a> 
</div>&nbsp;&nbsp;
 

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
          github_user_name: username #AquielRocha
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=8F0D87&height=120&section=footer"/>
