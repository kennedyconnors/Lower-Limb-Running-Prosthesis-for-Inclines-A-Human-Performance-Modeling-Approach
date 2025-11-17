# Computational Modeling of Cognitive Workload in Running-Specific Prosthesis Users

This repository contains the computational models, scripts, and data used in the study "Lower-Limb-Running-Prosthesis-for-Inclines-A-Human-Performance-Modeling-Approach".

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
- Cogulator (version 4.5.2)
- GPT: HPM-NL (Junho Park)

## Usage

### Running CPM-GOMS Models
1. Install Cogulator from [https://cogulator.io/download.html]
2. Open `cogulator-scripts/current_prosthesis_model.txt` in Cogulator
3. Run simulation

### Running HPM-NL Analysis
The HPM-NL (Natural Language-based Human Performance Modeling) framework is implemented as a custom GPT in ChatGPT.
1. Go to ChatGPT: https://chat.openai.com/
2. Search for the custom GPT: `HPM-NL` by Junho Park
4. Upload the task decomposition file from `hpm-nl-code/task_decomposition.txt`
5. Follow the prompts to generate workload estimates

## Citation
If you use these materials, please cite:

[citation information once published]

## Contact
[Junho Park junho.park@ucalgary.ca]
[Regan Kane regan.kane@ucalgary.ca]
[Kennedy Connors kennedy.connors@ucalgary.ca]

## Acknowledgments

[Any acknowledgments]
