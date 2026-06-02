# ✈️ Haneda Ops — Director's Season (July 2026)

A gamified daily to-do & habit tracker. You play the **Operations Director of Tokyo
Haneda International Airport**: plan each day of July like a flight schedule, complete
your tasks, and fly Haneda up the world rankings. Log all 31 days to finish the season
and see if you crown Haneda the **#1 airport in the world**.

## How it works
- **Scoring per day** — complete ≥50% of your tasks = **4 pts**, ≥75% = **8 pts**, 100% = **16 pts**.
- **Routes** — every day you close out opens one real Haneda international route as a boarding pass (Seoul → Shanghai → … → London, JFK, Frankfurt).
- **Rankings** — your points climb Haneda past 30 real rival hubs (Changi, Doha, Incheon, Dubai…). Reach the top to win.
- **Times** — add a range like `04.30 - 08.00` on **your own local clock**, or leave it blank for "anytime." Nothing defaults to a set time.
- **Saving** — progress saves automatically in your browser via `localStorage` (and `window.storage` when present). Close the tab and come back; your season is waiting.

## Files
```
index.html                     ← the whole game (open this)
assets/haneda-logo.png         ← wordmark in the top bar
assets/haneda-map.jpg          ← terminal map (Crew Guide tab)
assets/haneda-what-to-do.jpg   ← amenities guide (Crew Guide tab)
```

## Run it locally
Just open `index.html` in any modern browser. Keep the `assets/` folder next to it.
(Tip: leave the file in a fixed folder — browsers tie saved progress to the file's location.)

## Publish free on GitHub Pages
1. Create a new GitHub repository and upload these files (keep the folder structure).
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Choose branch **`main`** and folder **`/ (root)`**, then **Save**.
4. After a minute your game is live at `https://<your-username>.github.io/<repo-name>/`.

Because GitHub Pages serves `index.html` automatically, the link above just works.

## Credits
Built as a personal productivity game. Aviation route/ranking flavor is based on real
2025–26 busiest-international-route data. The embedded video and Haneda imagery are used
for guidance within the app.
