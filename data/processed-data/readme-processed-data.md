# Processed Data

This folder contains data that has been processed or cleaned by code.

Files here should are based on raw data in `data/raw-data/` and should be possible to recreate by
running the processing scripts in `code/data-processing/`.

## File Inventory

| File Name | Description | Survey(s) | Time Unit |
|-----------|-------------|-----------|-----------|
| ipeds_institution_characteristics.csv | Details about institutions, including UNITID, name, location, and attributes like public/private, size, Carnegie classification | HD | Fall Term |
| ipeds_cohort_retention.csv | Uses adjusted cohort and count of students retained next fall to calculate retainment rate | Fall Enrollment (D) | Fall Term |