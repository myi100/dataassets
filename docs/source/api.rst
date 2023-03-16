Q-Dietary Oxysterols and Diabetes
=================================

.. autosummary::
   :toctree: generated

   lumache

# REDCap

## Screening Questionnaire

### Project Statistics

+----------------------+----------------------+
| Records in project   | Most recent activity |
+======================+======================+
|         109          | 03/16/2023 11:58am   |
+----------------------+----------------------+


### Data Quality Metrics

+-----------------------------------------------+---------------------+
| Rule Name                                     | Total Discrepancies |
+===============================================+=====================+
| Blank values* (required fields only)          | 166                 |
| Field validation errors (incorrect data type) | 72                  |
| Field validation errors (out of range)        | 0                   |
| "Outliers for numerical fields                | 2                   |
| Hidden fields that contain values***          | 11                  |
| Multiple choice fields with invalid values    | 0                   |
| Incorrect values for calculated fields        | 0                   |
+-----------------------------------------------+---------------------+


### Codebook

+--------------------------------------------------+-------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------+
| Variable / Field Name                            | Field LabelField Note                                                                           | Field Attributes (Field Type, Validation, Choices, Calculations, etc.)                                  |
+==================================================+=================================================================================================+=========================================================================================================+
| [record_id]                                      | Record ID                                                                                       | text                                                                                                    |
| [date]                                           | DateToday's date                                                                                | "text (date_mdy, Min: 2021-07-01), Required, Identifier                                                 |
| Custom alignment: LV"                            |                                                                                                 |                                                                                                         |
| [name]                                           | Name (First, Last)Provide First and Last Name                                                   | "text, Required, Identifier                                                                             |
| Custom alignment: LV"                            |                                                                                                 |                                                                                                         |
| [date_of_birth]                                  | Date of Birth                                                                                   | "text (date_mdy, Min: 1931-01-01, Max: 2003-01-01), Required, Identifier                                |
| Custom alignment: LV"                            |                                                                                                 |                                                                                                         |
| [current_age]                                    | Current Age Years                                                                               | text (number), Required                                                                                 |
| [zip_code]                                       | Zip Code                                                                                        | text (zipcode), Required, Identifier                                                                    |
| [are_you_african_american]                       | Do you describe yourself as African American?                                                   | radio, Required1 Yes 2 No                                                                               |
| "[not_africian_american] Show the field ONLY if: |                                                                                                 |                                                                                                         |
|  [are_you_african_american] = '2'"               | If you answered no, which ethnic group(s) do you identify with:                                 | radio1 American Indian or Alaska Native 2 Asian 3 Native Hawaiian or Pacific Islander 4 White/Caucasian |
| [sex_assigned_at_birth]                          | Sex assigned at birth:                                                                          | radio, Required1 Male 2 Female 3 Other                                                                  |
| [tobacco_use]                                    | Have you used tobacco - cigarettes, cigars, pipes, or smokeless tobacco - in the past 3 months? | yesno, Required1 Yes 0 No                                                                               |
| [marijuana]                                      | Have you used marijuana products - smoking or edibles - in the past 3 months?                   | yesno1 Yes 0 No                                                                                         |
| [are_you_pregnant]                               | Are you currently pregnant or think you may be pregnant?                                        | yesno, Required1 Yes 0 No                                                                               |
| [are_you_currently_breast_f]                     | Are you currently breast feeding?                                                               | yesno, Required1 Yes 0 No                                                                               |
| [hba1c]                                          | In the past 6 months, what is you most recent HbA1c (glycated hemoglobin) level?                | text (number), Required                                                                                 |
| [lower_blood_sugar]                              | Do you currently take prescription drugs to lower your blood sugar?                             | radio, Required1 Yes 2 No                                                                               |
+--------------------------------------------------+-------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------+

