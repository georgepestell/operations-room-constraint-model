# Constraint Modelling - The Operations Room

This project aims to solve "the operations room" problem class through the construction of constraint problem class using essence prime for the Savile Row constraint solver.

# System Requirements

- savilerow (constraint solver)

# Running Instructions

The savile row constraint solver is used to run the model on instances. Examples are defined in the `instances` directory.

```bash
savilerow <model> <instance> [-sat]
```

The `-sat` parameter enforces SAT encoding which can improve performance.
 
# Cleaning Log Files

A makefile `clean` command gives a quick and easy cleanup command for the savile row log/output files:

```bash
make clean
```

