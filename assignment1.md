# Task 1: Observation and Data Collection Plan

## Observation

I was interested in how coffee shop activity changes depending on the coffee shop and time of day. I chose three coffee shops: Philz Coffee, Cafe 53, and Afro Joe's Coffee & Tea. I focused on observable characteristics of the spaces rather than collecting information about individual people.

One observation represents one visit to a coffee shop at a specific date and time. During each visit, I recorded the number of people present, the number of available seats, the number of people working or studying, and the number of people waiting in line.

## Initial Domain Questions

Before collecting my data, I was interested in the following questions:

1. How does the number of people in a coffee shop change throughout the day?
2. Which coffee shop tends to have the most people working or studying?
3. How does available seating vary with the number of people in the coffee shop?
4. How does the number of people waiting in line vary between coffee shops and times of day?

## Data Collection Process

I collected observations from three coffee shops: Philz Coffee, Cafe 53, and Afro Joe's Coffee & Tea. I collected observations across multiple dates and times of day to capture variation in coffee shop activity.

Each observation was recorded during a visit to one coffee shop. I recorded the coffee shop, date, time, number of people present, available seats, number of people working or studying, and number of people in line.

In total, I collected 27 observations, with 9 observations from each coffee shop. The observations covered early morning, morning, midday, afternoon, and evening periods.

I chose different times of day because coffee shop activity can change throughout the day. Collecting data at multiple locations and times allowed me to compare both differences between coffee shops and changes throughout the day.

## Limitations and Potential Biases

The data represents snapshots of each coffee shop rather than continuous observations throughout the day. The coffee shops were also observed on different dates, so differences between observations may be influenced by the specific day as well as the time.

The classification of whether someone was working or studying was based on observable behavior, so there may have been some uncertainty when making this distinction. Available seats may also be affected by the layout and size of each coffee shop, making direct comparisons more difficult.

I did not record other factors that could influence coffee shop activity, such as weather, special events, or the exact capacity of each location. These factors could be considered in a future collection.

## Data Dictionary

| Attribute | Type | Description | Example |
|---|---|---|---|
| `coffee_shop` | Categorical | Coffee shop where the observation was collected | Philz Coffee |
| `date` | Temporal | Date of the observation | 9/18/2026 |
| `time` | Temporal | Time when the observation was collected | 10:00 AM |
| `people_counted` | Quantitative | Number of people observed inside the coffee shop | 16 |
| `available_seats` | Quantitative | Number of visibly unoccupied seats | 2 |
| `working_studying` | Quantitative | Number of people visibly working or studying | 11 |
| `people_in_line` | Quantitative | Number of people waiting in the ordering line | 3 |






# Task 2: Pilot and Data Collection

Before collecting the full dataset, I used my first 10 observations as a pilot to test whether my collection procedure and attributes were practical to record consistently. The pilot included observations from Philz Coffee, Cafe 53, and Afro Joe's Coffee & Tea at different times of day.

The pilot showed that the attributes were generally straightforward to record. Counting the total number of people, available seats, and people in line could be done during a short observation. I also found that the number of people working or studying required more judgment because it was 
not always possible to know exactly what someone was doing. I therefore treated this attribute as an estimate based on observable behavior, such as someone using a laptop, notebook, or other study/work materials.

The pilot also showed that recording the exact date and time was important because coffee shop activity varied considerably throughout the day. I kept the same attributes for the remainder of the collection so that observations from different coffee shops and dates could be compared consistently.

After the pilot, I continued using the same collection procedure and collected a total of 27 observations. The final dataset contains 9 observations from each of the three coffee shops: Philz Coffee, Cafe 53, and Afro Joe's Coffee & Tea. 
Observations were collected at different times ranging from early morning to evening in order to capture variation in activity.

One limitation of the collection process was that the observations were snapshots rather than continuous measurements. The number of people and available seats could change shortly before or after an observation was recorded. 
Additionally, determining whether someone was working or studying involved some subjective judgment. Despite these limitations, keeping the same attributes and observation procedure throughout the collection made the observations more consistent and comparable.






# Task 3: Final Dataset and Reflection

## Final Dataset

My final dataset contains 27 observations collected from three coffee shops: Philz Coffee, Cafe 53, and Afro Joe's Coffee & Tea. Each coffee shop has 9 observations. Each observation represents one visit to a coffee shop at a specific date and time.

The dataset contains 7 attributes:

- Coffee shop
- Date
- Time
- People counted
- Available seats
- People working or studying
- People in line

The observations were collected across multiple dates from September 18, 2026 to October 2, 2026. The times range from 6:00 AM to 7:00 PM, providing observations from early morning, morning, late morning, afternoon, and evening.

## Variation in the Data

There was noticeable variation in the number of people observed across the coffee shops and times of day. The number of people counted ranged from 2 to 17. Available seats ranged from 2 to 16. The number of people working or studying ranged from 0 to 11, while the number of people in line ranged from 0 to 12.

The data also contains variation between coffee shops. For example, Cafe 53 generally had fewer people during some of the early morning and afternoon observations, while Philz Coffee and Afro Joe's Coffee & Tea had several observations with higher numbers of people. The number of people working or studying also changed depending on the coffee shop and time of day.

