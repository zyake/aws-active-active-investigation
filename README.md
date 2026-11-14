# AWS active-active investigation

Architecture investigation of active-active and active-standby applications using multi-Region Amazon Aurora DSQL.

## Read the report

- [Complete architecture and availability report](aws_aurora_dsql_architecture_and_availability_report.md)
- [Regional routing and recovery dependencies](aws_aurora_dsql_architecture_and_availability_report.md#regional-routing-and-recovery-dependencies)
- [Customer recovery and root cause analysis](aws_aurora_dsql_architecture_and_availability_report.md#customer-recovery-and-root-cause-analysis)
- [Download the Markdown report and diagrams](aws_aurora_dsql_architecture_and_availability_report_markdown.zip?raw=1)

## Coverage

| Topic | Investigation |
| --- | --- |
| Architecture decisions | Application active-active versus active-standby, with Aurora DSQL responsibilities and application boundaries |
| AWS Well-Architected pillars | Operational Excellence, Reliability, Performance Efficiency, Security, Cost Optimization, and Sustainability |
| Regional recovery | Ingress, internal dependencies, database endpoints, asynchronous work, destination capacity, and failback |
| Incident investigation | Customer recovery, operation correlation, uncertain outcomes, evidence collection, and causal analysis |
| Availability | AWS service SLAs, measured customer outcomes, SLOs, and recovery exercises |
| Supporting evidence | Links to AWS documentation, AWS architecture guidance, and public papers |

The report includes 46 diagrams. The expanded routing and incident-investigation sections each contain detailed decision tables, examples, and proposed validation exercises.

Report edition: **14 November 2026**. Illustrative diagrams and calculations are labeled in the report. Page references refer to the earlier 44-page PDF and Word edition; the expanded sections are part of this Markdown edition.

## Files

Keep the `aws_aurora_dsql_architecture_and_availability_report_assets` directory alongside the Markdown file when viewing the report locally. The ZIP contains a portable copy of the report and its diagrams. Source links require internet access.
