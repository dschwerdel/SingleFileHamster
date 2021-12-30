# SingleFileHamster
Let the hamster clock your time

My goal is to pack everything in one file. So, right now there are three parts in this file. The html / css for styling and general visual parts, including animating the second part: the inline image. Yes, very important.
Third part: a little javascript logic for clocking your time.

Everything is in one file. Maximum portablity. Also no framework at all. Lets invent the wheel!

The clocked time is saved in the localStorage of the browser. Which means all the data stays with you or more precise with your browser session, as long as you keep your "cookies".

Have a preview:
https://www.schwerdel.net/hamster/

I still have a long way to go with this project. But most key features are implemented. 
+ Start and stop the time, and log those events
+ Take and log a break, restart work after the pause 
+ Name your job cathegory or choose from drop down menu

Long term goals:
- prented to care about chrome scrollbars
- have a export function in a meaning full format
- maybe show some graphs, but this goes to an extra file

Short term goals:
- clean up and comment the code (don't worry we will refactor it later)
- save the user created job categories in the localstorage, display it if they're there. (Actually this works somewhat. But the dropdown menu is not refreshing properly, so I commented it out.)
- work on a nice design. 
- fix the display of the history, show a total of time per day
- just make it better

Proudly but stupidly made with gedit
