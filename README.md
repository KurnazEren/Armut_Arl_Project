# Armut_Arl_Project

**Business Problem**

Armut, Turkey's largest online service platform, brings together service providers and those who want to receive service. It provides easy access to services such as cleaning, modification and transportation with a few touches on your computer or smart phone. It is desired to create a product recommendation system with Association Rule Learning by using the data set containing the service users and the services and categories these users have received.

**Data Set**

The data set consists of the services customers receive and the categories of these services. It contains the date and time information of each service received.

* UserId: Customer number
* ServiceId: Anonymized services belonging to each category. (Example: Upholstery washing service under the cleaning category)A ServiceId can be found under different categories and refers to different services under different categories. (Example: The service with CategoryId 7 and ServiceId 4 is honeycomb cleaning, while the service with CategoryId 2 and ServiceId 4 is furniture assembly)
* CategoryId: Anonymized categories. (Example: Cleaning, transportation, renovation category)
* CreateDate: The date the service was purchased
