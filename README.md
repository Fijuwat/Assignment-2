# Assignment-2 API Experiment
I want to test if Englsih "Pinyin", which is typing Mandarin in English will be detected by the system.
I hypothesize that the dataframe won't really count "Pinyin" as words since it's a system for different languages but not for different language in different phonetic transcription. I also hypothesized that when a verbally abusing word is combined with another word especially in context, its toxicity will decrease.

## Hypothesis and experiment
I want to test if Englsih "Pinyin", which is typing Mandarin in English will be detected by the system.
I hypothesize that the dataframe won't really count "Pinyin" as words since it's a system for different languages but not for different language in different phonetic transcription.


1. Wo Ai Ni = I love you 
2. xiè xie = Thanks 
3. Gan = Fuck

## Conclusion (Result)
I conclude that my hypothesis is actually right since all of my result can't run an output, which means that the dataframe doesn't contain words ("Pinyin") that I had enter. Thus, when people are using Pinyin to swear, curse, or making recist statements, the system can't really detect it. Therefore, the dataframe really should add on new data for Pinyin to stop the verbal abuses using Pinyin.  


## Hypothesis 2 and experiment 2
I have try out different combinations of words and form different sentences.

I hypothesized that when a verbally abusing word is combined with another word especially in context, its toxicity will decrease.

I will test these following queries in order to test my hypothesis.
1. Fuck 
2. Fuck you 
3. I fuck you 
4. I fucking you
5. you fuck me 
6. fuck the cake
6. shit
7. you are shit
8. you are shitty
9. you are shitting
10. stop shitting me
11. that cake is shit
10. Bitch 
11. you are a bitch
12. we are bithes
13. you are bitchy
14. We love to be bitch
15. Son of a bitch
16. bitch cake

## Conclude (Result)
After the experiment, I think my hypothesis is being rejected.
I originally if the verbally abusing words are combined with other words, its toxicity will drop. However the experient shows that, if the system detect that the verbally abusing words are pointing toward "someone", the toxicity will actually be raised by the other words that is added into the sentence, for example the score of "fuck" is lower than that of "fuck you" even though "fuck you" have two words instead of one, it is still higher since it's pointing to "you".
