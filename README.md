# Overview
This repository contains stored procedure, scripts for managing and analyzing data from 5 Starbucks branches. 
All branch data is automatically merged into the Starbuks's master one, using a scheduled job.

## Daily Job Schedule
Job Purpose: Merges data from 5 separate branch sources into a centralized master dataset.

Time: Runs daily at 6:25 PM.

Job Type: script scheduled via DBMS_SCHEDULER.

## Technologies Used
  Oracle SQL Developer (11g)
  Git & GitHub
