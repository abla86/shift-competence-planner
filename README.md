# Shift & Competence Planner

A practical C#/.NET staffing tool for planning shifts and checking whether staffing and competence requirements are met.

## What it does

- Stores employees with role, position percentage and competencies
- Stores day/evening/night shifts
- Defines minimum staffing per shift
- Defines required competencies per shift
- Shows which employees are assigned
- Warns when staffing is below minimum
- Warns when required competence is missing
- Calculates worked/planned hours per employee
- Adds and removes employees from shifts
- Saves planner data locally as JSON
- Exports the shift plan to CSV
- Includes automated xUnit tests

## Run

```powershell
dotnet restore
dotnet run --project ShiftPlanner
```

## Test

```powershell
dotnet test
```

## Important

The included names and data are fictional sample data only.

Do not store real patient information in this project.
If used with real employee data at work, follow the employer's information-security and privacy requirements.
