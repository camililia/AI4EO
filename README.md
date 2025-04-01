# AI4EO Project
This project focuses on predicting the arrival time and delays of trains, considering spatial and temporal features. The model is implemented using PyTorch Lightning for ease of training and management of complex workflows. The main objective is to predict delays based on the given train network data, weather conditions, and other related features. The model uses both spatial relationships (from a network graph) and temporal dependencies (from past delays and environmental factors) to predict delays for specific train lines.
## Data
The data used in this project consists of two main components:
1. Train Network Data: This contains the edge list of the train network (stations and their connections) and additional metadata like the distance between stations.
2. Station Features: This contains data for each station, including environmental factors like temperature, precipitation, and train delays. The data is structured in CSV format for each station.
