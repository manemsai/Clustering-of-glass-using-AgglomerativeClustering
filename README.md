# 🔍 Clustering of Glass using Agglomerative Clustering  

## 📌 Overview  
This project applies **Agglomerative Hierarchical Clustering** to classify different types of glass based on their chemical composition. The goal is to group similar glass samples together, helping in forensic and material science applications.  

## 🚀 Features  
- **Preprocessing of Glass Dataset**  
- **Agglomerative Clustering Implementation**  
- **Dendrogram Analysis for Optimal Clusters**  
- **Feature Scaling and Data Normalization**  
- **Visualization of Clusters**  



## 🔧 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/manemsai/Clustering-of-glass-using-AgglomerativeClustering.git
   cd Clustering-of-glass-using-AgglomerativeClustering
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

## 🛠 Usage  
1. **Run the clustering script:**  
   ```bash
   python clustering.py
   ```  
2. **Analyze the results:**  
   - Check **dendrogram plots** to determine the best number of clusters.  
   - Review **cluster assignments** for each glass type.  

## 📊 Dataset Details  
- The dataset contains chemical composition of different **types of glass**.  
- Features include **refractive index, sodium, magnesium, aluminum, silicon, potassium, calcium, barium, and iron content**.  
- The goal is to identify natural groupings among the glass samples.  

## 📈 Methodology  
1. **Data Preprocessing**: Handling missing values and scaling features.  
2. **Hierarchical Clustering**: Using **Ward’s linkage** for merging clusters.  
3. **Dendrogram Analysis**: Determining the optimal number of clusters.  
4. **Cluster Visualization**: Scatter plots and heatmaps for better insights.  

## 📖 Technologies Used  
- **Python**  
- **Scikit-Learn** (for clustering)  
- **Matplotlib & Seaborn** (for visualization)  
- **Pandas & NumPy** (for data handling)  
