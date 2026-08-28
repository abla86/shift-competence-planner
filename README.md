# Shift & Competence Planner

A C#/.NET staffing-planning application for modelling shifts, staffing requirements and competence coverage using fictional workforce data.

## Start here

| Need | Go to |
|---|---|
| Run the application | [Run locally](#run-locally) |
| Run tests | [Test](#test) |
| Understand scope | [Data and scope](#data-and-scope) |
| See the portfolio context | [Developer portfolio](https://abla86.github.io/developer-portfolio/) |
| Inspect source | [GitHub repository](https://github.com/abla86/shift-competence-planner) |

## Demonstrated functionality

- Employee records with role, position percentage and competencies
- Day, evening and night shifts
- Minimum staffing requirements per shift
- Required competencies per shift
- Assignment of employees to shifts
- Detection of staffing gaps
- Detection of missing required competence
- Planned/worked-hour calculations
- Local JSON persistence
- CSV export
- Automated xUnit tests

## Run locally

```powershell
dotnet restore
dotnet run --project ShiftPlanner
```

## Test

```powershell
dotnet test
```

## Data and scope

The repository uses fictional sample data only. It is a demonstration and planning project, not a validated workforce-management or clinical decision-support system.

Do not commit patient information, confidential employee information, credentials or other sensitive data.

## Portfolio evidence

The project demonstrates C#/.NET application development, domain modelling, validation logic, local persistence, CSV export and automated testing.

## Status

This repository is part of the ABLA86 engineering portfolio. Current implementation status is represented by the code and repository history.

## Change-control audit

See [docs/REPOSITORY-CHANGE-AUDIT-2026-08-28.md](docs/REPOSITORY-CHANGE-AUDIT-2026-08-28.md) for the repository change-control and traceability record.
