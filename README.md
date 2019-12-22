# Drop Game - Built for Twitch

## A Twitch overlay drop game. Type `!drop <image | emote>` in the chat to play

> Original Drop game by [instafluff](https://twitch.tv/instafluff). See the original code [here](https://github.com)

## Todo

- [ ] Setup client
- [ ] Get target on the screen with swaying animation
- [ ] Get drop image on the screen with swaying animation
- [ ] Game logic to drop an image
  - [ ] Starts out above the screen at random X coordinate
    - [ ] Has random X and Y velocity
  - [ ] Collision detection for edges of screen
    - [ ] Reverse X velocity if hits edge
    - [ ] Stop dropping when it hits the bottom of the screen
  - [ ] Score drop if it lands within the target
  - [ ] Twitch chat on client with emote support
  - [ ] Allow !drop with no emote, get the users avatar image from twitch API
