### Hi there 👋

<!--
**AbelAmezcua/AbelAmezcua** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
<!-- [![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=AbelAmezcua)](https://github.com/anuraghazra/github-readme-stats)  -->

name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at every 12AM UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.e09178a1-8663-4509-a5d2-27da3e5ec0d3 }}
