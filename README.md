# Project_6_SWIFT

**Project Goal:**
- Based on the assigned data to create a Dashboard using Tableau to deliver insight and directions of improvements. Combined with other businees focused insights, this Dashboard can serve as a reference tool when making decisions in cross-border transactions and potential market expansions.

**Dataset**
- A set of transaction details in excel of company Alpha Inc delivered with the service of Paylocator.

**Data Exploration and Processing**
- As there's no unique ID in the original data, actions on matching a few column information to create an identifier with different status indicators were needed. Also, in order to explore as much information as possible, new columns such as Bank Name and Country were also added.

**Charts included in the Dashboard:**

1. First we have a **Pie Chart** showing the distirubution of all transaction status, this is to have an idea of the percentage of completed transactions versus ongoing or pending ones.

2. The second piece of information is the **average Time needed for each transaction**. We did the calculation based on the time difference of the same transaction at status NEW and status COMPLETED.

3. Then we did a **Line Chart** to show the fluctuations of Total Charges (Initial Amount * Charges %) over the months. An reference **Average Line** has also been set to visually spot the months where the charges are higher or lower.

4. Our fourth chart is a **Line Chart** of the Initial Amount by month + a **forecast** for following months. In order to have a smooth line, we put 0 for the months with missing data. **Depending on the directions of the cashflow** (either in or out), we can gain some insight on our business reality as well.

5. Following we have another **forecast on the total number of transactions made by month**. This is done by a bar chart and we can see that the estimated number of transactions in the following months is 2. 

6. The sixth chart is a **Line Chart** indicating **the choice of currency** for the tarnsacitons and their initial amount. We also drew a **Trend Line** to see the potential directions of how each currency and their initial amount could move in the future.

7. Starting from Chart 7 we will focus more on the countries wtith whom the transactions were made. We started with a **Tree Map** showing the choice of banks per country and their representation out of of all transactions.

8. Then on chart 8 we used a **Map** to show the locations of creditors as well as the **percentage of their initial amount** over total.

9. Next, we have another **Map** showing the **Average Transaction Time** in each country. 

10. And on chart 10, we explore **the average charges in each country** in EURO and in USD with a **Bar Chart**. This can tell us how the choice of currency can have an impact on the charges. While in some countries using EURO will have lower charges, in others this might not be the case.

11. The 11th chart uses a **parameter** to filter the view **by Year**. The display is a **Bubble Chart** showing the number of transactions per country per year. The **size** of the bubble also inidicates the number of the transactions in the respective country. 

12. Lastly, we will display a **Map** with key informations from our previous charts. This is also done by a **parameter** using **Country as a filter**. By clicking on a specific country, the key informations of that country will show in the view. 


**Summary and Conclusion:**

As mentioned previously, the purpose of this dashboard is to first of all show stakeholders a **global view** on the situation of our Cross-Border transactions in the past, and gain predictive information about the future with the help of forecast. Secondly, we put an **emphasis on the countries** with whom the transactions were made. By exploring the different elements such as average charges per country per currency, the disrtibution of transaction number in the world, and the total initial amount by country etc, we should be also to conclude some basic insight. Then again, **further investigation and information from other business units such as the purpose of the transactions, the directions of cash flow (in or out) and the cross-border business strategy of the company would also be required** in order to construct concrete suggestions with more relevance to reality.
