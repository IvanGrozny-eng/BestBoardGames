# BestBoardGames
Dark-mode board game catalog template (Vanilla JS)
This is a clean, dark-mode focused landing page / catalog template for board games. It’s built on vanilla tech (no frameworks, no bloat), so it loads fast and is super easy to customize.

What’s in here?

Pure Vanilla JS and CSS: No need to install node_modules or anything complicated. Just open it and it works.
Neon-ish UI: Dark theme with purple and orange accents. Looks solid on mobile too.
Built-in Search and Filters: Filters games by type (strategy, coop, etc.) and has a live search bar.
LocalStorage Favorites: Users can click the heart icon, and it saves their favorites in their browser.
Functional Modal: Click Review on any game to see a popup with details, fake price history graph, and component list.

How to edit this thing

It's all in the index.html file.
Scroll down to the script tag at the bottom. You'll find a const called gamesData. Just edit that array with your own game titles, prices, and images.

Example structure inside index.html
{
    id: 1,
    title: "Game Name",
    rating: 4.8,
    type: "strategy",
    // ...etc
}
