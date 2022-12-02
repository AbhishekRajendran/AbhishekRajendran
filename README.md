### Hi Abhishek Here! 👋
A Data Scientist working in Kochi,Kerala,:india:India

- 🔭:chart_with_upwards_trend:Worked on Sales and CRM data retrieving valuable insights
- Now working on
   + Different types of retail datasets to gain more expertise
   + Developing dashboard for sales analysis challenge cases
   + 
- :e-mail: How to reach me: Email: ahishekrajendran2555@gmail.com , Linkedin - https://www.linkedin.com/in/abhishek-r-33912b193/ , Instagram  - a_b_his_he_k
-  
-->[![trophy](https://github-profile-trophy.vercel.app/?username=AbhishekRajendran&theme=onedark)]
on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          COMMIT_MSG: 'Specify a custom commit message'
          MAX_LINES: 10
