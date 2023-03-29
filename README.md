# Training-data
How Much Training Data Do You Need?


There isn’t a hard-and-fast-rule but tasks like training a model to analyze the sentiment of brand mentions will require far less data than something that needs an incredibly confident model, like self-driving cars.

With text analysis, it all depends on the use case and the number of tags you need. As a general rule of thumb for training MonkeyLearn models:

Topic detection: at least 100-300 samples per tag.
Sentiment analysis: at least 500-1,000 samples per tag.
Intent classification: at least 100-300 samples per tag.
Urgency detection: at least 100 samples for the Urgency tag and 200 samples for the Non-Urgent tag.
The more you train your model, the smarter it will become, so it’s always safe to err on the side of “a lot of training data.”
