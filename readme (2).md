
# Olympic 2024 Interactive Dashboard

Welcome to the Olympic 2024 Interactive Dashboard project! This project leverages Power BI to build a dynamic and engaging dashboard that visualizes key data from the Paris 2024 Olympics. Designed to provide real-time updates and interactive visualizations, this dashboard allows users to track medal counts, athlete performance, event schedules, and more, offering a comprehensive view of the games.



## Acknowledgements

Kaggle: For providing comprehensive Olympic datasets.
Figma: For its powerful design tools.
Power BI: For its robust data visualization capabilities.
## Features


Interactive Visualizations: Engaging charts and graphs that let users explore Olympic data from multiple perspectives.

Real-Time Data Updates: Automatically refreshes to include the latest data, keeping the dashboard current and relevant.

Customizable Views: Filters and slicers to allow users to focus on specific athletes, countries, or events.

Performance Tracking: Visuals to monitor athlete performance, medal counts, and historical comparisons.


## Dataset Link
https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games
## Steps

### 1. **Power Query: Setup Tables**

**Objective**: Import and prepare data for your dashboard.

#### Steps:
1. **Open Power BI Desktop**:
   - Launch Power BI Desktop to start a new project.

2. **Connect to Data Sources**:
   - Go to the `Home` tab and click on `Get Data`.
   - Select your data source (e.g., Excel, CSV, SQL Server) and load your data.

3. **Transform Data Using Power Query**:
   - Click on `Transform Data` to open the Power Query Editor.
   - **Clean and Transform**: Remove unnecessary columns, filter out irrelevant rows, and correct data types.
   - **Create Relationships**: Ensure tables are properly related if using multiple datasets.
   - **Setup Tables**: Ensure each table is structured correctly and create calculated columns or tables if needed.

4. **Load Data**:
   - Click `Close & Load` to import the cleaned data into Power BI.

### 2. **Overview Page**

**Objective**: Create a summary page with key metrics and visualizations.

#### Steps:
1. **Create a New Page**:
   - In Power BI, add a new page and name it "Overview".

2. **Add Visualizations**:
   - **DAX Measures**: Use DAX to create measures for key metrics (e.g., total medals, average performance).
     ```DAX
     TotalGoldMedals = SUM('Medals'[Gold])
     ```
   - **Filters**: Add slicers for filtering data by country, sport, or date.
   - **Visualization**: Insert charts, maps, and KPI visuals to summarize data.

3. **Add World Map**:
   - Drag and drop the "Map" visual from the Visualizations pane.
   - Configure it to show data by country using the appropriate fields.
   - Add a filter to select different countries.

### 3. **Figma Background Creation**

**Objective**: Design and implement a visually cohesive background for your dashboard.

#### Steps:
1. **Design in Figma**:
   - **Create Background**: Use Figma to design a background that aligns with the Olympic theme.
   - **Add Colors**: Choose a color palette that matches the Olympic branding or your preferred theme.
   - **Incorporate Images and Icons**: Add relevant images and icons (e.g., Olympic rings, country flags).

2. **Export Assets**:
   - Export your Figma designs as images (PNG, JPEG) or SVG files.

3. **Import to Power BI**:
   - In Power BI, go to the `View` tab and select `Page Background`.
   - Upload your Figma-designed background images to enhance the visual appeal.

### 4. **Athletes Page**

**Objective**: Display detailed information about athletes.

#### Steps:
1. **Create a New Page**:
   - Add a new page and name it "Athletes".

2. **Add Visualizations**:
   - **Total Number of Countries and Players**:
     - Use cards or KPI visuals to display total counts.
   - **Gender Breakdown**:
     - Use pie charts or bar graphs to show the distribution of male and female athletes.
   - **Medal Counts**:
     - Create visuals for gold, silver, and bronze medals using bar charts or pie charts.

### 5. **Country Page**

**Objective**: Show detailed information and statistics for individual countries.

#### Steps:
1. **Create a New Page**:
   - Add a new page and name it "Country".

2. **Add Visualizations**:
   - **Country Overview**:
     - Use tables and charts to display country-specific data, including medals, athletes, and other statistics.
   - **Interactive Filters**:
     - Add slicers or dropdowns to select different countries and view their data.

### 6. **Historical Page**

**Objective**: Provide insights into historical Olympic data using various visualizations.

#### Steps:
1. **Create a New Page**:
   - Add a new page and name it "Historical".

2. **Add Historical Data Visualizations**:
   - **Timeline**:
     - Use line charts or area charts to show historical trends over the years.
   - **Comparative Analysis**:
     - Create visuals to compare different Olympic Games, showing medal counts, performance metrics, etc.
   - **Interactive Filters**:
     - Add filters to allow users to select different years or Olympics and view corresponding data.



By following these steps created a dynamic, interactive Power BI dashboard that effectively presents Olympic 2024 data and enhances user engagement.