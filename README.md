# NLTHelper_Commands
Series of commands to trigger items in NLT  Helper


[Link to NLT Helper](https://github.com/starfishmod/NLT-Helper)

[Random Grouping Generator](https://www.randomlists.com/team-generator)


Generate API Key in NLT\Neon
Run ```api_key XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX``` Only required first time running software
```
Run ip 127.0.0.1
```
Everything beyond required each race meet
```
dropHeats 1
```
```
points 20 18 17 16 15 14 13 12 11 10 9 8 7 6 5 4 3 2 1
```
Pick a name for event ie Craiola19Mar2026
```
newevent Craiola19Mar2026
```
```
addclass Mini_Z
```
Inform first group that race is about to start and they are required to line up to race, other racers are to marshall the race
```
nextheat Mini_Z 1
```
Announce race end, prior racers to put car and radio down and get to marshalling positions
Announce next race group
Trigger Race
```
nextheat Mini_Z 1
```
Announce race end, prior racers to put car and radio down and get to marshalling positions
Announce next race group
Trigger Race
```
nextheat Mini_Z 2
```
Trigger Race
```
nextheat Mini_Z 2
```
Announce race end, prior racers to put car and radio down and get to marshalling positions
Announce next race group
Trigger Race
Calc results as below
```
results Mini_Z
```
```
splitfinals 5 Mini_Z
```
Announce racers finals, request B Main to line up and A main drivers to marshall
```
final Mini_Z B
```
Announce End of Race, driver to bump, all non bumping drivers to marshall and A main drivers to line up
Trigger Race
```
final Mini_Z A
```
Announce End of Race
```
results Mini_Z
```
Deliver Results
