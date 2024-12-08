## Summary of Business Problem and Project Objective
Swire Coca-Cola, one of the world’s largest beverage companies, faces significant operational challenges due to unplanned machine breakdowns at its manufacturing plants. These disruptions reduce production capacity to 94.4% and result in an estimated $60 million annual loss, impacting both efficiency and profitability.

The objective of this project was to address these challenges using predictive analytics. By analyzing machine performance data, the project aimed to forecast equipment failures, optimize maintenance schedules, and improve overall production efficiency.

## Group's solution

Our group applied survival analysis and regression modeling to machine performance data to predict equipment failure and downtime durations. This approach provided actionable insights into unplanned machine failures and enabled proactive maintenance planning.
Key highlights of the group’s solution include:

- **Survival Analysis:** We Used Kaplan-Meier estimates to identify time-to-failure probabilities for key functional locations and equipment like filler and valve.
- **Regression Models:** Developed and tested multiple models, with ElasticNet achieving the best performance (Test RMSE: 82.27)

These insights were translated into recommendations for optimized maintenance schedules and inventory management strategies, significantly reducing unplanned downtime and operational disruptions.

## Contribution to the project
I was responsible for structuring the EDA file and writing interpretative comments to highlight key insights from the data. We began the modeling phase by building a series of regression models, but they did not yield the results we expected. After reviewing the outcomes, I suggested shifting our approach from predictive to descriptive modeling, which led us to explore Kaplan-Meier curves for survival analysis.

As part of this analysis, I focused on unplanned maintenance breakdowns and identified fillers as a key category due to their frequent unplanned order descriptions. I recommended running a Kaplan-Meier analysis specifically for fillers, which helped refine our maintenance strategy and improve targeting.

## Business Value of the Solution
The predictive maintenance solution offers substantial business value by addressing unplanned machine breakdowns, which are a major issue for Swire Coca-Cola. By converting unplanned activities into planned ones, the company could reduce median downtime by 36% at full capacity. This brings several advantages:

- Operational Efficiency: Fewer unplanned production disruptions would allow Swire to maintain a steady production pace and improve capacity utilization.
- Cost Savings: Reducing downtime can minimize financial losses, currently estimated at $60 million annually, while also cutting repair and replacement costs and labor expenses linked to unplanned breakdowns.
- Lean Inventory Management: Better insights into high-demand parts would allow for more efficient inventory planning, helping to avoid overstocking and ensuring the availability of critical components, which minimizes repair delays.
- Strategic Resource Allocation: The sounlition would help Swire enable prioritization of high-risk locations, optimizing the allocation of resources like labor and spare parts, thus minimizing operational disruptions.
- Proactive Maintenance Management: By streamlining maintenance plans, the company would move from a reactive to a more proactive strategy, minimizing downtime and addressing possible failures before they happen.
  
These improvements can enhance Swire Coca-Cola’s production reliability, reduce waste, and strengthen its competitive position in the beverage industry.

## Difficulties Encountered
Our group encountered a few significant challenges during the project:

- Missing Data: A substantial portion of the data (up to 70%) was missing in key fields. Deleting these records would have removed valuable information, and imputing values would have introduced bias. We had to work creatively with the available data, finding ways to make the most of it without compromising the integrity of our analysis.
- Unidentified Machine Age: The lack of clear data on machine age and usage patterns made it difficult to incorporate these factors into our models, affecting the accuracy of predictions and limiting the insights we could derive from this.

Despite these difficulties, we worked together to develop innovative solutions and deliver meaningful insights from the data.

## Learning Received
Throughout this project, I learned how to navigate real-world problems where data is often incomplete or missing. Working with limited data required us to think creatively and come up with innovative solutions that allowed us to make the most of the available information while preserving the integrity of our analysis. I also gained valuable experience in survival analysis, a technique I had not encountered before, which broadened my modeling skills and analytical toolkit.

Additionally, I realized how essential effective communication and teamwork are when addressing challenges and making project decisions. Collaborating closely with my team allowed us to leverage each other’s strengths and ensure that we were consistently moving toward our goals. This project reinforced the importance of adaptability, problem-solving, and clear communication in tackling complex, real-world issues.
