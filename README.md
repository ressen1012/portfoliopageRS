## Website Performance Optimization portfolio project - Resul Senturk

Some useful tips to help you get started:

1. Downloaded the repository to local machine
2. Added local repisotory to GitHub
3. Created new branch called gh-pages
4. Hosted to GitHub to analyze page speed using google's PageInsights

## Part 1 - Analyzing index.html Using PageInsights:
1. 73 Mobile, 88 Desktop scores origional file
2. Deleted font.googleapis.com/css?family=Open+San
3. Inlined CSS and JS
4. Added async to analytics.js
5. Added meta tag and cache control
6. Cached images pizzeria.jpg & profilepic.jpg
7. Optimized images (compressed/resized)
8. Minified html
9. Achieved  93 Mobile, 94 Desktop score

## Part 2 - Effective Optimizations For 60 FPS
1. Deleted determineDx and moved it into changePizzaSizes function
2. Changed the slider value to a percent width
3. 