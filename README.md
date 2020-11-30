# detectingFakeNews

Looking at machine learning algorithms to detect fake news.

## showing news that is similar
What is the problem?
     - Find news articles similar to one youre reading from different sites.
       The idea is to get diffarent perspectives


aproach 1:
- more rule based.
- if they share the same "tags" then they are about the same thing
- if the dates are around the same time, they probably are similar

aproach 2:
- KNN
- The date could be used as a validation
- Words used in the body would be used for perameters of KNN
- The words in the title will label the news articles
