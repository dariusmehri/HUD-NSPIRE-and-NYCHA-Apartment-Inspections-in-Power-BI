### HUD NSPIRE and NYCHA Apartment Inspections in Power BI

This project implemented the use of Python to develop data-engineering algorithms that converted several incoherent HUD inspection reports into a unified, analysis-ready dataset for visualization in Power BI. This gave commissioner-level managers easy access for performance tracking, compare NYCHA inspection outcomes, and accelerate progress toward compliance and improved building safety.

The most important challenge was to convert non-text readable independent inspection reports into text readable data that could be input into Power BI for visualization. Once the data was converted into text,  the next step was to develop algorithms to transform the unstructured data into a structured csv files for visualization. Both of these steps were accomplished by developing data engineering algorithms in Python.

### Results

The table below presents a sample of Asset Management Projects (AMPs), their inspection scores, and a comparison with the previous inspection cycle.

<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/13ec452a-a389-47a1-bf94-7a3af8944155" />


###

A random sample of 30 apartments is inspected, with identified deficiencies generating deduction points that are aggregated at the AMP level.


<img width="627" height="565" alt="image" src="https://github.com/user-attachments/assets/a9dba2d0-7878-43b5-ac18-ed1aeeb4a9cc" />

###

Inspection notes were analyzed using text-mining techniques to create standardized deficiency categories. The most common categories were electrical and egress issues, followed by lead and mold.

<img width="790" height="535" alt="image" src="https://github.com/user-attachments/assets/c170bd1c-708a-40e1-9373-2fc706f7511c" />

###

A drill-down analysis was developed to compare NSPIRE deficiencies with findings from annual NYCHA apartment inspections.

<img width="916" height="457" alt="image" src="https://github.com/user-attachments/assets/f38a2db6-a999-48b3-9257-a7cd1847513d" />


