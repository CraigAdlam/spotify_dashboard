## Spotify Dashboard - Reflection

### Usability

- Based on the feedback received, the dashboard is very easy to use and navigate from tab to tab
- Some users overlooked some features and requested more clarity, guided steps were added in the headers to clarify what can be done

### Reoccurring Themes

- Large dataset and multiple filters resulted in slower load times, however, preprocessed data was utilized and partitioned data to improve speed of navigation
- Keeping the format consistent with the headers, Spotify colours, and spacing/layout to be visually aesthetic

### Valuable Insights

- One user requested to have a link beside each top song so that they could sample the specific song - implemented in tab 2
- Also requested to have the pictures of the top 3 artist in the world displayed depending what was selected - implemented in tab 3



### Tab 1 – Discover Music Taste

**What has been done:**

- Genres, artists, track names, filters
- Statistics table of music, including min, mean, and max, are shown in the table based on the filtering
- Genre proportion based on the filtering
- Radar chart of scaled values based on the filtering
- If the filters are not selected, the values of the table and charts will be calculated based on all data

**Limitations:**

- Slow loading (track names list of the filter contains about 80,000)

**What needs to be improved:**
- Remove data/make the dataset callable when needed (stored variable)
- Make search area smaller/equal to the chart area beside
- Use Card element header instead of paragraph



### Tab 2 – Find New One?

**What has been done:**

- Created sliders for each music feature on the left pane which interacts with the plots on the right pane (Feature Bar Plot, Feature Bar Plot, and the Song Table)
- When the sliders are used to select feature ranges, Feature Bar Plot will be updated with the average musical feature proportions, showing the trends
- When the sliders are used to select feature ranges, Feature Bar Plot will be updated to reflect the musical features showing fine-tuned visualizations
- When the sliders are used to select feature ranges, Song Table gets updated with the top 10 songs based on the feature ranges selected

**What needs to be improved:**

- Rename ambiguous table columns
- Add mark ticks/slider position
- Potential rearranging of the plot positions for maximum impact
- Change background colors/Card colors to match the Spotify green theme
- Add a checkbox to implement selecting rows based on popularity



### Tab 3 – Explore Globally

#### **What has been done:**

##### Improvements from Milestone 2
- Change background colors/Card colors to match the Spotify green theme (COMPLETED IN MILESTONE 4)
- Add second index to slider (so there are 2) so a range of popularity can be selected (COMPLETED IN MILESTONE 4)
- Limit table to popularity or include 3/4 metrics (mainly covered in first 2 tabs) (COMPLETED IN MILESTONE 4)

##### Improvements from Milestone 3
- CHANGED 2 horizontal bar charts that display the top 10 songs and artist globally to SINGLE PIE CHART AND PICTURES OF TOP 3 ARTISTS
- MODIFIED main popularity slider to control the output that is presented UTILIZING A RANGE WITH 2 SELECTORS
    - Included for both global top 10 artists PIE CHART as well as the TOP 3 ARTIST PICTURES
    - Also controls the output for the top 10 songs when specific country selected
- Reformatted colours, headers with steps to guide the user, positioning/layout/sizing of the chart/table areas



**What needs to be improved:**

    - If so, potentially add an additional plot or summary statistics in the bottom right to further describe popularity insights (NOT COMPLETED)
        - THIS WAS NOT COMPLETED IN MILESTONE 4 due to positioning, space, and layout of tab 3


