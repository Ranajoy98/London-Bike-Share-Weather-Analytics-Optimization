# London Bike Share Weather Analytics & Optimization

## Project Overview
Comprehensive data analysis of London's bike sharing system, examining temporal patterns, weather impacts, and usage behaviors to optimize operations and improve service delivery.

## Key Achievements

### Advanced Analytics Implementation
- **Multi-dimensional Analysis**: Successfully integrated temporal, weather, and usage pattern analysis
- **Interactive Dashboards**: Created two comprehensive Tableau dashboards with dynamic filtering capabilities
- **Correlation Analysis**: Identified strong relationships between weather conditions and bike share demand
- **Predictive Insights**: Generated actionable insights for operational planning and resource allocation

### Data Visualization Excellence
- **4 Specialized Charts**: Developed targeted visualizations for different analytical needs
- **Real-time Filtering**: Implemented interactive controls for dynamic data exploration
- **Trend Analysis**: Created trend lines and correlation coefficients for quantitative insights
- **Professional Presentation**: Designed executive-ready dashboards with clear visual hierarchy

## Key Metrics Summary

### Usage Statistics
- **Total Cumulative Rides**: 19,905,972
- **Peak Daily Average**: 2,286,214 rides
- **Weekday Performance**: 1,223.3 average rides (highest)
- **Weekend Performance**: 977.4 average rides
- **Holiday Performance**: 769.5 average rides (37% lower than weekdays)

### Temporal Patterns
- **Morning Peak**: 8-9 AM (2,087,164 total rides)
- **Evening Peak**: 5-6 PM (1,201,745 total rides)
- **Peak Hour Usage**: 3K rides during holiday peaks vs 2K on regular days
- **Low Usage Hours**: 0-5 AM (consistently under 500 rides)

### Weather Impact Analysis
- **Optimal Weather**: Clear conditions generate 7,146,847 total rides
- **Temperature Correlation**: Strong positive correlation (0.8+) with usage
- **Humidity Impact**: Inverse relationship - 60%+ humidity reduces usage by 50%
- **Wind Speed Threshold**: Usage drops significantly above 40 km/h wind speed
- **Severe Weather**: Snowfall reduces usage to just 15,051 rides

## Strategy Recommendations

### 1. Operational Optimization
**Fleet Management**
- **Peak Hour Deployment**: Increase bike availability during 8-9 AM and 5-6 PM windows
- **Weekend Rebalancing**: Redistribute bikes from business districts to recreational areas on weekends
- **Holiday Planning**: Reduce active fleet by 25% during holidays to optimize maintenance costs

**Maintenance Scheduling**
- **Low-Usage Windows**: Schedule maintenance during 0-5 AM hours
- **Weather-Based Planning**: Plan major maintenance during high humidity periods (>70%)
- **Seasonal Adjustments**: Increase maintenance frequency during winter months

### 2. Weather-Responsive Strategy
**Dynamic Pricing Model**
- **Premium Weather Days**: Implement surge pricing during optimal conditions (15-25°C, low humidity)
- **Incentive Pricing**: Offer discounts during marginal weather to maintain usage
- **Extreme Weather Protocol**: Suspend service during severe conditions (>50 km/h winds, snowfall)

**Predictive Resource Allocation**
- **Weather Forecasting Integration**: Adjust daily bike distribution based on weather predictions
- **Temperature Thresholds**: Prepare for 40% usage drop when temperatures fall below 5°C
- **Humidity Monitoring**: Implement alerts when humidity exceeds 60%

### 3. Customer Experience Enhancement
**Targeted Marketing**
- **Weekend Promotions**: Develop recreational ride campaigns to boost weekend usage
- **Holiday Packages**: Create special holiday rates to increase utilization during low-demand periods
- **Weather Alerts**: Implement customer notifications for optimal riding conditions

**Service Improvements**
- **Peak Hour Service**: Ensure 95% bike availability during morning and evening rushes
- **Weather Stations**: Install real-time weather displays at major docking stations
- **Comfort Campaigns**: Educate users about optimal riding conditions

### 4. Business Intelligence
**Performance Monitoring**
- **Daily KPIs**: Track usage against weather forecasts and day-type predictions
- **Correlation Tracking**: Monitor temperature-usage correlation strength monthly
- **Efficiency Metrics**: Measure fleet utilization rates across different conditions

**Growth Planning**
- **Capacity Expansion**: Focus growth investments during high-correlation weather periods
- **Geographic Analysis**: Identify stations with highest weather sensitivity for targeted improvements
- **Seasonal Budgeting**: Allocate 30% more resources during optimal weather months

## Technical Implementation

### Dashboard Features
- **Interactive Filters**: Real-time filtering by weather conditions, day type, and time periods
- **Correlation Analysis**: Statistical correlation coefficients for weather variables
- **Trend Visualization**: Time-series analysis with forecasting capabilities
- **Performance Metrics**: Key performance indicators with benchmarking

### Data Processing
- **Hourly Granularity**: Analysis at hourly level for precise operational insights
- **Multi-variable Analysis**: Integration of 8+ weather and temporal variables
- **Statistical Validation**: R-squared values and correlation coefficients for reliability
- **Scalable Architecture**: Framework ready for additional data sources

## Success Metrics

### Operational Efficiency
- **Fleet Utilization**: Target 85% utilization during peak periods
- **Maintenance Optimization**: 25% reduction in weather-related repairs
- **Resource Allocation**: 15% improvement in bike availability scores

### Revenue Impact
- **Weather-Responsive Pricing**: Projected 12% revenue increase
- **Peak Hour Optimization**: 20% improvement in high-demand period satisfaction
- **Holiday Strategy**: 30% increase in holiday period usage

### Customer Satisfaction
- **Service Availability**: Maintain 95% availability during optimal conditions
- **Weather Preparedness**: Reduce weather-related service disruptions by 40%
- **User Experience**: Achieve 90% customer satisfaction scores

---

## Data Sources
- **Primary Dataset**: London Bike Share hourly usage data
- **Dataset Link**: https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset
- **Dataset Nature**: The dataset includes information on weather conditions, timestamps, and bike rental counts. 
- **Weather Integration**: Temperature, humidity, wind speed, and weather category data
- **Temporal Variables**: Holiday calendars, weekend/weekday classifications


## Tools & Technologies
- **Python**: Data preprocessing and analysis.
- **Tableau**: Interactive dashboard creation.
- **Libraries**: Pandass for data manipulation.


## Acknoledgement
- The data is acquired from 3 sources:

- Https://cycling.data.tfl.gov.uk/ 'Contains OS data © Crown copyright and database rights 2016' and Geomni UK Map data © and database rights [2019] 'Powered by TfL Open Data'

- freemeteo.com - weather data

- https://www.gov.uk/bank-holidays

- From 1/1/2015 to 31/12/2016
