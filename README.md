# Amazon-ML-Challenge-2024



**Problem Statement:**

Feature Extraction from Images

In this hackathon, the goal is to create a machine learning model that extracts entity values from images. This capability is crucial in fields like healthcare, e-commerce, and content moderation, where precise product information is vital. As digital marketplaces expand, many products lack detailed textual descriptions, making it essential to obtain key details directly from images. These images provide important information such as weight, volume, voltage, wattage, dimensions, and many more, which are critical for digital stores.

**Dataset:**

The dataset is divided into two main files:

train.csv: Contains over 310,000 image links along with metadata.

test.csv: Contains over 130,000 image links along with metadata.

Each dataset has the following columns:

index: An unique identifier (ID) for the data sample

image_link: Public URL where the product image is available for download. Example link - https://m.media-amazon.com/images/I/71XfHPR36-L.jpg

group_id: Category code of the product

entity_name: Product entity name. For eg: “item_weight”

entity_value: Product entity value. For eg: “34 gram” Note: For test.csv, you will not see the column entity_value as it is the target variable.

**Results:**

Our model achieved the following results:

F1 Score: 0.5079737062482348

Rank: 132 out of 2500+ registered teams
