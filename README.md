# amazon_vine_analysis
## Overview  
The Amazon Vine program is a service that allows for product manufacturers to receive a review for products sold online. Companies provide products to Amazon Vine members who are then required to publish a review. Given a large dataset of reviews for the category of major household appliances, the purpose here is to extract the reviews from both paid Vine members and those who are not participants in the Vine program to determine whether being a part of the Vine program influences the proportion of five-star product reviews.  

## Results  
After filtering the dataset to only include products with greater than 50 percent of votes qualifying as 'helpful' and splitting the dataset into Vine and non-Vine users, the following results and datasets were obtained:  

Dataset samples:  
![vine](https://user-images.githubusercontent.com/60231630/150667735-43239bc2-28eb-430c-bba0-76b8ac696964.png)  

![non_vine](https://user-images.githubusercontent.com/60231630/150667747-4a64fcde-5733-491f-bdcc-70d64eb91e40.png)  



*  A total of 29742 reviews were obtained for non-Vine reviewers and 210 reviews were obtained for Vine reviewers  
*  A total of 1963 reviews were 5-stars for the non-Vine reviewers and 18 reviews were 5-stars for the Vine reviewers  
*  This corresponds to 6.6 percent of reviews being 5-stars for non-Vine reviewers and 8.6 percent of reviews being 5-star for Vine reviewers  

##  Summary  
A cursory look at the proportion of 5-star reviews between Vine and non-Vine reviews would suggest that there is not a bias toward 5-star reviews for reviewers participating in the Vine program as the proportions are similar, albeit more reviewers are present for the non-Vine reviews. To better support this analysis a statistical test of independence for the proportion of 5-star reviews for Vine and non-Vine variables would be of use here. 
