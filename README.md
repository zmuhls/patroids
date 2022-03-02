***PATROIDS***

A re-imagined, NFL-themed Asteroids clone in Python, using pygame  
    
    authored by Amin Bandali
    adapted by Zach Muhlbauer

## How To Play

To play the game, open a terminal (or command line window), cd into the folder, and type:  
` python patroids.py `
	or
` python3 patroids.py `

Click anywhere on the screen to start the game.  

You have 3 lives to begin with (displayed at top left).  
Each time a Patriot hits your Buffalo Bill, you lose a life (and likely miss the playoffs that year, prompting buy-out rumors).  

Needless to say, you have to avoid the Patriots! 

You begin with a 0 score (displayed at top right corner).  

Use up arrow to accelerate, and the left + right arrows to rotate the Bill.

You can generate footballs using the space bar.  
- When a football hits a Belichick, he breaks it into two Brady's. Your score increases by 25.
- When a football hits a Brady it breaks it into two Gronkowski's. Your score increases by 50.  
- When a football hits a Gronkowski, he is vanquished and your score increases by 100.  

The game gets more difficult for each 20 seconds you survive:  
- One more Patriot is added to the screen (they were 4 initially)  
- The radius inside of which the Patriot are created becomes smaller, becoming more difficult to dodge. This prescription is no surprise, as the Patriots are relentless and refuse to acquiesce or compromise. They only know destruction, as in Shiva, except less merciful. Run, if you can!

(All football-missiles are in fact deflated.)
