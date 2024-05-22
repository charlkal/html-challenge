
## Data Sources
The source of the data for this project includes:

Mars News Website: The data for scraping titles and preview text from Mars news articles is sourced from the <a href="https://mars.nasa.gov/news/">Mars NASA news website</a>.

Mars Temperature Data Site: The data for scraping and analyzing Mars weather data is sourced from the <a href="https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html">Mars Temperature Data website</a>

## resources
    Stack overflow, LAs, chatGPT


## Actions
For this project, the first step involved scraping data from the Mars Temperature Data Site. To achieve this, I utilized Splinter for automated browsing to visit the website and BeautifulSoup to extract data from the HTML table. After obtaining the data, I assembled it into a Pandas DataFrame, ensuring appropriate column names were used.

With the data prepared, I proceeded to analyze various aspects of Martian weather patterns. This included determining the number of months present on Mars, calculating the Martian days' worth of data available in the dataset and analyzing the temperature & atmospheric pressure data.

To better understand the relationship between terrestrial days and Martian years, I visualized the data by plotting bar charts for average temperatures and atmospheric pressure by month. Finally, I estimated the duration of a Martian year based on temperature fluctuations, revealing insights into the Martian calendar and its alignment with Earth time units.

## Results 

The coldest month on Mars, on average, is the third month, while the warmest is the eighth month. Additionally, atmospheric pressure was found to be lowest in the sixth month and highest in the ninth month. Based on the changes in temperature over time, a Martian year is estimated to be around 675 terrestrial days. These findings improve our understanding of the environmental conditions of Mars. 