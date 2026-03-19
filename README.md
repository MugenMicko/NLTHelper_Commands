# NLTHelper Commands
Series of commands to trigger items in NLT  Helper


[Link to NLT Helper](https://github.com/starfishmod/NLT-Helper)

[Random Grouping Generator](https://www.randomlists.com/team-generator)

[YouTube Video teaching how NLT Helper Works](https://www.youtube.com/watch?v=nXCQyP0KglI)

## Only to be used the first time you setup NTL Helper

Generate API Key in NLT\NeonTiming
Run ```api_key XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX``` Only required first time running software
```
Run ip 127.0.0.1
```

## Everything beyond required each race meet
```
dropHeats 1
```
```
points 20 18 17 16 15 14 13 12 11 10 9 8 7 6 5 4 3 2 1
```
Pick a name for event ie Craiola19Mar2026 (Do not use "/", only letters numbers and underscores "_")
```
newevent Craiola19Mar2026
```
```
addclass mini_z
```
If you choose to run additional classes, they will need to be added accordingly. ie you may want to run a box stock and mod class instead of straight Mini Z and these setup would be added as per below:
```
addclass boxstock
```
```
addclass mod_mini_z
```

Inform first group that race is about to start and they are required to line up to race, other racers are to marshall the race.
If you have used different class names the syntax is as follows  `nextheat <classname> <round number> <group letter>`
```
nextheat mini_z 1 a
```
Announce race end, prior racers to put car and radio down and get to marshalling positions
Announce next race group
Trigger Race
```
nextheat mini_z 1 b
```
Announce race end, prior racers to put car and radio down and get to marshalling positions
Announce next race group
Trigger Race
```
nextheat mini_z 2 a
```
Trigger Race
```
nextheat mini_z 2 b
```
Announce race end, prior racers to put car and radio down and get to marshalling positions
Announce next race group
Trigger Race
Calc results as below
```
results mini_z
```
```
splitfinals 4 mini_z
```
Announce racers finals, request B Main to line up and A main drivers to marshall
```
final mini_z b
```
Announce End of Race, driver to bump, all non bumping drivers to marshall and A main drivers to line up
Trigger Race
```
final mini_z a
```
Announce End of Race
```
results mini_z
```
Deliver Results
