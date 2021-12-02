# AI as a product
A selection of machine learning resources

https://twitter.com/rharang/status/1465340194606002177?s=20

To be able to use AI "for real," as in use it to (eventually) save you money and not just make a nice paper for an academic conference, you usually need a problem with as many of the following attributes as possible

- The cost of errors needs to be *extremely low*. AI will inevitably make mistakes. You want those mistakes to be of the "I had to push the button twice" variety, not the "my car just rammed a school bus at 80mph" kind. 
- The decision needs to be possible but expensive for a human to double-check; "Is this blurry image a cat or a dog?" and not "is this specific network packet bad or good?"  If you can't check, you have no idea if your AI is working. If it's cheap, just don't use AI at all
- There needs to be a lot of the same kind of decision. The best zucchini-vs-volleyball detector in the world doesn't matter if that decision is only relevant once a week
- There needs to be an actual benefit from making the right decision: if you put the right product in front of your customer and that increases sales, that's good. If you can tell when a customer is grumpy but don't have anything to do with that information, that's bad.
- The cumulative benefit from making the right decision has to outweigh the combined benefit of "I'm just using a dumb rule and it does ok-ish" plus "...but I didn't commit to the lifetime care and feeding of a deep learning model." Did you try picking the most common class?
- You have to not care all that much about how it got to the answer, only aggregate performance statistics. AI models are famously difficult to interpret, and attempts to create post-hoc explanations generally haven't worked out that well.
