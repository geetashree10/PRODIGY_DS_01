# PRODIGY_DS_01

In this analysis, we used R programming to visualize the Australia total population data from a CSV file. 
By employing the `readr` and `ggplot2` libraries, we created either a bar graph or histogram showcasing the distribution of population over time, 
providing a clear and insightful representation of demographic trends.

```
library(readr)
library(tidyverse)

library(ggplot2)
# Read the CSV file
australia_data <- read_csv("C:/Users/geeta/AppData/Roaming/Microsoft/Windows/Network Shortcuts/Australia.csv")

#creating a bar graph
ggplot(data = australia_data, aes(x = Year, y = `Australia Total Population`)) +
  geom_bar(stat = "identity", fill = "skyblue") +
  labs(title = "Australia Total Population",
       x = "Year",
       y = "Total Population")
```
![image](https://github.com/geetashree10/PRODIGY_DS_01/assets/158750505/a1634149-c4db-4662-87ba-7f077290bbca)



