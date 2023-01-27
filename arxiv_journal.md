
# ArXiv Journal

The way scientific discovery is organized makes it work but it could work way better. There are inefficiencies that are huge. For starters, people collaborate way less than what they should. There is no centralized "Wikipedia" for science (except maybe wikipedia itself) but advances are usually distributed in numerous individual (e.g. scientist or team) contributions. It is the task of the scientists to keep track of the state of their fields in their minds. This means that it's usually hard for researchers to know who else is working or starting to work on a given topic, to be well-informed about what the state-of-the-art is and something that is seldom mentioned, it's hard for them to wisely choose a topic to work on.

We are seeing, specially in AI, a lot of new work being produced that makes the inefficiencies more accute. In particular, the sheer amount of written new knowledge makes it hard to actually find the most relevant or the best articles: they lie along hundreds of bad articles. The "top" conferences (e.g. NeurIPS, ICML, CVPR, etc.) no longer host only "great" works but they add a lot of noise. They're hosting more than 2k papers per year, each!

The peer review system is also kind of broken. Although the anonimity promises reviews to be less biased, the affiliations and names are one of the most important pieces of information researchers use nowadays to quickly consider to read or not a given article (because affiliations are a relatively cheap proxy needed to navigate the noise). 

It's also important to note that science is many times based on the good faith of researchers. It isn't that hard to publish an article saying "we did X" without really having done X. This doesn't make reviewers cynical and they usually trust that the written lines are true. Such good-faith is also asumed when building impactful collaborative information management infrastructure such as Wikipedia or Stack Exchange. 

We need such impactful collaborative information management infrastructure for science too. We need it to do better research faster. Here comes how such a future solution could look like:

- researchers publish papers in arXiv
- researchers host code in github repositories 
- if applicable, researchers create a demo using huggingface spaces
- they are all linked together

All of this already exists to some extent, paperswithcode.com allow researchers to see code and papers linked, huggingface spaces is similar and they're probably going to be integrated on arXiv. What is lacking?

connectedpapers.com is good to check related work and we'll probably have a big language model helping us query all of arXiv. What is lacking?

What is lacking is the peer review system. A way to score papers that help us navigate the noise. openreview.net is a nice initiative that needs to be taken forward.

## The proposal
Allow researchers to rate papers. Nowadays the best metric we have are github stars per day in paperswithcode.com. We should be able to go into arXiv and see the punctuation of a paper and rate it ourselves. It can be a single score at first and more granular scores later. To difficult the spamming we can integrate captchas and standarize the opinions of all reviewers. We should be able to review the paper and the authors should be able to answer. Later we can create a list with the best rated papers in the last X days and create a journal with big impact out of it.

## A second proposal
Complementary to the previous proposal is the Unified arXiv. The Unified arXiv would be a tree of research questions and theoretical/experimental answers or a similar monolitic document. In fact, the only thing we need to get such unified arXiv is a querying function (a large language model with references) and an ordering function that tells us where to go next (e.g. if we are learning). It would be nice to extract the research questions, provide answers as quotes, and provide related interesting research questions.

## A third proposal
It would be also nice to have the ability to extend or edit an arXiv paper. This is, have an original version and a collaborative version that has been edited by different people. Who did what can be checked to not lose the incetives of the current system that is very much based on the assignment of individual responsability over a piece of work.

## misc
- a way to check if a given image was or not in the training set: checking belonging to predefined training sets.