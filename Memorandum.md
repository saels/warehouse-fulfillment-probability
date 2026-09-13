**To: Management**

**From: Santiago Leyva, Lead Data Scientist**

**Date: March 9, 2026**

**Subject: Inventory analysis for weekend sales**

I’m writing to inform you about the inventory analysis for the weekend sales. This analysis includes the actual inventory analysis and the needed inventory to satisfy our customer, considering that this weekend will be especially busy and our stores need to have enough inventory.

With the objective of providing more insights, first the parameters must be obtained according to our data. According to it, the demand of the customers can be modelled through a normal distribution with mean of 800 and standard deviation of 250 for each of our stores. The data also shows that the warehouse has 9500 units to provide to our stores.

To have the mean and standard deviations, the calculations were done, providing a mean of 9600 and a standard deviation of 25012, approximately 866.0254. With that data, the calculations were done, obtaining the fill rate guaranteed by our current units. With 9500 units, the fill rate is 45.404%. That means that we have less than 50% probability to satisfy all our customers this weekend.

As the weekend is expected to be a busy one, the calculations were done to have a fill rate of 85%, 95% and 99% to have more insights. The results were that we need 10498, 11025 and 11615 in available inventory respectively to satisfy the demand. As it can be seen, our current inventory doesn’t reach these numbers by 998, 1525 and 2115 units respectively.

As we have a limited budget and the weekend is near, it is recommended that our warehouse get at least 1525 units extra. This will provide a 95% probability that all our customers will be satisfied. There will be a 5% risk that some customers will not be able to acquire our product, then, if the management department wants to reduce this risk, more products could be purchased. Every extra unit apart from the 1525 stated, will reduce this risk.

Thank you for taking the time to review this analysis. Please feel free to send any questions or concerns you have to me.

Graphics for the analysis:

Red -> actual limit for fill rate

Gold -> limit for fill rate of 85%

Orange -> limit for fill rate of 95%

Green -> limit for fill rate of 99%

<img width="715" height="455" alt="image" src="https://github.com/user-attachments/assets/6ee810f7-8e87-4950-a92f-14fe840a57e8" />

<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/3032a24e-37c2-4b32-b328-b03b988e2647" />
