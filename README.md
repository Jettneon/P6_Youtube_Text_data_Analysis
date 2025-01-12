# YouTube Text Data Analysis Project

This project performs an exploratory data analysis (EDA) on a dataset containing information about YouTube videos, focusing on the video metadata such as title, views, likes, comments, and more. The goal is to understand trends in YouTube content and how various features like views, likes, and comments relate to each other.

## Task

1. **Set up the Environment**: Import necessary libraries such as pandas, matplotlib, and seaborn for analysis.
2. **Understand the Data**: Perform initial data exploration, such as inspecting columns, checking for missing values, and displaying basic statistics.
3. **Data Preprocessing**: Clean the dataset as required (e.g., handle missing values, check data types).
4. **Exploratory Data Analysis (EDA)**: Generate visualizations to explore relationships between features like views, likes, and comments.

## Data Columns

The dataset contains the following columns:

| Column Name              | Description |
| ------------------------ | ----------- |
| `video_id`               | Unique identifier for each video |
| `trending_date`          | Date when the video was trending |
| `title`                  | Title of the video |
| `channel_title`          | YouTube channel name |
| `category_id`            | Category ID of the video |
| `publish_time`           | Publish time of the video |
| `tags`                   | Tags associated with the video |
| `views`                  | Number of views the video received |
| `likes`                  | Number of likes the video received |
| `dislikes`               | Number of dislikes the video received |
| `comment_count`          | Number of comments on the video |
| `thumbnail_link`         | Link to the thumbnail image of the video |
| `comments_disabled`      | Boolean indicating if comments are disabled |
| `ratings_disabled`       | Boolean indicating if ratings are disabled |
| `video_error_or_removed` | Boolean indicating if the video has an error or was removed |
| `description`            | Description of the video content |

## Data Exploration

The dataset consists of **40,840 rows** and **16 columns**. We explore the dataset to better understand the distribution of views, likes, and other features, as well as identifying patterns in the data. Below are the key steps of the analysis:

1. **Initial Exploration**: Inspect the first few rows and column names.
2. **Data Types**: Check the data types of the columns and identify any issues like missing values.
3. **Missing Data**: Identify and handle missing values, especially in the description field.
4. **Descriptive Statistics**: Generate descriptive statistics such as mean, median, and standard deviation for numerical columns.
5. **Data Visualizations**: Create visualizations (e.g., histograms, scatter plots) to explore the relationships between video metrics like views, likes, and comments.

## Example Code

Below is a snippet of code for reading the dataset and performing basic data exploration:

## How to Use
To replicate the analysis or use the code for your own projects, follow these steps:
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/Analysis_of_Stock_Market.git

2. Install required libraries using pip.
   ```bash 
    pip install -r requirements.txt

3. Open the Jupyter notebook to begin the analysis.
   ```bash 
    jupyter notebook Analysis_of_Stock_Market.ipynb


## Technologies Used
- **Python**: The primary programming language used for data analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static visualizations like charts and graphs.
- **Seaborn**: For statistical data visualization based on Matplotlib.
- **Jupyter Notebook**: Interactive coding environment used for this analysis.

License
This project is licensed under the MIT License - see the LICENSE file for details.

