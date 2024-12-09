# CCAI Insights Looker Dashboards

## Overview

This CCAI Insights Looker Block uses the BQ export to provide a more holistic view of the business's call center and agent performance via the following dashboards:

* Call Center Performance: Executive dashboard displaying high-level metrics intended for call center management. 
* Agent Performance: Performance metrics for an individual agent, linked from the Agent ID dimension.
* Agent Operations: Performance metrics for agents in aggregate.
* Conversation Lookup Dashboard: Detailed transcript and sentiment analysis for an individual conversation, linked from the Conversation Name dimension.

## Instructions

1. Copy each of files from the dashboards, models and views folders into a new LookML Project
2. Copy the manifest.lkml file into the LookML project
3. Update the db_connection_name constant in the manifest file with your db connection name
4. Update the insights_table constant in the manifest file with your Insight export's dataset.table name

## Documentation
[BQ Schema](https://cloud.google.com/contact-center/insights/docs/bigquery-all-schemas)
*Note: This Looker block is compatible with BQ Schema v4 and higher