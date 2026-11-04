BEAT WAYFARER - VERCEL WEBSITE PACKAGE

This is the static PC/browser website version of Beat Wayfarer.

DEPLOY WITH VERCEL (recommended: Vercel CLI)
1. Extract this ZIP folder on your computer.
2. Install Node.js if you do not already have it: https://nodejs.org/
3. Open a terminal/Command Prompt in the extracted folder.
4. Run: npx vercel
5. Follow the prompts to create/link your Vercel project.
6. To publish the live production version, run: npx vercel --prod

You can also push the extracted folder to a GitHub repository and import that
repository from https://vercel.com/new. No build command is needed; this is a
plain static HTML/CSS/JavaScript game. The website entry point is index.html.

FILES
- index.html: game website
- game.js: game logic
- styles.css: visuals and layout
- flightly-logo.png: game logo
- vercel.json: static hosting configuration

NOTE
This package hosts the browser game. It does not build a standalone Windows EXE.
The game can be played in a desktop browser after deployment.
