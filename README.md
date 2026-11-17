name: Metrics
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [main]
permissions:
  contents: write
jobs:
  metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: YOUR_USERNAME
          template: classic
          base: header, activity, community, repositories, metadata
          plugin_isocalendar: yes
          plugin_languages: yes
          plugin_habits: yes
          plugin_topics: yes
