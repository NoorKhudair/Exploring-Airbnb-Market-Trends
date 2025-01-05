# Exploring-Airbnb-Market-Trends
This project focuses on analyzing Airbnb listings in New York City, utilizing data from 2019. The project integrates data from multiple file formats (.csv, .tsv, and .xlsx) to gain insights into listing prices, room types, host details, and review timelines. By aggregating and processing these datasets, the goal is to uncover key trends in the Airbnb market, such as pricing patterns, room types, and review frequencies.

**data/airbnb_price.csv**
This is a CSV file containing data on Airbnb listing prices and locations.
- **`listing_id`**: unique identifier of listing
- **`price`**: nightly listing price in USD
- **`nbhood_full`**: name of borough and neighborhood where listing is located

**data/airbnb_room_type.xlsx**
This is an Excel file containing data on Airbnb listing descriptions and room types.
- **`listing_id`**: unique identifier of listing
- **`description`**: listing description
- **`room_type`**: Airbnb has three types of rooms: shared rooms, private rooms, and entire homes/apartments

**data/airbnb_last_review.tsv**
This is a TSV file containing data on Airbnb host names and review dates.
- **`listing_id`**: unique identifier of listing
- **`host_name`**: name of listing host
- **`last_review`**: date when the listing was last reviewed
