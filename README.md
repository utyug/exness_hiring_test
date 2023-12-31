Hello there!

If you are going to join our team of researchers and analysts at Trading Division of Exness we have a test task for you here.

The task is the following. Suppose your collegues developed some cool feature and conducted an A/B test for a group of clients. But unfortunetely they lost the information about control group clients ;) Your goal is to help them with post analysis of the test results. 

What you have is data on all clients from which the test clients were selected, some relevant features to take in account and couple of metrics of interest the test was aimed to increase.

Specifically, in the data folder you will find zipped csv dataset with the following columns:
* `user_uid` - hashed client identifier
* `country` - encoded country of client's origin
* `traffic_source` - encoded channel of attraction
* `days_since_reg` - number of days from the first time client visited our platform to the date of test launching
* `value_segment` - client's value segment
* `rev_pre` - revenue collected for some fixed period (90 days) before the test launching date
* `rev_post` - revenue collected for some fixed period (630 days) after the test launching date
* `profit_pre` - profit collected for some fixed period (90 days) before the test launching date
* `profit_post` - profit collected for some fixed period (630 days) after the test launching date
* `is_test` - flag indicator for clients included in test group 

What we expect you to do: 
* Come up with some solution with relevant control group selection
* Make an estimation of uplift in terms of two metrics of interest (`rev_post`, `profit_post`) and its statistical significance 
* Wrap up your solution as reproducible code in jupyter notebook and concluding part with short summary of your results

Hope you will enjoy the task ;) 
Good luck!

