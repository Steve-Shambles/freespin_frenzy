# freespin_frenzy
A graphical slot machine with outrageously generous freespins feature.

Freespin Frenzy V0.90
By Steve Shambles May 2020-2023.

Written using Python V37.6 and Tkinter on Windows 7 64bit.
A (very slow) work in progress.

To do:
Menu icons
Make hold buttons flash when hold activated.

A REALISTIC SPIN FOR THE REELS.
if not then change how they spin in some way as makes my eyes go wobbly
after a while and also may be the source of the memory problem.
use 5 cards instead of 3.

Bug:
A massive memory bug, the game will crash after gobbling up loads of memory,
on my 16gig machine I get about 100-120 spins before a crash,
thats why I save the bank and high score to disc so player can continue where
it crashed. I need pro help to fix this.

![Alt Text](https://github.com/Steve-Shambles/freespin_frenzy/blob/main/cards/screenshot_00.png)

Introduction:

Everyone loves generous freespins in slot machines don't they?
I wanted to make my own dream freespin feature.
I held back on some things as to keep it a bit realistic though, after all 
the machine is supposed to make a profit over the long run, usually between 2 and 8%-ish profit from turnover.
I have no idea how to work out the correct payouts vs chances\odds of each win, so this is simply a random game for fun,
for now at least, there is a long long way to go to make this a proper slot machine, so just enjoy as a free game.

How to play Freespin Frenzy:
----------------------------
First select your stake using the orange "stake" button,
clicking it will roll between $1 and $5.

You start off with $200 to play with.

If the "HOLD" buttons light up you can click on each hold button to hold
1, 2 or all three reels, random hold after win sometimes comes up so keep an eye out for that. You have a 1 in 5 chance of a hold.

Now click on the green "SPIN" button to start the game. If you prefer you can use the spacebar to spin the reels, I put this in after getting carpal tunnel syndrome type pain after many hours of testing.

Below the "STAKE", "HOLD" and "SPIN" buttons you will see your current
"BANK" which is self explanatory.

Below the bank line we have the "BONUS POT" this is assigned a new random value at the start of each spin. You can win the bonus pot by getting three 
bonus pot cards up together on the reels.

At the very bottom of the window we have your "HIGH SCORE". This is the highest amount you have ever reached in your BANK.
This score is saved to disc and loaded in the next time you play.

Above the three reels\cards is the games message area this will tell you the outcome of every spin and how much you have won if anything, this area is 
also used during freespins to keep you informed of spins left, wins, etc.

![Alt Text](https://github.com/Steve-Shambles/freespin_frenzy/blob/main/cards/screenshot_01.png)

At the top left of the game window you will see a drop-down "MENU".
Options in the menu include:

soundfx on   : swithch sound effects on
soundfx off  : switch them off
Help         : This text file
About        : version info and copyright

Source code on GitHub: Will take you to my main repository,
                       lots of my rubbish code there to laugh at.

Make a donation: If you feel sorry for this sad old man doing all this work
                 for fun and not profit feel free to send me a fiver or tenner
                 via PayPal, I don't think you even need a PayPal account.


Pay table:
----------

JJJ  5x stake
QQQ 10x stake
KKK 15x stake
AAA 20x stake

Note: Any three suits the same pays 1x stake.
i.e. three diamonds.

3 x Bonus pot cards wins bonus pot(random amount).

3 x Freespins cards wins 15 freespins, all wins are tripled,
every losing spin gives you consolation prize of 1x stake.
every freespin card that appears increases you freespins by one.
Except when all 3 freespins cards appear during freespins ,
this retriggers another 15 freespins.
Note: the jackpot (3 wilds) will end the freespins immediately.

3 x Wilds is the jackpot and pays 200 x stake.

Note: A single wild card can replace any symbol
except freespins, suit or bonus pot.

![Alt Text](https://github.com/Steve-Shambles/freespin_frenzy/blob/main/cards/screenshot-2.jpg)

Good luck.
Steve Shambles May 2023


