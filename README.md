# Training with the Eleven VR Table Tennis Ball Machine: Dynamic Dynamic Drillinator Settings

# Introduction and logic

- This is a guide to using settings for the Eleven table tennis ball machine. Information on installing the settings is at the bottom. The following explains why this guide and settings exist. 
- In real life, table tennis players in metropolitan areas can learn drills and get coaching from visiting a table tennis club and working with coaches. 
- But with the advent of VR table tennis such as with the game Eleven, more people will be learning and improving at the sport in their homes without some of these support structures, so more guidance for these players should be helpful. 
- VR allows types of training for players on their own not easily accessible for most players, such as use of ball machine or "multi-ball" style training, with players able to employ types of training that normally coaches would advise on. 
- In addition, VR allows types of training that would not be possible in real life (at least not without employing 1-1 coach available in your bedroom at any time of the day or night).
- A key feature is the ability to move a table tennis robot to any position on the table on a point by point basis. Since this is a novel feature there are (currently, but see below) not any guides available on how to utilise the power these kinds of feature provides. This document is a starting point to documenting how these kinds of features might be employed to enhance sport skill development. 
- This is a guide for beginners and intermediate players. More advanced players might not need such a guide, and will have more existing knowledge of adapting IRL drill and coaching to their VR training. Below I have provided some links to existing guides on table tennis drills to provide ideas on how players can adapt existing drills. 
- Disclaimer: I am not an expert table tennis player or coach, but someone who is currently using the ball machine to improve at the sport. If you want a coach the Eleven Discord does have some coaches offering VR coaching services. The internet is also full or resources to help. I give some suggested Youtube channels videos below. One tip is to video yourself when learning new techniques- which is particularly useful as with VR you don't get to see your own shots or footwork. 
- For another batch of settings by a VR table tennis coach see ALEX
- This guide and settings is based on the Eleven ball machine in June 2020 (see https://eleven-vr.fandom.com/wiki/Ball_Machine). This may be updated in time as new features become available and with additional training ideas. 

# Advantages of the VR ball machine to In Real Life (IRL)

- There are unlimited balls! You can play forever and it will never run out of balls, never jam, and you never had to pick up balls from the floor again.
- It doesn't cost the same price as a second hand car. The Eleven robot has functionality similar to a top of the range robot, and they don't come cheap.
- You don't have to find and pay a professional coach to do multi-ball drills.
- IRL players create variation in parameters through their positioning, timing and stroke mechanics. Variations mimicing this variation can be easily programmed into a VR ball machine, with some variations (such as positioning of the X,Y and Z coordinates) not possible with a IRL robot. 
- It can move! This is a game changer. A regular robot is stuck in a single location, normally at the centre line baseline (where it is mounted to the table).  A coach doing a multi ball training will also normally have a fixed location, often the coaches forehand on one side of the table where their balls are stored in a basket. Real life players can implement more complex drills, but they can get tire and make mistakes. The Eleven robot can be programmed to move around to shoot from anywhere, creating variation across shots which mimic shot dynamics of IRL better compared to a static ball. Real life players don't always hit their shots from the middle of the table. But the ability to move the ball machine increases the possibilities and complexity of drills hence this guide. 
- See [here](http://www.sportsmedia101.com/other/olympics/2019/07/advantages-disadvantages-of-table-tennis-robots) for some advantages and disadvantages of robots in general.

# Notes on consistency and competition

It is important in drills to work on consistency. You need to get the ball on the table. One way to keep focus on consistency is to count how many in a row you can hit on the table, and make a note of your "high score" for particular drills. How consistent you want to aim for will depend on your particular training goals. Sometimes you might want 100% consistency (particularly as a beginner working on basics), such as 50 balls in a row on the table. A good minimum target to aim for in skill development is at least 80% accuracy. Higher might suggest the drill is to easy and not providing enough challenge to drive learning, and lower that the drill is too hard, leading to a loss of form. 
If you are training on your own, setting targets can help with motivation and keeping your focus. Here are some methods:

- One way to measure an accuracy target (such as 80%) is to count how many balls in you can land on the table in a row. Twenty works as a number you can aim for. Count each ball that lands on the table, and start again once you reach 20. If you miss a ball, start at 0. If you are consistently reaching 20, it might be time to increase the drill difficulty. 
- Set a timer IRL, such as 2 minutes, and count how many hits on the table you make. 
- Create some game dynamics by giving yourself three "lives". Every time you miss a shot you lose a life. Use a IRL stopwatch to see how long you can go before losing all your lives, or how many strokes you can make. 
- Choose a number, like 10, and count how many you hit out of that number each round of the drill, e.g. 1 of 1, 2 of 2, 2 of 3 (if you miss the third ball). 

# Principles behind Dynamic Drillinator Settings

1. The settings are named in capitals for the shot the ball machine is emulating, not the shot that you should hit.   
2. Naming conventions: STROKE + location of robot (Left/Middle/Right) > placement of shot (Left/Middle/Right) + Additional Information; e.g. L > R = would be for two right handed players a shot from the forehand side across the diagonal to the opposing forehand side. The > or < sign indicates the direction of the ball (from left to right or right to left) and = indicates a parallel shot e.g. R=R.Ts = Topspin, Bs = Backspin, Ss = Sidespin (shots like LOOP defined by spin won't have additional spin markers). Rand = Static robot but random horizontal angle, RandX = Random robot on horizontal/X axis (hitting parallel balls).
3. The settings are ordered (approximately speaking) in the order shots might be expected in a rally (though most rally's don't last this long!), as follows:
   -A player SERVEs (1st ball)
   -An opponent returns with a quick topspin FLICK, or BACKSPIN return that is Short or Long (2nd ball)
   -Players hit BACKSPIN pushes until one player opens up with an attack
   -A DRIVE or LOOP is initiated as an attacking shot (sometimes this happens as a 3rd ball attack)
   -Players now exchange attacking LOOPing balls 
   -Fast aggressive looping balls can be returned with a BLOCK or COUNTER to gain the initiative leaving the opponent reactive with less time to respond
   -A player hits a poor quality shot allowing a player to a SMASH
   -A player switches to all out defence and throws up a LOB to be smashed by the opponent.
4. Following the above logic, the settings have been designed to allow easy creation of drills using the Eleven settings, where shots quick be quickly selected and unselected in a drill to run in a sequential order. For example, setting up a three ball drill might involve 1) SERVE which you return with a long push 2) BACKSPIN which you attack with an "open up" topspin loop and the robot hits back with 3) DRIVE, which you loop and put away for a winner, and the drill repeats. 
5. Rather having pre-settings for a large number of possible drills, it is designed to be used in a dynamic way based on chaining shots as above, to create well known drills or your own novel drills. 
6. Not every possible shot has been programmed in - partly because it will lead to an unwieldy set of possible options but also it is herculean task. Users can customise shots as they need. Remixes are welcomed with more shots, and future versions of the settings might be more comprehensive. 
7. No one set of parameters of strokes will suit all players. Settings, such as randomness, speed, launch speed and spin, should be individually customised to suit your skill level and training goals. The current settings are about IRL advanced beginner/intermediate level.
8. While the settings are designed to allow easy creation of point-like drills, they are also designed to allow standard systematic/regular and irregular drills, particularly (currently) for DRIVE, BACKSPIN rallies. To illustrate, a classic drill is the Falkenberg. This can be run using DRIVE 1) L>R 2) R<L 3) L=L or 3) M=M to make it easier. Settings can be adjusted to modulate difficulty.  
9. The current design of these settings means that it is more work to arrange drills for strokes don't follow the order. For example, having TOPSPIN followed by BACKSPIN will mean having to move items around. The Eleven ball machine will be implementing a shuffle feature in future which will allow more irregular drills which will mimic real life play as the player will not know what will be coming next. 
10. Nearly all settings use minor variation for as many parameters as possible. The logic is that this allows for better transfer for playing non-robots in actual rallies, who naturally hit with lots of variations on each shot. This may occasionally mean balls hitting the net or coming off the table. Alter settings to reduce parameter spread if it is a problem. Also reduce variation to reduce difficulty and if you are focusing more on technique. 
11. Some settings will have a random machine and/or ball placements, and drills can be set up to include these. Some ways to maximise variation (and make you work harder) is to have a central robot and vary the angle (Rand in the settings), or to keep angle roughly the consistent and vary the horizontal (X coordinates) position of the robot (RandX).  These often come last in drills, and so are ordered within a stroke block, though some drills involve varying between a particular stroke and a random stroke (e.g. FH, random, BH, random, FH etc..), so these shots could be moved.
12. Unlike a drill with a person, with an IRL ball machine or with a coach multi-ball feed, you can hit the ball anywhere as no-one will return it. But the Eleven robot can be moved. While you are unconstrained on where you can hit, and might want to vary each time (e.g. hit to FH, then BH then FH etc...), ideally you should hit to where the robot will hit their next shot from (if known). As a general rule, hitting back to where the opponent is not a great way to win points, so getting the robot moving round the table will encourage you not do this, and give you a target to aim for. 
13. To simulate IRL as best as possible, try to use time intervals in regular drills where the robot fires at approximately the same time as you hit it (this will obviously depend on how fast and early you hit the ball).  
14. At the time of writing, the Eleven robot just does sequential ordering, but shuffle is a feature that is due to be added. 
15. Note on: YOUR OWN SERVE
    The current Eleven robot doesn't allow you to serve in the ball machine mode (there is a separate option for pure serve practice). But it can be useful to simulate a rally where you serve and then have to respond to an opponent return. To facilitate this YOUR OWN SERVE throws up an easy ball which you are meant to serve to just like it was your own toss of the ball. This can be moved to better match your own ball toss position. You can then transition to an opponents "2nd ball" return to setup your "3rd ball" attack. 
    Note on: DRIVE
    These are called DRIVEs which prototypically are hit as flat (no spin shots) but the settings currently use topspin, so could have been called TOPSPIN DRIVES, but I didn't want to have too many settings is becomes harder to navigate`. These shots are "bread and butter" for setting up standard rallying drills, and so can be customised (e.g. to reduce spin to make them more standard DRIVEs). 

