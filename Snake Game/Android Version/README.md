# Android Snake Game [![Build Status][travis-image]][travis-url]

This app is classic snake game where the user can play the game and store high score.

## Functionality

- In this game snake will die i.e. game will be over if snake hits the wall or its head get stuck with its body.
- As score increases speed of snake will increase.

## Code explanation

- I have used canvas to draw the snake and field using drawrect and other method calls.
- I have created one thread to run the snake code to have user freedom of doing other things in main thread.
- For storing high score of user I have used **SharedPreferences** to store it in `GAME_DATA` file.
- Check the code at folder [`SnakeGame`](https://github.com/kalpeshdusane/Fun-Coding-for-Games/tree/master/Snake%20Game/Android%20Version/SnakeGame).

## Running Game

Install APK file: [`SnakeGame.apk`](https://github.com/kalpeshdusane/Fun-Coding-for-Games/blob/master/Snake%20Game/Android%20Version/SnakeGame.apk)

## Screenshot of the game app

![image](readmeImage/game1.png)

![image](readmeImage/game2.png)

![image](readmeImage/game3.png)

![image](readmeImage/game4.png)

![image](readmeImage/game5.png)

## Acknowledgement

Most of the coding is followed from the article on this [website: gamecodeschool](http://gamecodeschool.com/android/coding-a-snake-game-for-android/) by John Horton

<!-- Markdown link & img dfn's -->
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
