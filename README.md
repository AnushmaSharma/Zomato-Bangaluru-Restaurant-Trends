# Zomato-Bangaluru-Restaurant-Trends
# BACKGROUND:
The Zomato Bangalore Restaurants dataset captures Bengaluru's diverse and expanding food scene, featuring around 12,000 restaurants offering cuisines worldwide. This data provides key insights into restaurant types, locations, cuisines, pricing, and customer ratings, helping new entrants understand local demographics and dining preferences. Amid growing demand from the city’s busy population, new restaurants face challenges from established competitors and rising costs. This dataset enables an analysis of popular cuisines, neighbourhood food trends, and consumer preferences to support better business decisions in Bengaluru's restaurant industry.

# DATA SOURCE:
The data in this project comes from one primary source: the Zomato Bangalore Restaurants dataset on Kaggle. This dataset contains detailed information about approximately 12,000 restaurants in Bengaluru, covering geographic variables like location and neighbourhood, continuous variables such as average cost and ratings, and categorical variables including cuisine type, restaurant type, and popular dishes. The data was scraped in two phases: first capturing basic details like URLs and addresses, and then gathering more specific information, such as customer reviews, pricing, and restaurant features. With over 15 variables, this dataset offers a comprehensive view of Bengaluru’s diverse dining scene, making it highly relevant for analyzing customer preferences, food trends, and neighbourhood dining patterns.

# DATA COLLECTION PROCESS:
The Zomato data was gathered in two phases. During initial exploration of the website structure, it was observed that each neighbourhood had around 6-7 restaurant categories, including Buffet, Cafes, Delivery, Desserts, Dine-out, Drinks & nightlife, and Pubs & bars.

Phase I: In the first phase, only basic information such as URL, name, and address of each restaurant was collected, which was visible on the main page. URLs for individual restaurants were stored in a CSV file to facilitate the later extraction of additional data for each restaurant. This approach minimized the load on the system and streamlined the data extraction process. The information for each neighbourhood and category is available here.

Phase II: In the second phase, detailed information was retrieved for each restaurant and category through individual data scraping. This included 15 variables, covering attributes like online ordering, table booking options, rating, votes, phone number, location, restaurant type, popular dishes, cuisines, approximate cost for two people, review lists, and menu items. 

# WHY I HAVE CHOSEN THIS DATASET:
I have chosen this dataset because, as a foodie, I love exploring different cuisines and dining options. Before moving to Canada, I lived in Bangalore, where I often ordered food through Zomato. This experience connected me to the city's vibrant restaurant culture, making this dataset especially interesting to analyze. The data provides a rich view of Bangalore’s dining landscape, allowing me to explore patterns in customer preferences, cuisine types, and neighbourhood trends, which resonate with my own experiences in the city.

# DATA LIMITATIONS
Sampling Bias: The data was sourced only from Zomato listings, which may not represent the full range of restaurants in Bangalore, especially smaller or unlisted establishments.

Incomplete Data: Some columns had missing values which required imputation or standardization, potentially introducing inaccuracies.

Data Freshness: Since the data is static and pulled at one point in time, it may not reflect recent changes, such as new restaurants, closures, or updates in menu offerings and prices.

Ambiguities in Variables: Categories like "Approx Cost" might lack precision, as they could vary widely depending on the specific context or time of visit (e.g., weekend vs. weekday pricing).

Data Quality: Data inconsistencies, such as invalid characters in phone numbers, required cleaning, but some noise or minor errors may persist.

# DATA ETHICS
Data Privacy: Although no personal information about customers is included, any identifiable information (e.g., specific phone numbers or restaurant addresses) should be handled with care to prevent misuse.

Data Source Ethics: The data was scraped from Zomato, and it's essential to consider the platform's terms of service. Unauthorized data scraping may violate policies, so it's necessary to review and ensure compliance with the data source’s guidelines.

Bias and Fairness: Using data from a single source may unintentionally amplify biases inherent to that platform. For instance, Zomato listings may overrepresent certain types of restaurants (e.g., high-end dining) and underrepresent smaller or minority-owned businesses.

Transparency: When using or sharing this data, it's important to disclose how it was collected, any limitations, and potential biases to avoid misleading interpretations.

TABLEAU LINK: https://public.tableau.com/app/profile/anushma.sharma/viz/AnushmaSharma_ZomatoBengaluruRestaurants/ZomatoBengaluruRestaurants?publish=yes

