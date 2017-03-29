## Report 2 Review
### Review of [The Association Between Drug Usage and Depression](https://github.com/davpapp/ThinkStats2/blob/master/Reports/report2.md)


###### First Impressions:
Having the motivating question as the title does make it easy to identify the motivating question. I also like the introduction restating it, and explaining where the data comes from. Overall, I also felt like report flowed pretty well.

###### Structure and Style


The biggest problem is the way that the results of the regressions are presented. All the data is there, which is good, but it's hard to immediately pick out what is important from what the library returns. It would be especially difficult for readers who hadn't used the statsmodels library for their regressions.

In the data-mining, it's hard to tell what the what the diseases are that are correlated with depression, and what the motivation was for finding them. I eventually realized that they were more control variables, but I'm still not quite sure why they are there, since they don't seem like they would help determine whether drugs are associated with depression.

###### Formatting and Typos
- In the methodology section, you mention controlling for 'AGE, SEX, INCOME, race': race is the only one not capitalized.
- In line 5 of the Jupyter notebook, you print the variables, making it difficult to read on Github.