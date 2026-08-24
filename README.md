# School Districting Optimization with Gurobi

This repository contains a fully synthetic mixed-integer linear programming example for school districting and student assignment.

The model assigns neighborhood-grade groups to schools while minimizing weighted travel distance and respecting school capacity and grade availability.

## Scope

The project is designed for educational use in operations research, optimization, and mathematical programming courses.

All names, entities, schools, neighborhoods, and numerical data in this repository are fictional and created solely for teaching purposes.

## Model Structure

The model includes:

- neighborhood-grade student populations,
- school capacities by grade,
- school grade availability,
- neighborhood-to-school travel distances,
- binary assignment decisions,
- capacity constraints,
- exactly-one-school assignment constraints,
- grade eligibility restrictions.

The repository also includes an extended formulation with continuity preferences and explicit school-use variables.

## Requirements

- Python 3.10 or newer
- gurobipy
- A valid Gurobi license

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Run

```bash
python school_districting.py
```

## Files

- `school_districting.py`: baseline optimization model
- `school_districting_extended.py`: extended teaching model
- `requirements.txt`: Python dependency list
- `LICENSE`: non-commercial license terms
- `.gitignore`: standard Python exclusions

## License

This repository is provided for personal, academic, and educational use only. Commercial use is prohibited. See `LICENSE` for the complete terms.
