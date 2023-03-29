### Hi there 👋

<!--START_SECTION:waka
name: Waka Time

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
          WAKATIME_API_KEY: ${{ secrets.waka_fd4acd9e-4dc9-4450-9253-e5604dc83135 }}
          GH_TOKEN: ${{ secrets.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 }}
          SHOW_PROFILE_VIEWS: "True"
          SHOW_TOTAL_CODE_TIME: "True"
          SHOW_OS: "True"
          SHOW_LANGUAGE: "True"
          SHOW_TIMEZONE: "True"
          SHOW_EDITORS: "True"
END_SECTION:waka-->
