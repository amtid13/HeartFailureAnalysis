# HeartFailureAnalysis

Cardiovascular diseases (CVDs) are the number 1 cause of death all over the world, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide.
Heart failure is a common event caused by CVDs, and this dataset contains 12 features that can be used to predict mortality by heart failure, as well as analyze and understand the main factor for these diseases.

Most cardiovascular diseases can be prevented by addressing behavioral risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity, and harmful use of alcohol using population-wide strategies.

People with CV disease or who are at high cardiovascular risk (due to one or more risk factors such as hypertension, diabetes, hyperlipidemia, or already established disease) need early detection and management, wherein a great analysis of it can be of great help.

In this dataset and task, the goal is to explore the following research question:

    What are the risk factors most predictive of mortality by heart failure?

In this task, a few datasets are provided:
1. base_metrics_patient.csv - the base DF contains the main metrics measured per each patient. These are:

    uniqueID - patient ID
    smoking - If the patient smokes or not (boolean)
    ejection_fraction - Percentage of blood leaving the heart at each contraction (%)
    serum_sodium - Level of serum sodium in the blood (mEq/L)
    platelets - Platelets in the blood (kiloplatelets/mL)
    creatinine_phosphokinase - Level of the CPK enzyme in the blood (mcg/L)
    diabetes - If the patient has diabetes (boolean)
    serum_creatinine - Level of serum creatinine in the blood (mg/dL)

    blood_metrics_df.csv - an additional dataset containing some more metrics about each patient. Specifically, it contains:
        uniqueID - patient ID
        anaemia - Decrease of red blood cells or hemoglobin (boolean)
        high_blood_pressure - If the patient has hypertension (boolean)
    demographic_data.csv - some extra data about the patient’s demographics, specifically:
        uniqueID - patient ID
        age - patient’s age
        sex - (male - 1, female - 0)
    follow_up_df.csv - a dataset containing details about a follow-up check with that patient. It contains:
        uniqueID - patient ID
        time - time passed (in days) between the measurement date (see dataset #1) until that “follow-up” date
        DEATH_EVENT - If the patient deceased during the follow-up period (boolean)
