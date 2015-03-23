# Twitter Domain (Requirements): #

Twitter messages have certain unique attributes that make it complex to analyze and classify while training the data set. Some of them are as follows:

  * **Length:** The maximum length of a Twitter message is 140 characters, thus the limited length of tweet, might be comprising of one or two sentences.

  * **Language model:** The language under consideration is English. Basic problem faced is the limited length which encourages the user to use slang and acronyms. Moreover users post tweet from different devices including mobile phones, thus increasing the rate of misspelling words.

  * **Negative sentences:** many people would write their tweets with negation before the adjective or verb, which complicates the training set. For example: a sentence such as NOT satisfied with the situation of the Senate in the U.S. has the adjective satisfied which assigns a positive polarity without considering the negation in the sentence.

  * **Dealing with emoticons:** The training data should contain clean labels. The emoticons serve as a noisy label. There are some cases in which the emoticon label would normally not make sense to a human evaluator.

  * **Casual language:** Tweets contain very casual language. For example, a user may want to right the word happy as: happpppppyyy/happpiieee/happy besides showing that people are happy, this emphasizes the casual nature of Twitter and the disregard for correct spelling.