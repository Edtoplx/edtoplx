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
          WAKATIME_API_KEY: ${{ secrets.waka_97ebeda4-241f-4d4a-baa4-99dc0a0b083f }}
          GH_TOKEN: ${{ secrets.ghp_VKTO37IKPHea6zywTuuaXiGagAmInY3xPMV }}
          SHOW_PROFILE_VIEWS: "True"
          SHOW_TOTAL_CODE_TIME: "True"
          SHOW_OS: "True"
          SHOW_LANGUAGE: "True"
          SHOW_TIMEZONE: "True"
          SHOW_EDITORS: "True"
END_SECTION:waka-->
