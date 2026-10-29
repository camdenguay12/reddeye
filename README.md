# ReddEye

Personal, noncommercial r/sportsbook Pick of the Day research dashboard.

Live site: https://camdenguay12.github.io/reddeye/

Pages: Daily POTD and Pick History. The dashboard reads data/picks.json. Each record has date, sport, event, selection, odds_american, upvotes, summary, result, reddit_url, and result_source_url. Results are win, loss, push, pending, or unverified. Every result must have an independent sports-results source. Never invent vote rankings, odds, or outcomes.

The dataset is intentionally empty until verified selections are available. The 7 AM ET ChatGPT task searches publicly indexed Reddit discussions and reports results, but may be unable to verify the top comment or update the repository. GitHub Pages only changes when a successful commit updates the JSON file.

Reddit API access has not been approved. No unauthorized scraper is included. This is not betting advice.
