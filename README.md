### HUD NSPIRE and NYCHA Apartment Inspections in Power BI

This project leveraged Python-based data engineering to transform multiple inconsistent HUD inspection reports into a unified, analysis-ready dataset for visualization in Power BI. The resulting dashboards provided commissioner-level leadership with clear visibility into inspection performance, enabled cross-cycle comparisons of NYCHA outcomes, and supported faster progress toward regulatory compliance and improved building safety.

The primary technical challenge was converting non-text-readable inspection reports into structured, text-based data suitable for analysis. Custom Python algorithms were developed to extract, normalize, and transform unstructured inspection content into standardized CSV files, making the data fully usable for reporting and visualization in Power BI.

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


