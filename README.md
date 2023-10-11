![banner_purchase_propensity](https://github.com/lorainemnrc/predict-purchase-propensity/assets/23328647/ede5eb16-d905-4dd0-af1d-b3b6abdd9db2)

<h1 style="color: #1048CB"><b>Overview</b></h1>

<p style="text-align: justify"> &emsp;The e-Commerce industry is pegged to be the future of retail in the Philippines given the increased digital adoption in the country due to the pandemic. However, customer drop-offs brought by product complexity and low purchase intent limit a business’ growth potential. While there are already efforts made in tracking and analyzing these drop-offs, knowing which aspect to focus on in the customer journey remains a challenge as there can be many points of exit that should be improved with a limited budget. Using Explainable AI, this project aims to uncover the main purchase decision drivers, and the small changes the business can do that would greatly encourage a customer to stay and proceed to purchase.</p>

<h1 style="color: #1048CB"><b>Data Source/b></h1>

<p style="text-align: justify"> &emsp; The data used in this project is sourced from [`UCI's Machine Learning Repository`](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset#), and is about how a visitor navigates through a site and whether the visit resulted to purchase or not. With 12,330 total sessions, the data includes details such as the visitor profile, value of the pages viewed, seasonality of the visit, ease of search, interest in buying, and web traffic quality. Table 1 provides a brief description of the features in the dataset.</p>

<br>
<center style="font-size:12px;font-style:default;"><b>Table 1. Online Shoppers Purchasing Intention - Data Dictionary</b></center>

|Feature    | Data Type     | Description                                                                           |
|:--------------|:-------------|:--------------------------------------------------------------------------------------|
|administrative|integer|indicates if the page is an administrative page. 1 if true, otherwise 0
|administrative_duration|float|indicates the duration of visit in an administrative page
|informational|integer|indicates if the page is an informational page. 1 if true, otherwise 0
|informational_duration|float|indicates the duration of visit in an informational page
|product_related|integer|indicates if the page is an product page. 1 if true, otherwise 0
|product_related_duration|float|indicates the duration of visit in an product page
|bounce_rates|float|indicates the bounce rate of a user across page visits
|exit_rates|float|indicates the exit rate of a user across page visits
|page_values|float|indicates the value of the page based on a google formula
|special_day|float|indicates whether the visit was near a speciay day. e.g. a holiday
|month|string|tells the month of visit
|operating_systems|integer|indicates the type of operating system used to enter the site
|browser|integer|indicates the type of browser used to enter the site
|region|integer|indicates region of the user
|traffic_type|integer|indicates the type of traffic type used to enter the site
|visitor_type|string|indicates the type of user visiting the site
|weekend|integer|indicates if the site visit happend during a weekend
|revenue|integer|indicates whether the site visit resulted into a sale


<h1 style="color: #1048CB"><b>Highlights</b></h1>

<p style="text-align: justify"> &emsp;There are 3 main drivers that affect a customer's decision to purchase - the value of the pages visited, seasonality of the visit, and ease of search. </p>

<p style="text-align: justify"> &emsp;1. For *Seasonal visitors*, the focus is to reduce the complexity of the experience and ease their search. This can be done by improving the design and usability of the pages, or implementing a recommender system for a more personalized user experience. </p>

<p style="text-align: justify"> &emsp;2. For *Non-Seasonal, Returning visitors*, it's important to increase their intent to purchase and ease their search of relevant products. These visitors could be encouraged to convert through marketing initiatives such as Nudge, which makes use of subtle prompts as a reminder to complete their purchases. </p>

<p style="text-align: justify"> &emsp;3. For *New visitors*, the focus should be on building trust and reducing complexity in their experience. Required personal information should be moderated for new users, and measures implemented to secure personal data and payment information should be apparent. Moreover, the onboarding process should be seamless, and relevant promotional offers could be shown but must not be overwhelming </p>

<p style="text-align: justify"> &emsp; Identifying these factors towards customer propensity will be a big help for e-commerce website operators. This allows them to better optimize their website design in order to maximize the likelihood of a successful transaction. These e-commerce operators can add seasonality promotions and bundles to entice seasonal visitors and give them a reason to purchase. They can streamline the website in order to increase the user experience of returning visitors and steer them towards the products they are looking for and most likely to purchase. And on top of that, these e-commerce operators can design their websites to be intuitive, easy to access, easy to join, and user-friendly for new visitors who are curious about the e-commerce platform. </p>

<p style="text-align: justify"> &emsp; A fully online transaction is inherently more challenging to control since the customer holds all the power with no salesperson to direct them to a possible purchase. Using the power of machine learning and explainability methods, allows these e-commerce operators to better understand their customers and help them design better experiences. </p>
