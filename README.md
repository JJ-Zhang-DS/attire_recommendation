# Attire Recommendation

## Project Overview

This project involves building a recommendation system for attire using a provided dataset. The goal is to develop a recommendation system that suggests attire items to users based on their past interactions and item features. The recommendation system will help users discover new items that they might be interested in purchasing. This project is a collaboration with a Chinese e-commerce company.

## Dataset Description

The dataset includes information about users, items, and their interactions. Below is a description of the files and data fields included in the dataset.

### Files

- `train_users.csv`: Contains user IDs in the training dataset.
- `train_items.csv`: Contains item IDs in the training dataset.
- `train_interactions.csv`: Records of user purchases in the training dataset.
- `test_users.csv`: Contains user IDs in the testing dataset.
- `test_items.csv`: Contains item IDs in the testing dataset.
- `sample.csv`: A sample output format where 20 items are randomly selected for each user in the testing dataset.

### Data Fields

Below is a brief description of the data fields:

- `user_id`: Unique identifier for users.
- `item_ID`: Unique identifier for items.
- `item_name`: Name of the item, including basic information.
- `order_time`: Time when the user purchased the item.
- `brand`: Brand of the item.
- `channel`: Sales channel of the item.
- `unit_price`: Unit price of the item.
- `category`: Subcategory of the item.
- `size`: Size of the item.
- `color`: Color of the item.
- `discount`: Discount applied to the item.

## Usage

1. **Data Preparation**: Ensure all the CSV files are placed in the appropriate directory.
2. **Model Training**: Train the recommendation model using the training dataset.
3. **Generating Recommendations**: Use the trained model to generate recommendations for users in the testing dataset.
4. **Output**: The recommendations will be output in a format similar to `sample.csv`.

## Requirements

- Python 3.x
- LightFM
- NumPy
- Pandas

## Installation

Install the required packages using pip:

```sh
pip install lightfm numpy pandas