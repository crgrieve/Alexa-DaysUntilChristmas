# Alexa-DaysUntilChristmas
Advent calendar skill tutorial built for teaching kids to code. 

I would recommend this tutorial as a starting point on Alexa skills introducing how to set up accounts on AWS and Amazon developer portal: https://developer.amazon.com/alexa-skills-kit/alexa-skill-quick-start-tutorial

## Intent:
```
{
  "intents": [
    {
      "slots": [
        {
          "name": "Day",
          "type": "LIST_OF_DAYS"
        }
      ],
      "intent": "DayIntent"
    },
    {
      "intent": "AMAZON.HelpIntent"
    }
  ]
}
```
## Slots:

LIST_OF_DAYS 
```
1
2
3
4
5
6
...
30
```

## Utterances:
```
DayIntent Open day {Day}
DayIntent Open door {Day}
DayIntent What's in door {Day}
DayIntent Advent door {Day}
```