Because I collected observations at different times and on different dates, the dataset allows me to compare coffee shop activity across both location and time. However, the number of observations at each specific time is limited, so the data should not be treated as a complete representation of each coffee shop's typical activity.

## Limitations and Biases

One limitation is that each observation is a snapshot of the coffee shop at one specific moment. The number of people, available seats, and people in line could change shortly before or after I recorded the observation.

Another limitation is that the coffee shops were not observed on exactly the same dates. This means that differences between coffee shops could be influenced by the specific date in addition to the time of day.

The classification of people as working or studying was also based on observable behavior. Someone using a laptop, notebook, or other materials could reasonably appear to be working or studying, but I could not always know their actual purpose.

Available seating is another limitation because coffee shops have different layouts and capacities. A shop with more available seats does not necessarily have less activity than a smaller shop.

I also did not collect information about factors such as weather, special events, or the total seating capacity of each location. These factors could have affected the observations.

## Reflection on the Data

The collection process captured differences in coffee shop activity across locations and times of day. It was particularly useful for recording quantitative characteristics that could be compared across observations, such as the number of people, available seats, and people in line.

However, the dataset does not capture why the coffee shops were busier or quieter. For example, I can observe that one coffee shop had more people at a certain time, but I cannot determine whether this was caused by the time of day, the date, weather, an event, or another factor that I did not record.

The data also captures the overall number of people rather than detailed information about individual visitors. This was intentional because I wanted to focus on the activity and characteristics of the coffee shop spaces rather than collecting personal information about customers.

## Revisiting My Domain Questions

### 1. How does the number of people in a coffee shop change throughout the day?

The dataset can help answer this question because I collected observations at different times of day. There are examples of lower and higher numbers of people at different times. However, because I did not collect every time period on every date, the results show patterns in my observations rather than a complete daily pattern.

### 2. Which coffee shop tends to have the most people working or studying?

The dataset can support a comparison of the three coffee shops because I recorded the number of people working or studying during every observation. However, the results should be interpreted carefully because the observations were collected on different dates and at different times.

### 3. How does available seating vary with the number of people in the coffee shop?

The dataset provides both the number of people counted and the number of available seats, so these variables can be compared directly. This question is one of the stronger questions supported by the dataset because both measurements were collected during every observation.

### 4. How does the number of people waiting in line vary between coffee shops and times of day?

The dataset can also support this question because I recorded the number of people in line for every observation. There is variation in line size across both coffee shops and times, although a larger dataset collected at more consistent times would provide stronger evidence of overall patterns.

Overall, the final dataset provides enough variation to explore differences between coffee shops and times of day, while the limitations mean that the results should be treated as observations of the sampled visits rather than generalizations about all coffee shop activity.






# Task 4: Abstract Tasks

For each domain question, I identified the main action I want a viewer to perform and the target of that action.

## Question 1: How does the number of people in a coffee shop change throughout the day?

**Action:** Compare and identify trends

**Target:** Number of people in the coffee shop across different times of day

The viewer should be able to compare the number of people at different times and identify whether coffee shop activity increases or decreases throughout the day.

## Question 2: Which coffee shop tends to have the most people working or studying?

**Action:** Compare and rank

**Target:** Number of people working or studying across coffee shops

The viewer should be able to compare the coffee shops and determine which locations tend to have more people working or studying.

## Question 3: How does available seating vary with the number of people in the coffee shop?

**Action:** Compare and identify relationships

**Target:** Available seats and number of people in the coffee shop

The viewer should be able to compare these two quantities and identify whether having more people in the coffee shop is associated with fewer available seats.

## Question 4: How does the number of people waiting in line vary between coffee shops and times of day?

**Action:** Compare and identify patterns

**Target:** Number of people in line across coffee shops and times of day

The viewer should be able to compare line sizes between coffee shops and determine whether there are noticeable patterns at different times of day.

## Summary of Abstract Tasks

| Domain Question | Action | Target |
|---|---|---|
| How does the number of people change throughout the day? | Compare and identify trends | People counted across times of day |
| Which coffee shop has the most people working or studying? | Compare and rank | People working/studying across coffee shops |
| How does available seating vary with the number of people? | Compare and identify relationships | Available seats and people counted |
| How does the number of people in line vary? | Compare and identify patterns | People in line across coffee shops and times |







# Task 5: Visualization Sketches

Based on my domain questions and abstract tasks, I created three substantially different visualization designs. Each design uses different visual encodings to represent the coffee shop data.

## Sketch 1: Line Chart

### Description

My first design uses a line chart to show how the number of people in each coffee shop changes throughout the day.

- **X-axis:** Time of day
- **Y-axis:** Number of people counted
- **Lines:** Coffee shops
- **Position:** Represents the number of people
- **Color/line style:** Distinguishes the three coffee shops

### Strengths

This design makes it easy to see changes in activity throughout the day. The lines allow the viewer to identify increases, decreases, and differences between coffee shops.

### Weaknesses

There are relatively few observations at each time, and the observations were collected on different dates. Connecting the points with lines could make the data appear more continuous than it actually is.

