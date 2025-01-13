# Project Name
Enhanced Facebook Social Network Analysis

## Description
This project analyzes and visualizes a social network graph built from Facebook data. The objective is to explore relationships between nodes (users) and edges (friendships), compute network metrics, and provide insightful visualizations of the network structure.

## Features
- Constructs a graph from a given dataset.
- Calculates important network metrics such as degree centrality and clustering coefficients.
- Visualizes the network with enhanced layouts for better comprehension.
- Outputs processed graph data and predictions.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/project-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd project-repo
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place the input files (`facebook_combined.txt.gz`, etc.) in the working directory.
2. Run the Jupyter notebook (`DM_Project.ipynb`) to process the data and generate outputs.

## Input Files
- `facebook_combined.txt.gz`: Contains the edge list for constructing the graph.
- Other supporting files (e.g., processed graphs, model files) should also be placed in the working directory.

## Output Files
- `processed_facebook_graph.gpickle`: A serialized graph for further analysis.
- `predicted_links.csv`: Contains predicted links based on the model.
- Visualizations: Saved as PNG or displayed inline.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`: For data manipulation.
  - `networkx`: For graph construction and analysis.
  - `matplotlib`: For visualization.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For questions or feedback, contact [your-email@example.com] or visit the [GitHub Issues](https://github.com/your-username/project-repo/issues).

---

**Note:** Ensure all input files are correctly placed, and dependencies are installed before running the project.

