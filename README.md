# deepracer
Udacity-AWS DeepRacer Challenge

I got an email from Udacity to compete in the AWS Deepracer challenge. If you have a winning entry, you are able to win a free machine learning course. Of course one of the problems may be that I spend a lot of money for compute time trying to win. But, I suppose that's only an issue if I am not doing well in the standings and just keep trying to train new models.

WHAT IS THE DEEPRACER CHALLENGE?

FIRST RUNS -default profiles
I ran with the no follow center line profile first. It had a mediocre finishing time, 30 seconds to complete a lap which put it right at about 50% 375 out of 650 contestants.

The next profile was one that just stays on the track. This had a slightly higher performance.

Next, I tried the 'avoid zigzag' profile and it ended up not even completing a run.


TRIAL AND ERROR
This is probably one of the worst strategies, but I used trial and error with the parameters of the 'follow-center-line' profile to try to find the limits of the speed that the car could take and succesfully completing the track. I set the maximum speed to 6m/s versus the default of 1m/s. I found that I could get in around 7m/s before the car was unable to complete a lap.

with these parameters in mind, I proceeded to try to find a strategy that would get me a better time. 
