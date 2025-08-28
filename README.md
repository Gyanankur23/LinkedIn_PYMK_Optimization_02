# LinkedIn_PYMK_Optimization_02 CaseCraft Analytics Project Sprint Project 2

## 🔍 Overview  
This project simulates LinkedIn’s “People You May Know” (PYMK) feature using graph-based link prediction. It builds a synthetic social graph, applies network analysis, and uses common neighbors and Jaccard similarity to suggest potential connections.

## 🎯 Objective  
To identify likely future connections in a simulated LinkedIn-style network using graph theory and link prediction techniques.

## 📊 Graph Setup  
- 30 synthetic users (`U1` to `U30`)  
- Randomized connections with 10% edge probability  
- Undirected graph using NetworkX

## 📈 Visual Explorations  
- Network graph layout using spring embedding  
- Degree distribution histogram  
- Top 10 users by degree centrality  
- Heatmap of predicted links based on Jaccard similarity

## 🧠 Link Prediction Techniques  
- **Common Neighbors**: Counts mutual friends between unconnected users  
- **Jaccard Similarity**: Measures neighbor overlap between user pairs  
- **Top Suggestions**: Ranked list of high-potential connections

## 📊 Key Visuals  
- Social graph visualization  
- Degree distribution histogram  
- Centrality bar chart  
- Jaccard similarity heatmap

## 🧠 Key Insights  
1. **Network Structure**: Sparse but connected graph with clear central hubs  
2. **Influencer Identification**: Degree centrality highlights users with high influence  
3. **Link Prediction**: Common neighbors and Jaccard similarity surface interpretable suggestions  
4. **Visualization Utility**: Charts and heatmaps reveal density, influence, and connection potential  
5. **Business Implication**: Mirrors real-world PYMK logic; scalable to larger graphs using embeddings or ML

## ✅ Final Conclusion  
This project demonstrates how graph theory and link prediction can power scalable, interpretable recommendation systems. By simulating a social graph and applying intuitive scoring techniques, it offers a modular blueprint for personalized connection suggestions in professional networks.