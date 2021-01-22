# NLP_customers_reviews
**_Link to the Medium blog post: https://daria-morgan.medium.com/more-then-just-stars-bd320232572b_** <br><br>
The idea behind this project was to see if I could create some actionable money saving insights from customers’ reviews using NLP.<br><br>
These insights can help either reduce returns, which will increase revenue and profit, create better marketing, or even modify some of these analyzed products instead of discontinuing them.<br><br>
1. For the analysis, I collected more than 15,000 reviews and some of its features such as rating, weight, height, and others. I did it using Python packages (Selenium and Beautiful soup). The code for scraping reviews provided in **_1_Scraping_data.ipynb_** jupyter notebook.<br><br>
2. From all these reviews I decided to dive deep into the bottoms section, specifically jeans, because from my experience they are the most problematic category to purchase online.<br><br>
3. As a part of my analysis, I did topic modeling. I separated reviews into a few topics based on what customers are discussing the most. These topics include: how jeans fit in waistline and hips, size and length of jeans, overall quality and comfort. For that step, I used a special NLP Python library, specifically a NMF algorithm and NLTK for pre-processing the reviews. For this step, please check my code in the following jupyter notebook: **_2_cleaning_data_and_analysis.ipynb_**.<br><br>
4. After dividing reviews by topics I came up with a few business insights and recommendations that can be found in the presentation **_Project_4_Daria.pdf_**.<br><br>
5. Also, few other interesting insights were found by using an NLP method called  Scattertex (**_4_ScatterText.ipynb_**) and Word Cloud (**_3_Word_Cloud.ipynb_**).
