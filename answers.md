# How does it respond to: 
#   My mother and I talked last night.
    Tell me more about your family.
#   I said no!
    Why so negative? 
#   The weather is nice.
    Hmmm.
#   Do you know my brother? 
    Why so negative?

#   Keyword         Response
    joe             Joe mama! jajajajajaja
    youre mom       tu madre es gordo!
    dylan is bad    yeah he is, god

# What happens when more than one keyword appears in a string? consider the string "My mother has a dog but no cat." Explain how to prioritize responses in the reply method. 
It reads the first keyword and the code ends with it printing the response based on what it read first. You have to put it first to prioritize it. 

# 1. What happens when a keyword is included in another word? Consider statements like "I know all the state capitals" and "I like vegetables smothered in cheese." Explain the problem with the responses to these statements. 
Whenever you say those statements, it will print out "Why so negative" to the kNOw the state capitals statment. For the word sMOTHERed, it will ask you more about your family. It is a problem because the bot isn't doing what it's supposed to. It looks for keywords in order in the code and whichever it sees first is the one it returns as the response. 