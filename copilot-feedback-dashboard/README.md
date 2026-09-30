# Copilot Trial Feedback & Metrics Dashboard

An Excel workbook that models how a generative AI Copilot adoption trial could
be evaluated — collecting user feedback, tracking adoption over an 8-week
trial, and turning raw responses into metrics a project team could act on.

## Why this project

Built specifically around this responsibility from a real posting:

> "Collecting and analyzing feedback data to derive useful metrics"

and

> "Helping develop procedures to improve evaluation processes for activities
> such as our Copilot trials"

## What's inside (`copilot_trial_feedback_dashboard.xlsx`)

- **Raw Data** — 40 simulated feedback responses across 4 departments over an
  8-week trial: satisfaction score, time saved, adoption status, feedback
  theme, and a comment. Modeled on what a Microsoft Forms / survey export
  would look like.
- **Dashboard** — live formulas (`AVERAGEIF`, `COUNTIF`, `COUNTIFS`) that
  calculate:
  - Overall response count, average satisfaction, average time saved, and %
    of users "Using Regularly"
  - Satisfaction and time saved broken down by department
  - Week-by-week satisfaction trend and adoption rate over the trial
  - Frequency of feedback themes (Ease of Use, Time Savings, Accuracy,
    Training Needed, Integration Issues)
  - Three charts visualizing all of the above
- **README (in-workbook)** — explains the data and how each formula maps to
  a real evaluation workflow.

Everything recalculates automatically — replace the Raw Data rows with a real
feedback export and the whole dashboard updates.

## Note on the data

All responses are randomly generated for demonstration. They don't represent
a real trial or real people — the goal is to show the analysis structure and
formulas working correctly on realistic-looking data.

## Tools used

Microsoft Excel (formulas: `AVERAGEIF`, `COUNTIF`, `COUNTIFS`) — deliberately
kept to standard formulas rather than a coding language, since this mirrors
the tools most evaluation/coordination roles actually use day to day.