---

## Sketch 2: Grouped Bar Chart

### Description

My second design uses grouped bars to compare coffee shop activity at different times of day.

- **X-axis:** Time of day
- **Y-axis:** Number of people
- **Bars:** Individual observations
- **Color:** Coffee shop
- **Height:** Number of people counted

The observations are grouped by time so that the coffee shops can be compared within the same general time period.

### Strengths

This design makes direct comparisons between coffee shops easy. The height of each bar provides a straightforward representation of the number of people.

### Weaknesses

The chart could become crowded because there are 27 observations. It may also be difficult to distinguish differences caused by the date from differences caused by the time of day.

## Comparison of Initial Sketches

| Sketch | Main Question | Main Encoding | Strength | Weakness |
|---|---|---|---|---|
| Line Chart | How does activity change throughout the day? | Position and line | Shows trends over time | Lines may imply continuous data |
| Grouped Bar Chart | How do coffee shops compare? | Bar height | Easy comparisons | Can become crowded |

I chose these two designs because they provide different ways of viewing the dataset. The line chart focuses on changes over time, while the grouped bar chart focuses on direct comparisons between coffee shops.







# Task 6: Visualization Design Comparison

## Comparing the Two Designs

The two visualization designs approach the coffee shop data differently. The line chart focuses on changes in activity throughout the day, while the grouped bar chart focuses more on direct comparisons between coffee shops.

### Line Chart

The line chart is useful for showing how the number of people changes throughout the day. The position of each point makes it easy to see increases and decreases in activity. Using separate lines for each coffee shop also makes it possible to compare the general patterns between locations.

One weakness is that connecting observations with lines may suggest that the data was collected continuously, even though each observation is a separate snapshot. The different collection dates also make the trends less direct.

### Grouped Bar Chart

The grouped bar chart makes it easier to compare the number of people between coffee shops at different times. The height of each bar provides a straightforward way to compare values.

However, the bar chart can become crowded because there are 27 observations. It may also be harder to see an overall trend across the entire day compared with the line chart.

## Design Comparison

| Criteria | Line Chart | Grouped Bar Chart |
|---|---|---|
| Readability | Easy to follow overall trends | Easy to compare individual values |
| Comparison | Good for comparing changes over time | Good for comparing coffee shops |
| Complexity | Relatively simple | Can become crowded |
| Expressiveness | Shows trends and changes well | Shows individual differences well |
| Scalability | More difficult with many coffee shops | More difficult with many observations |
| Originality | Uses a familiar visualization | Uses a familiar visualization |

## Final Design Choice

If I were to develop one of these designs further, I would choose the line chart. My main interest is understanding how coffee shop activity changes throughout the day, and the line chart communicates changes over time more clearly.

The grouped bar chart is useful for comparing individual observations, but it becomes more difficult to read as more observations are added. The line chart provides a clearer overall view of the patterns in the data.

## Process Reflection

Creating the two sketches helped me think about the difference between the questions I wanted to answer and the way the data should be represented. I initially focused on the data itself, but sketching the visualizations made it clearer that different designs emphasize different aspects of the same dataset.

The process also showed me that a visualization can make some patterns easier to see while making other information less noticeable. The line chart emphasizes trends over time, while the grouped bar chart emphasizes individual comparisons. This helped me understand why choosing an appropriate visual encoding is important when designing a visualization.







# Task 7: Collaboration and Process

Because I completed this assignment individually, I was responsible for all parts of the process. This included choosing the topic, developing the domain questions, collecting and organizing the observations, analyzing the dataset, creating the abstract tasks, and developing the visualization sketches.

## Workflow

I first chose coffee shops as my observation setting because they provided a simple way to observe activity across different locations and times. I then developed questions about the number of people, available seating, people working or studying, and people waiting in line.

After deciding what information to collect, I created a consistent set of attributes and used the same general observation process for each coffee shop. I organized the observations into a table so that each row represented one observation and each column represented an attribute.

After collecting the data, I reviewed the dataset to identify variation, limitations, and patterns that could support my original questions. I then converted the domain questions into abstract tasks based on the actions I wanted viewers to perform.

Finally, I created visualization sketches based on those tasks. I explored a line chart and a grouped bar chart because they emphasize different aspects of the data. The line chart focuses on changes over time, while the grouped bar chart focuses on comparisons between coffee shops.

## Organization and Documentation

I kept the dataset organized in a structured table with consistent attribute names and values. I also separated the dataset from the written assignment and visualization sketches so that each part of the project could be updated independently.

The GitHub repository contains the assignment document, dataset, and visualization sketches. I used GitHub to keep the different parts of the project organized and to document the development of the assignment over time.

## Reflection

Working individually gave me control over the entire process, but it also meant that I was responsible for making all of the decisions myself. I had to decide what information was useful to collect, how to organize it, and which visualization designs best matched my questions.

The process helped me understand that visualization design starts before creating a chart. The questions I asked influenced what data I collected, and the data I collected influenced which visualizations were useful. Creating sketches also helped me see the strengths and weaknesses of different ways of representing the same dataset.
