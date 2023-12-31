# Analysing Booking Data for Splendor Hotel Groups
![pics](https://th.bing.com/th/id/R.f0f921b3cb56a111c5ff3c5a69140cde?rik=hHWeC9LTlSgcJQ&pid=ImgRaw&r=0)

The analysis of Splendor Hotel Groups' booking data uncovers pivotal insights that hold the potential to significantly enhance operational efficiency and elevate customer satisfaction. Recommendations are proposed to refine market strategies and optimize pricing models, thereby fostering overall performance.
Introduction 
In this comprehensive report, we delve into the intricacies of Splendor Hotel Groups' booking data, aiming to reveal trends, understand customer behaviour, and provide nuanced recommendations to drive informed decision-making

## Dataset Overview
The dataset is a rich repository of information, comprising 17 features and 119,390 entries. It encompasses a wide range of details, from booking dates to guest demographics and financial metrics. Rigorous data processing, including the handling of missing values and standardization, ensures the dataset's integrity and reliability.

<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/1_Dataview.PNG"/>
</p>
The null Data was removed from the analysis 
                                                   
![pics](https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/2_repolaceNull.PNG) | ![pics](https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/3_neatdata.PNG)

## Key Findings

1. **Trends in Booking Patterns**
An in-depth examination of booking patterns over time discloses that Fridays consistently record the highest number of bookings. This trend may be attributed to individuals planning events for Saturdays or choosing Fridays for weekend getaways. Remarkably, the first quarter demonstrates the highest booking and revenue figures, while the second quarter lags behind.

<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/4_SeasonalTrend.PNG"/>
</p>

**Recommendation**: Launching engaging activities can increase the sales in the second quarter, promotions during the first quarter can stimulate sales and capitalize on the peak booking period

2. **Lead Time Variation**
Lead time varies across distribution channels, with Travel Agents (Online and Offline) leading the pack, and Contract Customers exhibiting the highest average lead time.

<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/5_Leadtime.PNG"/>
</p>

**Recommendation**: Tailoring communication strategies to accommodate the longer planning horizons of Contract Customers and prioritizing service efficiency for Travel Agents can enhance overall customer satisfaction

3. **Distribution Channel Insights**
The distribution of bookings reveals that the Online Travel Agent (OTA) channel dominates with 62% of total bookings, accompanied by the highest average daily rate.

<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/6_numberofBooking.PNG"/>
</p>

**Recommendation**: Prioritizing the Online Travel Agent channel and considering a slight reduction in the average daily rate to $105 for online travel Agent can optimize revenue without compromising occupancy. 

4. **Country of Origin Analysis**
Booking and revenue trends vary by country, with Portugal recording the highest figures and the United Kingdom showcasing the highest average revenue per booking. Potential high cancellation rates from specific countries are identified.

 <p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/7_bookingandRevenue.PNG"/>
</p>
 
**Recommendation**: Implement strategies to mitigate cancellations from high-risk countries and explore targeted marketing initiatives to further boost bookings from lucrative regions(United Kingdom).

5. **Revenue Loss by Customer Segment**
Transient customers, while contributing significantly to bookings, also record the highest revenue loss.

 <p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/8_revenueloss.PNG"/>
</p>

**Recommendation**: Implement customer retention initiatives, such as loyalty programs or exclusive offers, to increase the lifetime value of Transient customers.

6. **Average Length of Stay**
Different customer types and distribution channels exhibit varying average lengths of stay. Contract customers have the highest average length (5 days), while the offline travel agent channel has a 4-day average stay.

 <p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/Average%20length%20of%20stay.PNG"/>
</p>
 
**Recommendation**: . Since the length of stay has a direct impact on the revenue gain, Utilize length-of-stay insights to strategically allocate rooms, optimizing revenue by prioritizing high-value customer segments

7. **Check-out, Arrival, and Cancellation Patterns**
Patterns in check-out, arrival, and cancellation suggest resource allocation challenges on Fridays, impacting revenue due to cancellations. Friday recorded the highest arrival of guest and also highest cancellation which is suggested to be as a result of limited allocation.

<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/11_checkoutPattern.PNG"/>
</p>

 
**Recommendation**: Consider expanding resources or implementing shared allocation strategies to accommodate the high demand on Fridays, minimizing revenue loss

9. **Lead Time and Cancellation Probability**
An indirect relationship between lead time, cancellation probability, and revenue is identified, with longer lead times associated with lower cancellation rates and constant profits.

<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/13_RevenuebyTimelead.PNG"/>
</p>
 
**Recommendation**: Tailor services to the preferences of high-lead time segments, such as Travel Agents, to maximize revenue and minimize cancellations.
<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/12_customerandDepositType.PNG"/>
</p>

10. **Booking and Cancellation by Customer segment and Deposit type**: There is a consistent booking using the No Deposit type across all customer segments with the transient customer having highest cancellation.

 <p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/13_RevenuebyTimelead.PNG"/>
</p>

# Conclusion
This analysis serves as a robust foundation for strategic decision-making, emphasizing the importance of targeted marketing, diversified channel management, and resource optimization. By implementing the outlined recommendations, Splendor Hotel Groups can navigate the dynamic hospitality landscape with precision and enhance its position in the industry


# Dashboard
[Interact with the dashboard](https://app.powerbi.com/links/8THF0SltMq?ctid=27777323-512a-4384-a252-e0f0e9033f1f&pbi_source=linkShare)

<p align="center">
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/dashboard1.PNG"/>
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/dashboard2.PNG"/>
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/dashboard3.PNG"/>
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/dashboard4.PNG"/>
  <img src="https://github.com/AbraxAnalyst/AnalysisOfSplendor_Hotel/blob/main/pics/dashboard5.PNG"/>
</p>







