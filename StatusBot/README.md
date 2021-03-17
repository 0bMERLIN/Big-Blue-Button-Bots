## Status-🅱️ot

This bot changes the users status from a specified value to nothing for a specified amount of times

### usage
1. Paste the code into your browsers console in the video conference tab.
2. Replace &lt;delay&gt; with the delay you want between button presses
3. Replace &lt;count&gt; with the number of times you want the bot to set and reset the status
4. Replace &lt;symbol&gt; with one of the listed available status signs.<br>This will be the status sign, that will be activated and reset while the bot runs.
    - All the symbols defined are for the german version of BBB. If you aren't german, you will need to change them.
6. call
```js
annoyNoPopup(<symbol>, <delay>, <count>)
```

Example:
```js
annoyNoPopup(away, 10, 100)
```
