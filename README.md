# Computational Modeling of Cognitive Workload in Running-Specific Prosthesis Users

This repository contains the computational models, scripts, and data used in the study "Evaluating Cognitive and Physical Workload in Transtibial Amputee Runners Using Enhanced Running-Specific Prostheses on Inclines" [or your actual title].

## Repository Contents

### Cogulator Scripts (`cogulator-scripts/`)
- `current_prosthesis_model.txt`: CPM-GOMS model for baseline passive prosthesis
- `enhanced_prosthesis_model.txt`: CPM-GOMS model for enhanced powered prosthesis

### Operator Tables (`operator-tables/`)
- `task_operators.xlsx`: Complete list of perceptual, cognitive, and motor operators
- `timing_estimates.csv`: Time estimates for custom operators

### HPM-NL Code (`hpm-nl-code/`)
- `task_decomposition.py`: Natural language task decomposition framework
- `workload_calculations.py`: Cognitive workload estimation scripts

### Data (`data/`)
- `input_parameters.csv`: Simulation input parameters
- `simulation_results.csv`: Raw simulation outputs

## Requirements

- Cogulator (version X.X)
- Python 3.x
- [List any other dependencies]

## Usage

### Running CPM-GOMS Models
1. Install Cogulator from [link]
2. Open `cogulator-scripts/current_prosthesis_model.txt` in Cogulator
3. Run simulation

### Running HPM-NL Analysis
```bash
python hpm-nl-code/task_decomposition.py
```

## Citation

If you use these materials, please cite:

[Your citation information once published]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

[Your name and email]

## Acknowledgments

[Any acknowledgments]
