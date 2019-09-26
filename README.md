# CourseraDATAMETHODOLOGY
Data Methodology Case Study

Which topic did you choose to apply the data science methodology to?

ANS: I choose credit cards in a scenario where we should use information of credit cards companies in order to identify business opportunities

Next, you will play the role of the client and the data scientist.

Using the topic that you selected, complete the Business Understanding stage by coming up with a problem that you would like to solve and phrasing it in the form of a question that you will use data to answer. 

You are required to:

Describe the problem, related to the topic you selected.
Phrase the problem as a question to be answered using data.
For example, using the food recipes use case discussed in the labs, the question that we defined was, "Can we automatically determine the cuisine of a given dish based on its ingredients?".

ANS:    Problem description:

Finding business opportunities is a big challenge for entrepreneurs, the natural tendency is to start a related business close to one that is already successful, however there could be some missed opportunities for complementary products.

Evaluating the market situation and identify the potential growth of different kind of business from the ground could be very hard and with low accuracy, however credit cards has data of consumption per business that could be classified and sorted by several criteria, they also have information of each business, their products, location, etc.

Of course the data won’t be complete as some people pay in cash but, as long as we are looking for trends the gaps may not be relevant


Question:

Based on credit card consumption data of business in a given geographic sector, is it possible to identify a business opportunity?

Briefly explain how you would complete each of the following stages for the problem that you described in the Business Understanding stage, so that you are ultimately able to answer the question that you came up with. (5 marks):

Analytic Approach
Data Requirements
Data Collection
Data Understanding and Preparation
Modeling and Evaluation
You can always refer to the labs as a reference with describing how you would complete each stage for your problem.


ANS: 1. Analytic Approach
As long as we are looking for business that some how could be related, it is necessary to use a descriptive model. It would be also useful defining clusters within certain area.

2. Data Requirements

Always keeping in mind our goal is to identify opportunities of related business, we would not need to collect the business names but its location (address), the type of business (food, cuisine, sports, etc). Historical data of consumption in each business. It will be necessary to collect information from several sources at least the most common used or accepted in most part of the business.
It will also be necessary a list of products per industry type with sales information so the pre selected business could be expanded in related products.
Credit cards use their information to provide re targeting services to other companies, detailed information of business is probably confidential, how ever consolidate information with out the names and fiscal registration may be available for commercial purposes. It would be necessary to contact the B2B department and request the information described above for, at least, the last 3 years so we could identify seasonality, and market trends.
Products list could be find in any official national statistic organization. In Ecuador is the Central Bank the one who collects and publish data per product classified by the CIIU code. This information should be one year late how ever, as long as there is enough data from several years it could be possible to get an approach of -to date- data.
There could be two possible scenarios where there is a business opportunity. The first one is when product information shows high sales of some product and in the area there are few places where the item is sold and the second one when information of the area show a high sales of any product but complementary products aren’t offered in the same area

3. Data Collection

Information from credit cards should be in a structured form but it would be necessary to obtain weekly and monthly consumption, as long as product sales information from Central Bank have also other data attached to each product, it would be necessary to remove that unwanted information.
Data of products could be in a unustructered form so it would be necessary to define the fields, depending on the amount of rows it could be used Python or some other program in Jupiter notebooks.

4. Data Understanding and Preparation
Some data could be incomplete so we should figure out if it is necessary or if we can skip it. Some other information could present the same product with different names so we would want to fix that.
There will be in the product database a lot of information of different products such as gasoline that we will not be interested in son viewing the list of products and the amount of records should help us to concentrate in those we want to analyze. Then we should remove unnecessary data.

5. Modeling and Evaluation

As long as we’re working on a descriptive model we would not need a training set, however getting a decent figures of the calculated Up To Date product consumption is necessary because we depend on this information to take the right decisions
We should think that we’re assuming that people who are consuming some product in a defined areas are likely to consume some related product, so the modeling process should take us to estimate the sales of a different suggested related products in a defined area.
Some other market considerations may come out when performing the analysis so the process may be redefined and adjusted to get the best information to make a decision.
