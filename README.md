# timebox
This is a small demo of a timer that can be used for timeboxed meetings with multiple segments. It's nice to throw on a beamer and have it in the background for everyone to be reminded of the time.

Check out the demo:

[![YouTube Demo](https://img.youtube.com/vi/HgjwBcZYOXs/0.jpg)](https://youtu.be/HgjwBcZYOXs)


It's a simple HTML file, so you don't need any fancy server or external requirements! Pure JS, CSS, HTML!

To set up your timeboxes, simply edit the HTML file at the beginning of the script section:
```js
    var timeBoxes = [
        {name: 'Who\'s Wo', time: 10 * 60},
        {name: 'Your Persona', time: 5 * 60},
        {name: 'Reverse Brainstorming', time: 5 * 60},
        {name: 'Wait, What?', time: 3 * 60},
    ];
```
(Time is in seconds, for easier reading multiply the minutes by 60)
