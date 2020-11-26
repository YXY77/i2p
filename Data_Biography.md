# Data Biography

## Student Number: 20058393

---

### 1. Who collected the data?

Airbnb operators and managers (data analysts), or landlords who want to rent out their houses through the platform.

---

### 2. Why did they collect it?

Analyze the supply and demand of Airbnb housing in London, and explore what types of houses are more popular and can generate more revenue. Hence, the data should include the distribution and the price of the housing, the number of days rented in a certain period, the landlord’s income, etc.

---

### 3. How was it collected?

Inside Airbnb site uses crawling algorithms to obtain the list information from the public information on the Airbnb web[1]. After analysis, collation and aggregation, these data can be used for public analysis and discussion.

The listing data can be roughly divided into three parts: 1. Housing information 2. Landlord information 3. Rental information. Analyzing data helps to understand the situation of the London rental market.

---

### 4. What useful information does it contain?

*id, neighborhood_overview, host_id, host_response_time, host_response_rate, host_acceptance_rate, host_is_superhost, host_identity_verified, neighbourhood, neighbourhood_cleansed, latitude, longitude, property_type, room_type, accommodates, bathrooms_text, bedrooms, beds, amenities, price, minimum_nights, maximum_nights, minimum_minimum_nights, maximum_minimum_nights, minimum_maximum_nights, maximum_maximum_nights, minimum_nights_avg_ntm, maximum_nights_avg_ntm, has_availability, availability_30, availability_60, availability_90, availability_365, number_of_reviews, number_of_reviews_ltm, number_of_reviews_l30d, last_review, review_scores_accuracy, review_scores_cleanliness, review_scores_checkin, review_scores_communication, review_scores_location, review_scores_value, instant_bookable, calculated_host_listings_count, calculated_host_listings_count_entire_homes, calculated_host_listings_count_private_rooms, calculated_host_listings_count_shared_rooms, reviews_per_month.*

The information listed above includes a description of the basic situation of the house, personal information about the landlord, and statistics of some data on the rental situation of the house, which may be related to simple or complex research to be analysed.

---

### 5. What useful information is it missing?

There are four columns (*neighbourhood_group_cleansed, bathrooms*, *calendar_updated* and *license*) of fields that are totally empty, which may be due to structurally missing during the data collection process. And part of the information in the remaining columns (*neighborhood_overview*, *host_response_time*, etc.) is also empty, which seems to be randomly missing in the collected data.

---

### 6. To what extent is the data 'complete'?

It can be considered that the data is basically complete. Although some data are structurally missing, it seems that *neighbourhood_group_cleansed* and *bathrooms* are related to their adjacent data, namely *neighbourhood_cleansed* and *bathrooms_text*. And they can reflect similar results to some extent, therefore the lack of data will not have a serious impact on the final analysis, and these missing data can be cleared.

The randomly missing data in other columns may be in line with the real situation in the data collection process，the data itself does not exist or has not been captured. As for the properties of houses that are not in the list, such as the traffic and markets around the house and the square meter of the house may not be completely necessary for the problem of target analysis.

---

### 7. What kinds of analysis would this support?

We can analyse the leasing situation of Airbnb houses in London, and investigate which areas and characteristics of houses are most popular with tenants，this allows landlords to renovate their houses based on the results of the analysis to make them more matching with consumer preferences and improve the possibility of renting out. It can also give some suggestions to new landlords who plan to join, help them decide what kind of house to rent on the platform will be more competitive in the market.

Or discuss which hosts’ houses are most effective for renting through the Airbnb platform, and what are the specifics of these hosts and the houses they own. This information may be of more reference value for other landlords who want to increase their performance, especially new landlords.

---

### 8. What kinds of analysis would it _not_ support?

The landlord’s response data, for instance, *host_response_time*, *host_response_rate* and *host_acceptance_rate*, has some missing data, thus it is not conducive to studying the impact of the landlord’s response on the rental situation. In other words, when studying the impact of certain specific factors on house rental, if there are missing data, this type of analysis cannot be supported.

Besides, the data did not capture the "number of rented out", and this data was originally a key factor in judging the housing rental situation, and can only be replaced by the "number of house reviews" in the existing data. However, the two data cannot be entirely equivalent, because there may be cases where some users rented a house but did not commit the review, so the result of the analysis may not be fully representative.

---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

The data showing the basic conditions of the house and the data from the house review feedback are exploited to analyse what kind of house is more competitive in the market. Trace back the personal introductions and response rates of the landlords of these houses, and observe whether there are some common features. If so, they can be attributed to the reasons why the houses are easily selected by customers. The above uses are ethical, and the scientific analysis results will also benefit the interest relationship among Airbnb, the landlord, and the tenant.

Nevertheless, some data in the listing is relatively private, including the location of the landlord, associated with the landlord’s personal privacy, and the total number of houses the landlord owned, which leaks the landlord’s property privacy. And these data are placed on a public website, as open data can be crawled and processed illimitably. In the context of big data, it is not difficult to get some exact data and process it. In this way, data aggregation makes data management more challenging [2], which will increase security risks.

Furthermore, the landlord’s picture, whether the landlord is a super landlord, these data may trigger discrimination in terms of gender, race, age, etc. This is alleged data discrimination or data inequality [3], which will not be contributing to the healthy development of the market. 

Obviously, the use of personal data covers ethical issues, and it is crucial to balance the relationship between data security and privacy protection [4]. Then in the education of spatial data analysis, guidance on thinking about ethical issues will be extremely meaningful [5].

---

---
### References

[1]    K. Barron, E. Kung, and D. Proserpio, “The Sharing Economy and Housing Affordability: Evidence from Airbnb,” SSRN Electron. J., 2018, doi: 10.2139/ssrn.3006832.


[2]	   K. Crawford and M. Finn, “The limits of crisis data: analytical and ethical challenges of using social and mobile data to understand disasters,” GeoJournal, vol. 80, no.        4, 2015, doi: 10.1007/s10708-014-9597-z.


[3]	   S. Elwood and A. Leszczynski, “Feminist digital geographies,” Gender, Place Cult., vol. 25, no. 5, 2018, doi: 10.1080/0966369X.2018.1465396.


[4]	   V. van den Bemt, J. Doornbos, L. Meijering, M. Plegt, and N. Theunissen, “Teaching ethics when working with geocoded data: a novel experiential learning approach,” J.            Geogr. High. Educ., vol. 42, no. 2, 2018, doi: 10.1080/03098265.2018.1436534.


[5]    S. Elwood and M. Wilson, “Critical GIS pedagogies beyond ‘Week 10: Ethics,’” Int. J. Geogr. Inf. Sci., vol. 31, no. 10, 2017, doi: 10.1080/13658816.2017.1334892.

