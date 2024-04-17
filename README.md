# HR-Analytics

### OVERVIEW
  
#### Unveiling the Links Between Demographics, Performance, and Attrition
This HR Analytics project delves into the fascinating interplay between employee demographics, performance, and attrition. By leveraging a rich dataset encompassing employee information, performance reviews, and career history, we aim to shed light on the factors influencing employee retention and success within the organization. These insights can be instrumental in developing targeted HR strategies:
Tailored training: Focus training programs on areas linked to improved performance and satisfaction based on employee demographics or job roles.
Retention initiatives: Implement targeted programs to address the needs of high-risk groups identified through attrition analysis.
Work-life balance improvements: Address work-life balance concerns in departments with lower satisfaction or higher attrition rates.
This project aims to uncover valuable connections between employee demographics, performance, and attrition. By understanding these relationships, we can empower HR professionals to create a more engaging and rewarding work environment, ultimately leading to a more successful and satisfied workforce.

**Demographics:** We'll explore how factors like age, gender, education level (linked with the Education table), and marital status (from the Employee table) correlate with performance and attrition. Age analysis involves segmenting employees into age bins (AgeBins column) and examining if younger or older employees have higher performance ratings or are more likely to leave.
Similarly, we will investigate whether specific educational backgrounds or marital statuses influence employee satisfaction or retention.

**Performance:** Performance data (from the PerformanceRating table) will be a key focus. We'll analyze the relationship between various aspects of job satisfaction (environment, training, work-life balance) and employee performance ratings (both self and manager ratings). We can identify if employees with higher satisfaction in specific areas consistently outperform others. Additionally, correlations between training opportunities and performance improvements can be explored.

**Attrition:** We will explore if employees in specific departments, with lower satisfaction levels, or those who haven't received promotions in a long time (YearsSinceLastPromotion) are more likely to leave.


#### DataSets
**Employee Table:** This central table holds core employee details like demographics (age, gender), job information (department, role), compensation (salary, stock options), and career history (years with company, promotion history). It also includes an "Attrition" flag indicating if an employee left the company.
**Education Table:** This table links to the Employee table and details employee education levels (e.g., Bachelor's degree, Master's degree).
**Performance Rating Table:** This table captures employee performance reviews at specific dates. It includes details on the employee's satisfaction with various aspects of work (environment, training opportunities, work-life balance) and both self and manager performance ratings. This table links to RatingLevel table, Employee table, EducationLevel and SatisfiedLevel.
**SatisfiedLevel Tabel:** The table defines categories for satisfaction levels (e.g., Highly Satisfied, Neutral, Dissatisfied).
