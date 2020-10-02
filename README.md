# SnakeWorld

# Basic Snake HTML Game

Snake is a fun game to make as it doesn't require a lot of code (less than 100 lines with all comments removed). This is a basic implementation of the snake game, but it's missing a few things intentionally and they're left as further exploration for the reader.
<img width="395" alt="image" src="https://user-images.githubusercontent.com/2433219/94888166-76551f80-0435-11eb-97f9-432cc9297a71.png">

## Further Exploration

- Score
  - When the snake eats an apple, the score should increase by one. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
- Mobile and touchscreen support
  - Allow the game to be scalled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Better apple spawning
  - Currently the apple spawns in any random grid in the game, even if the snake is already on that spot. Improve it so it only spanws in empty grid locations
  
