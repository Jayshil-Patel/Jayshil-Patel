# Hi there 👋, my name is Jayshil Patel
I am curretly pursuing B.Tech 
I am currently learning Java and planning on pursuing web development, still, there is a lot to learn!!

## Skills
*XML 
*c
*SQLite
*python
*Java 
*JSON


- 🔭 I’m currently working on this page. 


![](https://komarev.com/ghpvc/?username=Jayshil-Patel&color=lightgrey)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Jayshil-Patel&hide=contribs,prs,issues)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Jayshil-Patel&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.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 }
