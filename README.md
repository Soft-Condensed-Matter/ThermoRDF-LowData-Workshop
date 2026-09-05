# ThermoRDF Low-Data Workshop — Google Colab

Canonical student notebooks for the workshop

**From thermodynamic space to molecular structure: machine learning in the low-data regime of statistical physics.**

The student workflow is intentionally simple:

**Open in Colab → run the setup cell once → work through the physics.**

No terminal, local Python environment, or manual asset upload is required.

## Student notebooks

1. [Open Notebook 01 in Colab](https://colab.research.google.com/github/Soft-Condensed-Matter/ThermoRDF-LowData-Workshop/blob/main/notebooks/01_physical_problem_and_low_data_COLAB.ipynb)  
   **Physical problem and low data**

2. [Open Notebook 02 in Colab](https://colab.research.google.com/github/Soft-Condensed-Matter/ThermoRDF-LowData-Workshop/blob/main/notebooks/02_local_to_global_learning_COLAB.ipynb)  
   **From local interpolation to global learning**

3. [Open Notebook 03 in Colab](https://colab.research.google.com/github/Soft-Condensed-Matter/ThermoRDF-LowData-Workshop/blob/main/notebooks/03_nonlinear_learning_and_model_design_COLAB.ipynb)  
   **Nonlinear learning and model design**

4. [Open Notebook 04 in Colab](https://colab.research.google.com/github/Soft-Condensed-Matter/ThermoRDF-LowData-Workshop/blob/main/notebooks/04_physical_validation_COLAB.ipynb)  
   **Physical validation: challenge the frozen model**

## Colab setup

Each notebook contains the same hidden setup cell. On a fresh Colab runtime it automatically:

1. downloads `ThermoRDF-Colab-Assets.zip` from the workshop GitHub Release;
2. verifies SHA256 `2e75fd65ad39a9dec41f7b089c2aafe51a6bb14eeee049b055be8ea3953a7bea`;
3. extracts the teaching data and frozen model;
4. checks required Python packages;
5. loads the high-level workshop API.

The companion asset is pinned to the release:

`student-colab-v1.0-rc1`

This is a release-candidate distribution for clean-room testing before the student Colab v1.0 workflow is frozen.

## Runtime

A standard **CPU Colab runtime** is sufficient. GPU is not required.
