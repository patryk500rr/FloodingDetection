# Flood Detection from Aerial Images (FloodNet Project)

This project uses a machine learning model to classify aerial images and predict whether a given area is **flooded** or **non-flooded**.

The model is implemented in **Python** using **TensorFlow** and **NumPy**, and is trained on real-world data from the **FloodNet** dataset.

---

## 🌊 Dataset Source

The dataset used in this project comes from **[FloodNet-Supervised_v1.0](https://github.com/BinaLab/FloodNet-Supervised_v1.0)**.

It contains aerial drone images showing flooded and non-flooded regions, along with corresponding color masks (segmentation labels).

📎 **A direct download link for the dataset can be found in the repository description.**

---

## 🧩 Project Structure

```
root
├── data
│   ├── colormasks   ← segmentation masks (Y)
│   └── supervised   ← aerial images (X)
└── src
    └── main.ipynb   ← main notebook with model code
```

---

## ⚙️ Requirements

- Python ≥ 3.9  
- TensorFlow  
- NumPy  
- Matplotlib  
- Pillow  
- scikit-learn  
- (optional) pandas

---

## 🚀 How to Run

1. Download the dataset from the link provided in the repository description.  
2. Place the `colormasks` and `supervised` folders inside the `data/` directory.  
3. Open `src/main.ipynb` in Jupyter Notebook or VS Code.  
4. Run all cells from top to bottom.  

The notebook will automatically load the dataset, preprocess the data, and train a classification model to detect flooded areas.

---

## 🧠 How It Works

1. Input images (`X`) come from drone aerial photography.  
2. Masks (`Y`) represent color-coded segmentation of flooded regions.  
3. The model learns to distinguish flooded vs. non-flooded areas based on image features.  
4. The output is a binary prediction indicating whether the area is flooded.

---

## 📄 License

Educational project — for learning and research purposes.  
The FloodNet dataset is owned and maintained by **BinaLab** (see link above).
