# **Fabricland College Quest Power BI Analytics Dashboard**

This project delivers a comprehensive, multi-page Power BI analytics dashboard built from *The College Quest in Fabricland Dataset*, a structured workbook containing two interconnected tables: **College_Profiles** and **Programs_Majors**. The goal of the dashboard is to help students, academic planners, and institutional leaders understand college performance, program quality, student life factors, and long-term outcomes within the Fabricland educational system.

<img width="1432" height="805" alt="image" src="https://github.com/user-attachments/assets/a79a8e1e-13bd-48ee-99dc-54398b54b710" />
<img width="1437" height="807" alt="image" src="https://github.com/user-attachments/assets/a6fdada2-2c41-4f1e-a6f7-aaf497e805a7" />
<img width="1437" height="806" alt="image" src="https://github.com/user-attachments/assets/57871e36-c073-4b91-8304-f67d83643008" />

The solution begins by importing and transforming data from the Excel file into a clean, relational model using **Power Query**. The **College_Profiles** table forms the core dimension, containing metrics such as tuition fees, MagicScore, placement rates, student satisfaction scores, diversity indices, and guild partnerships. The **Programs_Majors** table complements this with program-level details such as enrollment, graduation rates, popularity scores, starting salaries, difficulty levels, careers, and awards. A one-to-many relationship is created through the CollegeID key to ensure accurate filtering and drillthrough.

Using this model, the dashboard is structured into clear, purpose-driven pages:

* **Overview**: KPIs and high-level performance indicators for quick insights.
* **Colleges Page**: Benchmarking and ranking colleges on quality, affordability, student life, and outcomes.
* **Programs Page**: Analyzing demand, graduation rates, popularity, and salaries across academic programs.
* **ROI & Outcomes**: Visualizing the cost–benefit relationship between tuition and student success metrics.
* **Student Life & Diversity**: Assessing experience factors like housing, events, support services, and inclusion.
* **Guild Partnerships**: Exploring the network of guild connections and their impact on placements and salaries.
* **Drillthrough Pages**: Dedicated details for individual colleges or programs.

The dashboard uses a combination of **cards**, **ranked bar charts**, **scatter plots**, **matrices**, **small multiples**, and **network visuals**, each enhanced with drillthrough, tooltips, slicers, and bookmarks to enable interactive storytelling. DAX measures were created for ranking, payback years, weighted scores, enrollment shares, and experience indices to provide deeper analytical insights.

Overall, this project showcases strong competency in **data modeling**, **visual analytics**, **dashboard UX design**, and **business storytelling**. It transforms a raw, fantasy-themed dataset into a decision-ready intelligence system that highlights value-for-money colleges, high-impact programs, equity insights, and strategic guild partnerships.

* 21/11/2025
