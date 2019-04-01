# Basic Breakout HTML Game

This is a basic implementation of the Atari Breakout game, but it's missing a few things intentionally and they're left as further exploration for the reader.

## Further Exploration

- Lives
  - The player should have 3 chances to remove all the bricks. Display how many lives the player currently has using [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText). Remove a life when the ball goes below the screen
- Score
  - When a ball collides with a brick, the score should increase [based on the color](https://en.wikipedia.org/wiki/Breakout_(video_game)#Gameplay)
  - Display a high score using [localSorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- Mobile and touchscreen support
  - Allow the game to be scalled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Better paddle movement
  - Currently the paddle movement is sticky. If you press the opposite direction while releasing the other direction, the padddle doesn't move right away. And if you release a direction while holding the other, the paddle stops. Improve it so it doesn't do this.
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.