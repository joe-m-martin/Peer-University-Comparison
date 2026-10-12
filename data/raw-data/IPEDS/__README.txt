# IPEDS Data

To download new files, go to: 
https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx

Each survey folder requires a specific file to download. Follow the guide in the IPEDS Data Transformation script to locate the proper files.

# Output Files

12-month_enrollment.csv
CIP_Code_Analysis.csv (defines cip-codes for impactful degree metric)
cohort_retention.csv
doctoral.csv (count of doctoral degrees awarded)
enrollment.csv
enrollment_residency.csv
faculty.csv
finance.csv
graduation.csv
impactful_degrees.csv
Institution Characteristics.csv (institutional characteristics, dashboard uses most recent file, only)
net_price.csv
outcome_measures.csv (measures pell graduation rates)
pell_graduation_rates.csv (old file, needs to be fixed - has outcome measure for loan recipients)
pro_grad_tuition_fees.csv
student_fin_aid.csv (count/percent of students awarded pell/loans)
Terms.csv (enables script to join all tables by varying time units, ex. fiscal, acad, calendar year)
tuition_fees.csv
undergraduate_enr_res.csv (enrollment by residency)



# For Tableau dashboard: 

Each metric should be one calculation that returns a single measure. 

Create a parameter that selects individual metrics. This allows users to see one metric at a time. 
- Pair this with the ability to select 1-5 years worth of data for each metric. 

Create a case statement to change the calc when a new metric is selected. 

Create a long calc that sums all z-scores in the defined model: 
