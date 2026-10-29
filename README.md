# BoxRun store page: staging copy

A test copy of the save page draft (boxrun-api/client/store.html in the private BoxRun repo), on its own origin so it can never see players' saves. Not for players.

`reset.html` (test only) empties this origin's localStorage and sessionStorage on load, so the next run of the staging page starts as a new player's. Its title reads `BRRESET cleared N` (or `BRRESET failed <reason>`). It belongs on this staging origin only, never on save.boxrun.gg or in boxrun-store.