# Ideas for drills

- Drills can be classified into three types:
  **Systematic/Regular**: A regular pattern of strokes, e.g. hit FH, then BH, then FH etc... Best for working on basic mechanics of stroke production and movement.
  **Semi-systematic and irregular**: Semi-systematic drills will follow a pattern where there will be a number of shots followed by a random shot, or alternation between a fixed shot and a random. 
  **Point simulation**: mimicking the pattern of play. 
- You can use the machine to create all these kinds of drills.
- For example, you can implement the regular classic Falkenberg drill (see below) with the following:
- DRIVE L>R - you hit FH, DRIVE R-L, hit BH, DRIVE L=L, hit FH
- Difficulty can be varied by changing speed or the angle you have to move. This is a great cardio workout, which you could make intense (a "wide" Falkenberg) by manipulating settings to make the distance you travel larger. 
- This could be made into an irregular drill by adding a 4th ball machine shot such as DRIVE Rand which could land anywhere (and you try to hit with a FH)
- An example of a point simulation might involve something like: SERVE 1 (which you can vary in difficulty by changing the side spin amount), you return by pushing long to the right side which the robot returns with BACKSPIN R=R, for a ball that you attempt to loop crosscourt with your forehand (away from the last position of the robot). But the possibilities are large. 
- For inspiration of using and creating your own drills, see some of the resources below.  

