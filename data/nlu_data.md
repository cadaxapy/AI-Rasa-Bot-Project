<!--- Make sure to update this training data file with more training examples from https://forum.rasa.com/t/rasa-starter-pack/704 --> 

## intent:goodbye <!--- The label of the intent --> 
- Bye 			<!--- Training examples for intent 'bye'--> 
- Goodbye
intent:weather
What is weather in Bishkek
Weather in Naryn
weather in Bangkok
Какая погода в London
what's the weather in Berlin
what's the weather in Moscow
what is the weather in California
what is the weather in New Zealand
whats the weather in Dubai
what is the weather like in Almaty
how is the weather in Astana
how's the weather in Osh
hows the weather in Pekin
- See you later
- Bye bot
- Goodbye friend
- bye
- bye for now
- catch you later
- gotta go
- See you
- goodnight
- have a nice day
- i'm off
- see you later alligator
- we'll speak soon

## intent:greet
- Hi
- Hey
- Hi bot
- Hey bot
- Hello
- Good morning
- hi again
- hi folks
- hi Mister
- hi pal!
- hi there
- greetings
- hello everybody
- hello is anybody there
- hello robot

## intent:thanks
- Thanks
- Thank you
- Thank you so much
- Thanks bot
- Thanks for that
- cheers
- cheers bro
- ok thanks!
- perfect thank you
- thanks a bunch for everything
- thanks for the help
- thanks a lot
- amazing, thanks
- cool, thanks
- cool thank you

## intent:affirm
- yes
- yes sure
- absolutely
- for sure
- yes yes yes
- definitely


## intent:name
- My name is [Juste](name)  <!--- Square brackets contain the value of entity while the text in parentheses is a a label of the entity --> 
- I am [Josh](name)
- I'm [Lucy](name)
- People call me [Greg](name)
- It's [David](name)
- Usually people call me [Amy](name)
- My name is [John](name)
- You can call me [Sam](name)
- Please call me [Linda](name)
- Name name is [Tom](name)
- I am [Richard](name)
- I'm [Tracy](name)
- Call me [Sally](name)
- I am [Philipp](name)
- I am [Charlie](name)
- i m [Radj](name)


## intent:joke
- Can you tell me a joke?
- I would like to hear a joke
- Tell me a joke
- A joke please
- Tell me a joke please
- I would like to hear a joke
- I would loke to hear a joke, please
- Can you tell jokes?
- Please tell me a joke
- I need to hear a joke

## intent:weather
- What is weather in [Bishkek](city)
- Weather in [Naryn](city)
- weather in [Bangkok](city)
- Какая погода в [London](city)
- what's the weather in [Berlin](city)
- what's the weather in [Moscow](city)
- what is the weather in [California](city)
- what is the weather in [New Zealand](city)
- whats the weather in [Dubai](city)
- what is the weather like in [Almaty](city)
- how is the weather in [Astana](city)
- how's the weather in [Osh](city)
- hows the weather in [Pekin](city)


## intent:translate
- Please, translate [cat](word) to [russian](lang)
- translate [dog](word) to [english](lang)
- can you translate [apple](word) to [german](lang)
- translate pls [bottle](word) to [chinese](lang)
- translate me [table](word) to [kyrgyz](lang)
- translate me please [window](word) to [french](lang)
- translate word [tea](word) to [polish](lang)
- translate me plz [spoon](word) to [romanian](lang)
- translate me [mouse](word) to [korean](lang)
- translate me [banana](word) to [turkish](lang)
- what is [laptop](word) in [japanese](lang)

## intent:wiki
- what u know about [bishkek](wiki_word)
- do u know what is [python](wiki_word)
- give me information about [acer](wiki_word)
- show me info about [xiaomi](wiki_word)
- what is [apple](wiki_word)
- what you know about [microsoft](wiki_word)
- give me some information about [starbucks](wiki_word)
- tell me what is [cola](wiki_word)
- give me information about [dell](wiki_word)
- show me information about [asus](wiki_word)
- show me information about [auca](wiki_word)
- information about [namba](wiki_word)