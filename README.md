# Python_Gurobi_Optimization_Scheduling
Python Gurobi Scheduling Optimization
Outcome:
"cell_type": "markdown",
   "id": "120d46e4",
   "metadata": {},
   "source": [
    "Restricted license - for non-production use only - expires 2025-11-24\n",
    "Gurobi Optimizer version 11.0.0 build v11.0.0rc2 (win64 - Windows 11.0 (22621.2))\n",
    "\n",
    "CPU model: 12th Gen Intel(R) Core(TM) i7-12800HX, instruction set [SSE2|AVX|AVX2]\n",
    "Thread count: 16 physical cores, 24 logical processors, using up to 24 threads\n",
    "\n",
    "Optimize a model with 1605 rows, 650 columns and 4004 nonzeros\n",
    "Model fingerprint: 0x79e70a77\n",
    "Variable types: 26 continuous, 624 integer (624 binary)\n",
    "Coefficient statistics:\n",
    "  Matrix range     [1e+00, 5e+00]\n",
    "  Objective range  [1e+00, 1e+00]\n",
    "  Bounds range     [1e+00, 1e+00]\n",
    "  RHS range        [1e+00, 5e+00]\n",
    "Presolve removed 1295 rows and 179 columns\n",
    "Presolve time: 0.01s\n",
    "Presolved: 310 rows, 471 columns, 1616 nonzeros\n",
    "Variable types: 0 continuous, 471 integer (471 binary)\n",
    "Found heuristic solution: objective 1.0000000\n",
    "Found heuristic solution: objective 0.0000000\n",
    "\n",
    "Explored 0 nodes (0 simplex iterations) in 0.01 seconds (0.01 work units)\n",
    "Thread count was 24 (of 24 available processors)\n",
    "\n",
    "Solution count 2: 0 1 \n",
    "\n",
    "Optimal solution found (tolerance 1.00e-04)\n",
    "Best objective 0.000000000000e+00, best bound 0.000000000000e+00, gap 0.0000%\n",
    "Optimal solution found.\n",
    "\n",
    "Pediatrician Shift Assignments:\n",
    "Shift 1 assigned to Pediatrician 4\n",
    "Shift 2 assigned to Pediatrician 13\n",
    "Shift 3 assigned to Pediatrician 10\n",
    "Shift 4 assigned to Pediatrician 7\n",
    "Shift 5 assigned to Pediatrician 6\n",
    "Shift 6 assigned to Pediatrician 1\n",
    "Shift 7 assigned to Pediatrician 9\n",
    "Shift 8 assigned to Pediatrician 10\n",
    "Shift 9 assigned to Pediatrician 4\n",
    "Shift 10 assigned to Pediatrician 2\n",
    "Shift 11 assigned to Pediatrician 1\n",
    "Shift 12 assigned to Pediatrician 10\n",
    "Shift 13 assigned to Pediatrician 9\n",
    "Shift 14 assigned to Pediatrician 2\n",
    "Shift 15 assigned to Pediatrician 6\n",
    "Shift 16 assigned to Pediatrician 11\n",
    "Shift 17 assigned to Pediatrician 12\n",
    "Shift 18 assigned to Pediatrician 4\n",
    "Shift 19 assigned to Pediatrician 3\n",
    "Shift 20 assigned to Pediatrician 13\n",
    "Shift 21 assigned to Pediatrician 3\n",
    "Shift 22 assigned to Pediatrician 7\n",
    "Shift 23 assigned to Pediatrician 9\n",
    "Shift 24 assigned to Pediatrician 13\n",
    "Shift 25 assigned to Pediatrician 5\n",
    "Shift 26 assigned to Pediatrician 12\n",
    "Shift 27 assigned to Pediatrician 7\n",
    "Shift 28 assigned to Pediatrician 5\n",
    "Shift 29 assigned to Pediatrician 8\n",
    "Shift 30 assigned to Pediatrician 9\n",
    "Shift 31 assigned to Pediatrician 11\n",
    "Shift 32 assigned to Pediatrician 8\n",
    "Shift 33 assigned to Pediatrician 5\n",
    "Shift 34 assigned to Pediatrician 11\n",
    "Shift 35 assigned to Pediatrician 3\n",
    "Shift 36 assigned to Pediatrician 9\n",
    "Shift 37 assigned to Pediatrician 1\n",
    "Shift 38 assigned to Pediatrician 8\n",
    "Shift 39 assigned to Pediatrician 1\n",
    "Shift 40 assigned to Pediatrician 11\n",
    "Shift 41 assigned to Pediatrician 3\n",
    "Shift 42 assigned to Pediatrician 1\n",
    "\n",
    "Pediatrician of the Week Assignments:\n",
    "Week 1: Pediatrician 10 is the POW\n",
    "Week 2: Pediatrician 12 is the POW\n",
    "Week 3: Pediatrician 11 is the POW"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
