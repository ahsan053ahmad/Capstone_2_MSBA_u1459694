# Capstone_2_MSBA_u1459694
This repository contains individual notebooks and project documentation for Swire Coca-Cola’s predictive maintenance case.

## **Business Problem**
Swire Coca-Cola is grappling with a major production challenge: achieving only 94.4% of its annual production target, which translates to a shortfall of millions of cases. This issue stems from unplanned machinery breakdowns that disrupt production lines, costing the company approximately $60 million annually in lost productivity.

The company currently relies on a reactive maintenance system, which triggers repairs only after machinery failures occur. This outdated approach not only prolongs repair times but also exacerbates production losses by delaying the availability of critical parts and labor.

To address this problem, our project proposes a predictive maintenance solution leveraging advanced Survival Analysis techniques. The solution aims to forecast equipment failures, enabling Swire Coca-Cola to transition from reactive to proactive maintenance, significantly reducing downtime and improving production efficiency.

## **Project Objective**
This project focuses on providing Swire Coca-Cola with a robust, data-driven predictive maintenance solution. Our primary objectives include:

1. Developing a predictive maintenance model to forecast when machinery is likely to fail.
2. Identifying high-risk equipment and uncovering patterns associated with failures.
3. Enabling proactive maintenance scheduling by generating actionable insights, ensuring repairs are completed before breakdowns occur.

By achieving these objectives, we aim to help Swire Coca-Cola move closer to maximizing production capacity and achieving their annual targets.

## **Group Solution**
To address Swire Coca-Cola’s challenges, the team adopted a multi-faceted approach, leveraging individual strengths to tackle different aspects of the problem. The focus began with survival analysis, using Kaplan-Meier estimators to model survival probabilities and Cox Proportional Hazards models to identify risk factors contributing to equipment failures. Alongside this, the team developed models to forecast production losses, estimating the number of affected orders and total downtime caused by machine failures. Additionally, text-based work order data was analyzed to uncover patterns in the causes and durations of downtime, providing valuable contextual insights for maintenance planning. This collaborative strategy ensured a comprehensive solution addressing both predictive and contextual dimensions of the business problem.

## **My Contribution**
My work was pivotal in providing a statistical foundation for predictive maintenance through Survival Analysis. Key contributions included:

1. **Data Cleaning and Exploration**: Addressed significant data quality issues, such as missing values in critical fields (e.g., equipment IDs), through imputation and preprocessing techniques.
2. **Kaplan-Meier Survival Curves**: Generated survival curves to model the probability of equipment functioning over time at Varying Levels of Detail: From Functional Area to Equipment Types to Equipment IDs.
3. **Cox Proportional Hazards Model**: Utilized this model to evaluate the relative risk of failure, quantifying the impact of predictors like machine age, usage intensity, and environmental conditions.
These analyses provided actionable insights into which equipment types and locations were most prone to failures, guiding proactive maintenance planning.

## **Business Value**
The implementation of this predictive maintenance model offers significant benefits:
1. **Cost Savings**: Reducing unplanned downtimes could save the company up to $60 million annually, a substantial improvement to the bottom line.
2. **Enhanced Production Efficiency**: By improving equipment availability, Swire Coca-Cola could aim for production efficiency rates exceeding 98%, narrowing the gap toward full capacity.
3. **Data-Driven Decision Making**: The solution provides prioritized insights, helping maintenance teams focus on high-risk machinery and allocate resources effectively.
4. **Improved Resource Planning**: Spare parts and labor could be pre-positioned for maintenance tasks, minimizing delays and disruptions.
These benefits not only mitigate immediate losses but also contribute to long-term operational resilience and sustainability.

## **Challenges Encountered**
The project encountered significant challenges, particularly with data quality, as missing or inconsistent values in key fields required extensive cleaning and imputation. Additionally, the complexity of survival models demanded careful feature selection to balance overfitting risks while retaining relevant predictors. Collaborative integration posed another challenge, as aligning individual analyses into a cohesive framework required iterative discussions. Despite these obstacles, the team successfully delivered a practical and reliable predictive maintenance solution.

## **Lessons Learned**
The project highlighted the critical role of data quality, emphasizing the need to address missing and noisy data in real-world applications. It also demonstrated the power of Survival Analysis in predicting time-to-failure and identifying high-risk equipment. The collaboration proved invaluable, as integrating diverse methods created a unified solution. Ultimately, the scalability of the model especially doing survival analysis across multiple granularities e.g. from Functional Area to Equipment IDs not only addressed current challenges but also provided a framework for broader application across production facilities.