# Online drill resources

- 96 Drills -RoboPong 3050 XL (**highly recommended**)
  - https://shop.sport-schreiner-tischtennis.de/media/pdf/robopong/3050XL_Owners_Manual_Engl.pdf
  - https://www.youtube.com/watch?v=ezCPxECO-90
- 64 Drills - RoboPong 2050 
  - https://www.youtube.com/watch?v=PR_6GjVrJWs
  - https://cdn.shopify.com/s/files/1/2677/3302/files/1055_2055-Owners_Manual-6.11.18.pdf
- AMICUS Robot drills 79-99
  - http://www.butterflyonline.com/Templates/AMICUS-Professional-English-2015.pdf
- Ping Skills Drills (**highly recommended**)
  - https://www.pingskills.com/uploads/pdf/free-downloads/TSRDrills.pdf
- Best beginner drills to use with a robot? - OOAK Table Tennis Forum
  - https://ooakforum.com/viewtopic.php?f=16&t=16294
- Beginner Table Tennis Tips - Practice Drills
  - https://www.allabouttabletennis.com/table-tennis-tips.html
- The Falkenberg Drill and Why You Should Be Doing It
  - https://www.experttabletennis.com/the-falkenberg-drill/
- 10 training drill ideas for the first five shots in a rally
  - https://www.tabletenniscoach.me.uk/10-training-drill-ideas-for-the-first-five-shots-in-a-rally/

# Youtube Coaching Videos

- [YangyangTT](
  https://www.youtube.com/channel/UC10OPVuU4Ttsu1a9lW5r4Sg)
- [Ping Skills](
  https://www.youtube.com/user/pingskills)
- [Tom Lodziak](
  https://www.youtube.com/channel/UCqHc12tVGhzBtlMUq7MR7wA)
- [TableTennisDaily](
  https://www.youtube.com/watch?v=a2qDUlEe1ck&t=294s)
- [MLFM Table Tennis](https://www.youtube.com/channel/UChGPHBTi6BG9lHnWk6BgQsQ)
- [PingSunday EmRatThich](
  https://www.youtube.com/user/EmRatThichVo)

# Editing Eleven ball machine settings 

## For installing

- Download .json file - do not change name of "BallLauncherSettings.json"
- For Quest, use Sidequest to navigate to:
  sdcard/android/data/quest.eleven.forfunlabs/settings/
- For PC, navigate to:
  ...
- (Optionally) Back up existing BallLauncherSettings.json file
- (Optionally) Copy your existing settings to the downloaded.json using a text editor (note if appending: last individual setting should not have a comma at end)
- Replace with downloaded .json

## For manually editing

- Use an offline edit with .json syntax highlighting and folding (e.g. Notepad++ on Windows) or online editor such as https://codebeautify.org/jsonviewer
- Use online processor to check for .json parsing errors (e.g. missing a comma) 
