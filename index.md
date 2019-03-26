I learn new things in each project. Here I will summarize some of what I've learned.

For example, in the unit-4-game [Crystal Math](https://krisjecen.github.io/unit-4-game/), I used jQuery and learned how to use a [toggle()](http://api.jquery.com/toggle/) function to show/hide the game instructions:
- Set two classes, one for the elements you want to show/hide, and one for the toggle initiators, which in my case were text links that said "Hide instructions" & "Show instructions".
- Use inline style=display: none to initially hide the desired element(s).
- Use an on.click event targeting the toggle initiator, and within the function expression, target the elements you want to toggle, and call (?) the toggle effect on them.
- In the () of toggle() you can specify "slow" for a slow animation (600 ms duration; can also specify "fast" for 200 ms; default is 400 ms).
