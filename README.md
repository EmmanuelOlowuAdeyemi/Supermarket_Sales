<!DOCTYPE html>
<html>

<head>
</head>

<body>

<h2>About This Dataset:</h2>
<p>This dataset provides historical sales data from a supermarket company with records spanning three months across three different branches. The dataset offers valuable insights for predictive data analytics applications, given the dynamic market landscape characterized by the rapid growth of supermarkets and intense market competition.</p>

<h2>Scenario:</h2>
<p>In an environment of escalating growth and competitive challenges in densely populated cities, this dataset captures the sales dynamics of a supermarket chain's three branches. The dataset's temporal span of three months and comprehensive attributes enable the application of predictive data analytics methods to uncover trends and patterns that can inform strategic decisions.</p>

<h2>The Dataset Columns:</h2>
<ul>
    <li><strong>Invoice ID:</strong> Auto-generated identification number for sales transactions.</li>
    <li><strong>Branch:</strong> The branch of the supercenter, categorized as A, B, or C.</li>
    <li><strong>City:</strong> Location of the supercenters.</li>
    <li><strong>Customer Type:</strong> Type of customer, classified as 'Member' for those using a member card and 'Normal' for those without.</li>
    <li><strong>Gender:</strong> Gender of the customer.</li>
    <li><strong>Product Line:</strong> Broad categorization of items, including Electronic Accessories, Fashion Accessories, Food and Beverages, Health and Beauty, Home and Lifestyle, and Sports and Travel.</li>
    <li><strong>Unit Price:</strong> Price of each product in dollars ($).</li>
    <li><strong>Quantity:</strong> Number of products purchased by the customer.</li>
    <li><strong>Tax:</strong> 5% tax fee applied to the purchase.</li>
    <li><strong>Total:</strong> Total price, including tax.</li>
    <li><strong>Date:</strong> Date of purchase (Recorded from January 2019 to March 2019).</li>
    <li><strong>Time:</strong> Time of purchase (From 10 am to 9 pm).</li>
    <li><strong>Payment:</strong> Payment method used by the customer (Cash, Credit Card, Ewallet).</li>
    <li><strong>Gross Margin Percentage:</strong> Gross margin percentage.</li>
    <li><strong>Gross Income:</strong> Gross income generated.</li>
    <li><strong>Rating:</strong> Customer satisfaction rating based on shopping experience (Rated on a scale of 1 to 10).</li>
</ul>
<p>Find <a href="https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales">Dataset</a></p>

<h2>Cleaning and Transformation:</h2>
<p>First, cleaning and transformation had to be done on Excel. In order to present a workable dataset, I dealt with the following:</p>
<ol>
    <li>Null values</li>
    <li>Duplicate rows</li>
    <li>Renamed Column</li>
</ol>
<p>The cleaned dataset was also done in Excel for transformation.</p>
<ol>
    <li>Conditional Column for Tax 5%, Total, Gross Income and Rating</li>
    <li>Sort column 'Commute Distance' by Changing 10+ Miles to More Than 10 Miles</li>
    <li>Breakdown of Date stamp into Months (January, February, March)</li>
</ol>

<h2>Visualization:</h2>
<p>The analysis of the dataset offers a comprehensive understanding of customer behavior, sales distribution, and engagement levels across different categories, locations, and time periods. The examination highlights potential trends and opportunities for optimizing business operations and driving growth. Notable findings include a well-balanced gender distribution across the three locations, with Yangon showcasing the highest customer count, indicating a thriving market. The customer type distribution across product lines is evenly spread, suggesting a diverse customer base. 
While this balance is positive, there's potential to attract more members to certain product lines that are currently underrepresented. Moreover, female customers are predominant across all tax rate levels, which might influence overall tax contributions and financial dynamics. The distribution of gross income levels across months reveals variations in spending behavior, particularly in March, suggesting possible seasonality. The distribution of total price levels across months provides insights into spending patterns during different periods. Customizing pricing strategies or promotional offers to leverage periods with lower total price counts could be advantageous.</p>

</body>

</html>
<img src="https://github.com/EmmanuelOlowuAdeyemi/Supermarket_Sales/blob/main/Supermarket_Sales/SUPERMARKET%20SALES%20DASHBOARD.png" alt="Supermarket Sales Dashboard">
