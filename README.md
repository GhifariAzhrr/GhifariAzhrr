## 👤 About Me 
Hello, I'm GhifariAzhr 👋

#### 🌐 Social
![https://instagram.com/ghifariazhrr_](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)
![https://x.com/GhifariAzhrr](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)
  <a href="https://youtube.com/@ghifariazhr" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  </a>
![https://linktr.ee/ghipuk_](https://img.shields.io/badge/linktree-39E09B?style=for-the-badge&logo=linktree&logoColor=white)
![https://www.threads.net/@ghifariazhrr_](https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=Threads&logoColor=white)



#### 📊 Github Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GhifariAzhrr&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=radical&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://streak-stats.demolab.com?user=GhifariAzhrr&locale=en&mode=daily&theme=radical&hide_border=false&border_radius=5" height="150" alt="streak graph"  />
</div>

#### 🚀 Play games with me

<img src="https://raw.githubusercontent.com/GhifariAzhrr/GhifariAzhrr/output/snake.svg" alt="Snake animation" />

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<!--
**GhifariAzhrr/GhifariAzhrr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
