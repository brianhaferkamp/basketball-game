# Tabletop Basketball Game
A possession-by-possession quick play tabletop basketball game

This is a game demo only. There are four team cards created for you to try out: Phoenix, Chicago, New York, and Sacramento. Download the two PDF files--the team cards and the scorecard with timer. You'll need 2 d10 dice to use for this game. Roll real dice or use a virtual roller. You'll also need two small markers for time keeping.

## Game Components

Download these PDF files to have the components for the game:

[Team Cards](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Team_Cards_Demo.pdf)\
[Game Timer (Both Clock and Possessions Styles)](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Timer.pdf)\
[Scoresheet w/ Player Stats](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Scoresheet.pdf)\
[Scoring Runs Cards](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Scoring-Runs_Cards.pdf)\
[Game Guide](https://github.com/brianhaferkamp/basketball-game/raw/main/Basketball_Game_Guide.pdf)

[Watch this introductory video to learn how to play.](https://youtu.be/0hvPqzHxi-o)

## Game Play

This game requires two d10 dice to play. I've built a virtual dice roller and time keeper for the game that you're free to use on any device or computer: [https://cdpn.io/pen/debug/WNzRGez/706d5aa477cf55f1c8e5e103880a2f8d](https://cdpn.io/pen/debug/WNzRGez/706d5aa477cf55f1c8e5e103880a2f8d)

You can have a traditional tip off by rolling to see who gets the ball. I like to use

1-50 = Visitors\
51-100 = Home

You can also simply decide the possession and then alternate possession throughout the game. 

To play a possession, roll the d10 dice and combine the number to get a number between 1 and 100. Consult the play chart on the card of the team with possession. Here are the plays:

### RUN
If there is a scoring run, roll both d10 dice and consult the scoring run chart (bottom right of the card under 3PT%). Mark off the points on the scoresheet and take 4:00 off the timer.

To get the individual stats for a scoring run, find the correct scoring run card (download above) and roll the 2 d10 dice to get a roll result. Compare that roll result against the roll column on the scoring run card. Find the row the roll result falls within range of and consult the row for the scoring of each of the different players on the court. You  can write these scoring plays in for each player to show what happened during the scoring run.

### TO
Turnover. No scoring. Move the clock one space.

### FT Att
Free throw attempt x 2. Roll the d10 dice and compare it with the FT% of the team (chart under the W-L record). If the roll result is less than the FT% then the free throw is good. If it's higher the free throw has been missed.

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

The game is pretty simple and straightforward at this point. Play until the timer runs out, alternating possession between the teams. I'd love to hear your thoughts on the game play, fun factor, cards, timer, scoresheet--anything. Send any comments and suggestions to onbasebaseball@gmail.com.

## Defense

To use the defense (DEF) ratings you will add or subtract the defense rating to the shooting percentage for the team or player then compare the calculated percentage against the roll result of the shooting percentage roll. For example, if the original shooting percentage is 52.3 but the defense value is 3, the new shooting percentage is 55.3. If the defense value was -3 then the new shooting percentage is 49.3. You can use the team defense value against a team or individual player. To have individual player defense you would use the player guarding the shooter (i.e., playing the same position).

## Using Player Stats

If you want the granularity of keeping player stats you can use the player cards. First, roll for the play using the team card then roll 2 d10s and combine to get a roll result. Find the player for that play type that has a range that includes the roll result. Under each player name is that player's FT%, 2PT%, and 3PT% (in that order). Roll the 2 d10s again and combine to get the roll result. If the roll result is less than or equal to the player's shooting percentage for that type of shot then the basket is good. If it is greater than the player's shooting percentage the shot has been missed.
