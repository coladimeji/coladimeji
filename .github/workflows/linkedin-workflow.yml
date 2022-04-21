name: Latest linkedin activity
on:
  schedule:
    # Runs every 5 minutes
    - cron: '*/5 * * * *'
  workflow_dispatch:
  
jobs:
  update-readme-with-stack-overflow:
    name: Update this repo's README with latest activity from Linkedin
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: gautamkrishnar/blog-post-workflow@master
        with:
          comment_tag_name: "LINKEDIN ARTICLES"
          commit_message: "Updated readme with the latest stackOverflow data"
          feed_list: "https://www.linkedin.com/in/chrisoladimeji/recent-activity/posts/"

# ⚡  My Articles on Linkedin
<!-- LINKEDIN:START -->
<!-- LINKEDIN:END -->
