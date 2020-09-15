# LeadQualification_Project

This contains a group project to help an organization on a lead qualification to identify potential sales that will become a lead or customer

# Blossom Academy Use Case Data - Lead Qualification

# Background:

As a new quarter approaches, an influx of new sales activity has led your
sales team to work systematically down a list of new leads. With a
limited number of resources and time, being able to quickly identify a
lead with a higher probability to convert to an opportunity and
ultimately a close would aide in the prioritization and focus of your
dedicated sales resources, maximizing their time and effectiveness. We
can leverage ML to identify with a level of certainty the conversion to
an opportunity as well as a probability to close by looking for trends in
the features captured of the new incoming leads.
Business Question:
Given these attributes of each lead, will it convert to an opportunity?
Data Set Structure Guidelines:
New incoming leads are structured on each row with lead information. The
OppStatus is the target column and will be predicted along with a
probability percentage which can then be grouped into probability ranges
for consumption.
The "History" file is used to train the model, and the "PredictMe" file
is used to create predictions from the trained model.
The "PredictMe" data file is identical to the "History" file, except that
all values in the target column are blank.
