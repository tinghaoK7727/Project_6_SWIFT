# Project_6_SWIFT

**Project Goal:**
- Based on the assigned data to create a Dashboard using Tableau to deliver insight and directions of improvements. Combined with other businees focused insights, this Dashboard can serve as a reference tool when making decisions in cross-border transactions and potential market expansions.

**Dataset**
- A set of transaction details in excel of company Alpha Inc delivered with the service of Paylocator.

**Data Exploration and Processing**
- As there's no unique ID in the original data, actions on matching a few column information to create an identifier with different status indicators were needed. Also, in order to explore as much information as possible, new columns such as Bank Name and Country were also added.

**Charts included in the Dashboard:**

1. First we have a **pie chart** showing the distirubution of all transaction status, this is to have an idea of the percentage of completed transactions versus ongoing or pending ones.

2. The second piece of information is the **average Time needed for each transaction**. We did the calculation based on the time difference of the same transaction at status NEW and status COMPLETED.

3. Then we did a **line chart** to show the fluctuations of Total Charges (Initial Amount * Charges %) over the months. An reference **average line** has also been set to visually spot the months where the charges are higher or lower.

4. Our fourth chart is a **line chart** of the Initial Amount by month + a **forecast** for following months. In order to have a smooth line, we put 0 for the months with missing data. **Depending on the directions of the cashflow** (either in or out), we can gain some insight on our business reality as well.
