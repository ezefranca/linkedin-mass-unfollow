# linkedin-mass-unfollow
## How to mass unfollowing people on LinkedIn

LinkedIn nowdays is place with a lot of "Influencers" and a lot of people sharing things not interesting.

If you want to do a clean on your timeline do this steps:


0 - Make sure to note key people to follow. Save using the best way for you this list.

1 - This page on your profile: https://www.linkedin.com/feed/following/

2 - Open the Developer Tools in Chrome. Scroll down, several times, make sure to scroll to get all connections. Whilst LinkedIn lazy loads a decent sized list.

3 - In the Console View, type:

```javascript
var buttons = document.querySelectorAll("button.is-following"); for (i in buttons) { buttons[i].click() }
```
and press enter;

4 - Reload the page, if you need, repeat the process, until the ‘Following’ count drops down and the page says ‘Follow Fresh Perspectives’

5 - Re-follow key people saved on step 0.


Enjoy your feed.
