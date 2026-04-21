KICKOFF — TOURNAMENT MANAGER

A simple, no-backend football tournament manager built using HTML, CSS, and Vanilla JavaScript.
Create leagues, track scores, apply bonus rules, and run a knockout stage — all in one page.

---

FEATURES

PLAYER SETUP

* Add 4 to 10 players
* Optional:

  * Double round-robin
  * Bonus points system
  * Rival assignments (El Clasico rule)

LEAGUE SYSTEM

* Automatically generates round-robin fixtures
* Avoids back-to-back matches where possible
* Enter match scores easily
* Live updates after each result

LEAGUE TABLE
Tracks:

* Played (P)
* Wins (W)
* Losses (L)
* Goals For (GF)
* Goals Against (GA)
* Goal Difference (GD)
* Points (Pts)

Sorting:

1. Points
2. Goal Difference
3. Goals Scored

BONUS RULES (OPTIONAL)

* +1 point for 3+ goal win
* +1 point for beating a rival

KNOCKOUT STAGE

* Top 3 players qualify:

  * 2nd vs 3rd → Semi Final
  * Winner faces 1st → Grand Final
* Supports:

  * Draw resolution (penalties/manual pick)
  * Automatic progression
* Displays final tournament winner

DATA PERSISTENCE

* Uses localStorage
* Tournament progress is saved automatically
* Reload page → continue where you left off

UI HIGHLIGHTS

* Clean modern design
* Live progress bar
* Match cards with score input
* Animated champion banner
* Mobile responsive

---

TECH STACK

* HTML
* CSS
* JavaScript (Vanilla)
* No backend required

---

FILE

* League.html → Main application file

---

HOW TO RUN

1. Download the file
2. Open League.html in your browser
3. Enter player names
4. Click "Generate Tournament"
5. Start entering match scores

---

HOW IT WORKS

1. Generates all match combinations
2. Stores results in memory + localStorage
3. Updates table dynamically
4. Unlocks knockout stage after league completion
5. Determines final winner

---

NOTES

* League becomes locked once knockout starts
* Reset clears all progress
* Tie-breakers are handled automatically

---

FUTURE IMPROVEMENTS

* Online multiplayer / sharing link
* Firebase backend (for syncing across devices)
* Export standings as image

---

Built for competitive friend tournaments
