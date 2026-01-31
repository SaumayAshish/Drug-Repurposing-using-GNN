 Drug Repurposing Using Graph Neural Networks
An AI-Driven Framework for Novel Therapeutic Discovery

Overview
Drug development is costly, time-consuming, and high-risk. Drug repurposing offers a powerful alternative by identifying new therapeutic uses for existing drugs. This project implements an AI-driven drug repurposing framework using Graph Neural Networks (GNNs) applied to a large-scale biomedical knowledge graph.
The system leverages the Drug Repurposing Knowledge Graph (DRKG) and performs heterogeneous link prediction to discover potential drug–disease associations that can guide novel therapeutic discovery.

 Key Features

🔹 Large-scale biomedical knowledge graph processing

🔹 Heterogeneous GNN-based link prediction

🔹 Efficient handling of massive .tsv graph datasets

🔹 Negative sampling for robust training

🔹 End-to-end training, validation, and evaluation pipeline

🔹 Embedding visualization using t-SNE

🔹 Graph analysis and explainability with NetworkX

🔹 Fully Google Colab compatible

 Methodology

Data Loading

Streams DRKG triples efficiently to handle memory constraints

Filters biologically relevant relations for repurposing

Graph Construction

Builds heterogeneous graphs with drugs, diseases, and biological entities

Uses relation-aware edges for multi-type interactions

Model Architecture

Heterogeneous Graph Neural Network encoder

Dot-product decoder for link prediction

Binary classification objective (positive vs negative links)

Training & Evaluation

Train/validation/test splits

Negative sampling strategy

Final test evaluation metrics

Visualization & Interpretation

Node embedding visualization using t-SNE

Network-level insights via NetworkX

🛠 Tech Stack

Programming Language: Python

Deep Learning: PyTorch, PyTorch Geometric

Data Handling: Pandas, NumPy

Graph Processing: NetworkX

Visualization: Matplotlib, Seaborn

Dimensionality Reduction: scikit-learn (t-SNE)

📂 Project Structure
├── Drug_Repurposing_Using_Graph_Neural_Networks.ipynb
├── README.md
├── data/
│   └── drkg.tsv
├── outputs/
│   ├── embeddings/
│   └── visualizations/

▶️ How to Run
Option 1: Google Colab (Recommended)
Upload the notebook to Google Colab
Upload the drkg.tsv dataset to your Colab environment
Run all cells sequentially

Option 2: Local Environment
pip install torch torch-geometric pandas numpy matplotlib seaborn scikit-learn networkx

Then open and run the notebook: jupyter notebook

📊 Outputs

Predicted drug–disease associations

Learned node embeddings

Graph visualizations

Dimensionality-reduced embedding plots (t-SNE)

🎯 Applications

Drug repurposing research

Biomedical link prediction

Computational biology

AI-driven healthcare discovery

Academic projects & publications

📈 Future Enhancements

Integration with molecular fingerprints

Attention-based GNNs (HAN, R-GCN++)

Explainable AI (XAI) for prediction interpretation

Real-world clinical validation pipelines

API-based deployment using FastAPI

📜 License

This project is intended for research and educational purposes.
Please cite relevant datasets and frameworks when used in publications.

🤝 Acknowledgements

Drug Repurposing Knowledge Graph (DRKG)

PyTorch Geometric community

Open-source biomedical AI research

⭐ If You Find This Useful

Please ⭐ star the repository and share it with the research community!
