# Weekly Social Media Reporting Automation

A Python workflow that consolidates weekly exports from Facebook, Instagram, TikTok, X, and YouTube into a standardized reporting dataset.

The workflow automates repetitive data preparation, extracts show labels from post titles, maps sources using a reference table, and exports a consolidated CSV for manual validation.

## Business impact

Based on my experience with this weekly workflow, preparation and labeling previously required approximately 7–9 hours. After automation, approximately one hour of hands-on work remains for label validation and quality checks.

## Skills demonstrated

- Multi-source data integration using pandas
- Data cleaning and schema standardization
- Rule-based labeling and reference-table mapping
- Date parsing and multilingual text normalization
- Data validation and reporting automation

## Scope

This workflow processes downloaded platform exports. Labeling relies on title conventions and a maintained lookup table, with human review required for exceptions.

## Internal reporting context

This workflow reflects reporting requirements and conventions agreed through internal communication with the relevant teams. It demonstrates an internally aligned reporting process rather than a universal standard for social media measurement.

Most metric mappings and calculations follow the definitions in each platform’s exports. Additional choices—including interaction formulas, labeling rules, and the treatment of unavailable values—reflect internal reporting agreements.

Column names are standardized to simplify consolidation, validation, and internal approval. **Shared column names do not mean that metrics have identical definitions or are directly comparable across platforms.**

Other organizations may require different formulas and reporting rules. Before adapting this workflow, confirm the relevant platform definitions and agree the calculations with your teams.
