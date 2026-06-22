# Agent Instructions - Head of State Tweets and Stock Markets

## Project

This project studies how head of state tweets, posts, speeches, or formal declarations may affect stock market behavior.
The work may use public sources and licensed or paid datasets, including market data, text data, and metadata about events.

## Workflow

- Use issue -> branch -> pull request for every change, including documentation and analysis updates.
- Plan before editing multiple files.
- Keep edits scoped to the active question, dataset, or analysis step.
- Run the documented verification command before claiming work is complete.
- Treat agent output as a proposal until a human reviews the diff and evidence.

## Economics Standards

- Document data sources, transformations, units, timestamps, sample restrictions, and missing-data handling.
- Use relative paths.
- Do not modify raw data.
- Separate research claims from code mechanics.
- Be very careful with causal language.
- Do not claim identification, causality, or interpretation unless the design, assumptions, and evidence clearly support it.
- Flag confounding, simultaneity, anticipation, and selection issues explicitly when relevant.
- Prefer descriptive, event-study, or association language when causal identification is not airtight.

## Data and Privacy

- Public data and licensed or paid data are allowed.
- Do not commit secrets, API keys, private data, confidential manuscripts, or license-restricted files that should not live in the repo.
- Do not ask agents to read `data/raw/`, `data/private/`, or `.env`.
- If using any cloud or autonomous agent workflow, complete the risk card before connecting it to research work.

## Stata

- Use Stata for data cleaning, analysis, and replication when that is the project standard.
- Prefer do-files and logged runs over manual GUI steps.
- Record the exact Stata version, packages, and commands used for any analysis.
- Keep analyses reproducible from the repository with relative paths and scripted steps.

## Verification

Run the project’s documented verification command before claiming the work is complete.
If a task adds or changes Stata analysis, include the Stata replication or validation step in the verification plan.

## Final Packaging

For release or submission packaging, also follow the project’s replication instructions if present.
