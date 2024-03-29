# Ensake Frontend Test

## There are two tests involved

1. Showdown - is meant to test animation skills
1. Wheel - is meant to test general understanding of frontend - backend communications.

- Both tests can be done in the same repository ( and the same page, as the Showdown project is meant to be used as a header )
- Both tests need to run on IPhone 7 and newer, Desktop Chrome ( latest ), Mac Safari ( latest ), Windows  IE ( 10 and newer )
- Both have to be responsive. It’s up to you to decide on a layout.
- The tests need to be added to a public repository, so that we can check the code functionality and quality.

## 1. Showdown

- Inside the showdown folder, you will find a video file showing the animation required and all the relevant assets to make it work.
- The animation has to be using CANVAS ( you can use whatever canvas library you wish - pixi.js / three.js / etc)
- The animation has to start on page load and once it’s completed everything must remain lit, apart from the lightning bolt which needs to keep flickering at a 10 sec interval.

## 2. Wheel


- Inside the wheels folder, you will find the graphical assets for a wheel of fortune game.
- The application needs to do a request on an endpoint upon clicking the "spin" button ( you can have the endpoint as a static JSON file in the same repo ). The endpoint will return a JSON object in the following format:   { POSITION: 2 } . Based on the POSITION value the wheel will spin, and then stop on position 2. ( it’s up to you to assign numbers to all sides of the wheel ).
- Make sure that the wheel spinning "SEEMS" random. ( it’s up to you to decide timings / etc )


## Notes

- Any improvements you make to the projects, other then the ones included in this document, will be greatly appreciated. We want to also see how you would improve projects!
- Bonus points if your project has a build process to compile SASS / LESS / etc, minify JS, merge html parts into JS, etc.
- Bonus points if your project includes a dev server, so we can just clone -> npm install -> npm start 