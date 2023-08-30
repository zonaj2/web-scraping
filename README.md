## Module 11 Challenge: Web Scraping
### Instructions
In this challenge I scraped titles and previewed text from Mars news articles. I used Beautiful Soup and Chrome dev tools to extract text elements from a website and store these elements in a Python dictionary.

I also scraped and analyzed Mars weather data from a HTML table. I used Pandas functions to analyze the dataset 
to determine the following :
- There are 12 months that exist on Mars.
- There are 1867 Martian days worth of data in the scraped dataset.
- The coldest month on Mars is in month **3** = -83.30. The warmest month on Mars is in month **8** = -68.38.
- Atmospheric pressure is, on average, lowest in the **6th** month and highest in the **9th**.
# 
### I plotted the the results for: ###
### Average Temperature by Month ###
![Average Temperature by Month](output/Temp%20by%20Month.png)

### Average Pressure by Month ###
<p>Pressure is sorted in ascending order.</p>

![Average Pressure by Month](output/Pressure%20by%20Month.png)

### Daily Temperature ###
By exploring the length of time between the peaks in the plot for daily temperature I
was able to estimate how may terrestrial days exist in a Martian year.
The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.

![Daily Minimum Temp](output/Daily%20Minimum%20Temp.png)





