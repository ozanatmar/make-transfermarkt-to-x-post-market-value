# make-transfermarkt-to-x-post-market-value
Scrapes any Transfermarkt market value page and generates a ready-to-post X thread with top 10 players.

# Transfermarkt to X Post: Auto-generate market value rankings

Give it any Transfermarkt market value URL (league, club, position, country) 
and it scrapes the top 10 players and formats them as a ready-to-post X update 
with values, clubs, and an optional flag/icon prefix.

## What you need
- Make.com account (free tier works)
- A Transfermarkt URL (any market value page)

## Setup
1. Download workflow.json
2. In Make.com: Create scenario → ••• → Import Blueprint → select the file
3. Run the scenario with two inputs:
   - URL: any Transfermarkt market value page  
     (example: https://www.transfermarkt.com/premier-league/marktwerte/wettbewerb/GB1)
   - Icon (optional): an emoji or flag to prefix the post  
     (example: 🏴󠁧󠁢󠁥󠁮󠁧󠁿)
4. Output: a fully formatted X post in the scenario output

## Example output

🏴󠁧󠁢󠁥󠁮󠁧󠁿 Premier League – Most Valuable Players

1. Erling Haaland (Manchester City) – €200m
2. Declan Rice (Arsenal FC) – €120m
3. Bukayo Saka (Arsenal FC) – €120m
...

Who's the most valuable player in your league? 👇

## Use cases
- Football content accounts on X
- Newsletter writers covering transfers
- Fantasy football communities
- Club fan pages auto-posting weekly market value updates

## Extend it
Connect the output to:
- X module → auto-post on schedule
- Buffer/Typefully → schedule across multiple accounts
- Telegram/Discord bot → post to channels
- Notion database → log historical valuations

## Screenshot
![scenario](Screenshot%202026-05-19%20143304.png)

## Built by Ozan Atmar
I build Make automations and web apps for founders.  
Site: https://ozan.at/mar  
Email: ozanatmar@gmail.com
