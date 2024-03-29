# Tabletop Basketball Game
A possession-by-possession quick play tabletop basketball game

This is a game demo only. There are 4 teams for you to try out: 1986-87 (Boston, Los Angeles, Atlanta, and Dallas). Download all the game components below to try the game. You'll need 2 d10 dice to use for this game. Roll real dice or use the [virtual dice roller app I created](https://cdpn.io/pen/debug/WNzRGez/706d5aa477cf55f1c8e5e103880a2f8d). You'll also need two small markers for time keeping (if you're using the offline clock).

## Team and Player Cards w/ Fouls

NEW! Download these three teams from 1985-86 to try out the new foul system for teams:

[3 Teams w/ Fouls](https://github.com/brianhaferkamp/basketball-game/raw/main/uptempo_85-86_with_fouls.pdf)

### FOUL

I'm attempting to use a foul option in the game. This is new as of August 8, 2022. If you roll a FOUL then roll both d10 dice again and compare it to the ranges on the chart in the bottom left of the team card. This chart determines whether it was a defensive foul (non-shooting), a shooting foul, or an offensive foul. Shooting and defensive fouls count toward the total team fouls but offensive fouls do not. Each quarter the team fouls are reset so that after a team commits its fifth team foul in each quarter the opposing team gets 2 free throw attempts. There is no 1 and 1 bonus in the NBA. 

Once there are two minutes remaining in a quarter, the bonus rule applies after a team reaches their second foul. This happens regardless how many team fouls were committed during the quarter of play. In any overtime period, the bonus rule gets applied once a team goes over three fouls.

To figure out who committed the foul you can utilize the defense usage (the same as you use to find out who is the defender on the play). If a starter fouls out of a game then you will only use the bench player for that position for the rest of the game. If the bench player also fouls out you must substitute one of the other bench players into the position's spot for the remainder of the game.

## Game Components

Download these PDF files to have the components for the game:

[Team Cards w/ Starters & Bench Players](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Team_Cards_wBench_Demo_3.pdf)\
[Game Timer (Both Clock and Possessions Styles)](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Timer.pdf)\
[Scoresheet w/ Space for Individual Stats](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Scoresheet.pdf)\
[Scoring Runs Cards](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Scoring-Runs_Cards.pdf)\
[Game Guide](https://github.com/brianhaferkamp/basketball-game/raw/main/Uptempo%20Basketball%20Game%20Guide.pdf)

### Demo Video

[Watch this introductory video to learn how to play.](https://youtu.be/PowiwApeRBI)

## Game Play

This game requires two d10 dice to play. I've built a virtual dice roller and time keeper for the game that you're free to use on any device or computer: [https://cdpn.io/pen/debug/WNzRGez/706d5aa477cf55f1c8e5e103880a2f8d](https://cdpn.io/pen/debug/WNzRGez/706d5aa477cf55f1c8e5e103880a2f8d)

You can have a traditional tip off by rolling to see who gets the ball. I like to use

1-50 = Visitors\
51-100 = Home

You can also simply decide the possession and then alternate possession throughout the game. 

To play a possession, roll the d10 dice and combine the number to get a number between 1 and 100. Consult the play chart on the card of the team with possession. Here are the plays:

### RUN
If there is a scoring run, roll both d10 dice and consult the scoring run chart (bottom right of the card under 3PT%). Mark off the points on the scoresheet and take 2:00 off the timer.

To get the individual stats for a scoring run, find the correct scoring run card (download above) and roll the 2 d10 dice to get a roll result. Compare that roll result against the roll column on the scoring run card. Find the row the roll result falls within range of and consult the row for the scoring of each of the different players on the court. You  can write these scoring plays in for each player to show what happened during the scoring run.

### TO
Turnover. No scoring. Move the clock one space.

### FT Att
Free throw attempt x 2. Roll the d10 dice and compare it with the FT% of the team (chart under the W-L record). If the roll result is less than the FT% then the free throw is good. If it's higher the free throw has been missed.

### FOUL

I'm attempting to use a foul option in the game. This is new as of August 8, 2022. If you roll a FOUL then roll both d10 dice again and compare it to the ranges on the chart in the bottom left of the team card. This chart determines whether it was a defensive foul (non-shooting), a shooting foul, or an offensive foul. Shooting and defensive fouls count toward the total team fouls but offensive fouls do not. Each quarter the team fouls are reset so that after a team commits its fifth team foul in each quarter the opposing team gets 2 free throw attempts. There is no 1 and 1 bonus in the NBA. 

Once there are two minutes remaining in a quarter, the bonus rule applies after a team reaches their second foul. This happens regardless how many team fouls were committed during the quarter of play. In any overtime period, the bonus rule gets applied once a team goes over three fouls.

To figure out who committed the foul you can utilize the defense usage (the same as you use to find out who is the defender on the play). If a starter fouls out of a game then you will only use the bench player for that position for the rest of the game. If the bench player also fouls out you must substitute one of the other bench players into the position's spot for the remainder of the game.

### 2PT Att
Two point attempt. This is a two point shot. Roll the d10 dice and combine. Compare the roll result with the FG% of the team. If the roll result is less than or equal to the FG% then the shot is good. If it's higher than the FG% the shot has been missed.

### And 1
This is a made basket with a foul. Count the two points automatically and make a FT Attempt.

### 2PT
Automatic two points.

### 3PT Att
Three point attempt. Roll the d10 dice and combine. Compare the roll result with the 3PT% of the team. If the roll result is less than or equal to the 3PT% then the shot is good. If it's higher than the 3PT% the shot has been missed.

### 3PT
Automatic three points.

## Defense

To use the defense (DEF) ratings you will add or subtract the defense rating to the shooting percentage for the team or player shooting the ball then compare the calculated percentage against the roll result of the shooting percentage roll. For example, if the original shooting percentage is 52.3 but the defense value is 3, the new shooting percentage is 55.3. If the defense value was -3 then the new shooting percentage is 49.3. You can use the team defense value against a team or individual player. To have individual player defense you would use the player guarding the shooter (i.e., playing the same position).

## Using Player Stats

If you want the granularity of keeping player points you can use the player cards. First, roll for the play using the team card then roll 2 d10s and combine to get a roll result. Find the player for that play type that has a range that includes the roll result. Next to each player is that player's FT%, 2PT%, and 3PT% (in that order). Roll the 2 d10s again and combine to get the roll result. If the roll result is less than or equal to the player's shooting percentage for that type of shot then the basket is good. If it is greater than the player's shooting percentage the shot has been missed.

The game is pretty simple and straightforward. Play until the timer runs out, alternating possession between the teams. I'd love to hear your thoughts on the game play, fun factor, cards, timer, scoresheet--anything. Send any comments and suggestions to onbasebaseball@gmail.com.
