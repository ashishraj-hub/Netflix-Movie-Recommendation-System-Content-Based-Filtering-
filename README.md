# 🎬 Netflix Movie Recommendation System (Content-Based Filtering)

---

## 📌 Overview
This project implements a **Content-Based Filtering Recommendation System** for movies on Netflix.  
By analyzing movie metadata such as **genres, cast, crew, and descriptions**, the system recommends movies that are similar to a user’s preferences.  

The project is designed to demonstrate practical application of **Natural Language Processing (NLP)** and **machine learning techniques** in building personalized recommendation engines.

---

## 🎯 Objectives
- Preprocess and clean movie dataset  
- Extract meaningful features (genres, keywords, cast, crew)  
- Apply **TF-IDF Vectorization** and **Cosine Similarity** for content-based filtering  
- Build a recommendation function that suggests movies similar to a given title  
- Document workflow and results in Jupyter Notebook & Project Report  

---

## 📂 Repository Structure

├── Major Project 2.ipynb               # Jupyter Notebook with full workflow
├── Project Report.pdf                  # Detailed project report
├── cleaned_dataset.csv                # Preprocessed dataset
├── LICENSE                            # License file
└── README.md                           # Project documentation


---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** pandas, numpy, scikit-learn, nltk, matplotlib, seaborn  
- **Techniques:** TF-IDF Vectorization, Cosine Similarity, NLP preprocessing  
- **Tools:** Jupyter Notebook, GitHub  

---

## 📊 Workflow
1. **Data Preprocessing**  
   - Handle missing values  
   - Clean and normalize text data  
   - Extract features: genres, keywords, cast, crew  

2. **Feature Engineering**  
   - Apply **TF-IDF Vectorization** on movie descriptions  
   - Create combined feature vectors  

3. **Similarity Computation**  
   - Use **Cosine Similarity** to measure closeness between movies  

4. **Recommendation Function**  
   - Input: Movie title  
   - Output: Top N similar movies  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ashishraj-hub/Netflix-Movie-Recommendation-System-Content-Based-Filtering.git
   ``` 
2.Navigate to the project folder:
  ```bash
cd Netflix-Movie-Recommendation-System-Content-Based-Filtering
 ```
3.Install dependencies:
  ```bash
  pip install -r requirements.txt
```
4.Open the Jupyter Notebook:
```bash
jupyter notebook Major\ Project\ 2.ipynb
 ```

---

## 📈 Results

- The system successfully recommends movies based on content similarity.

- Example: Inputting "Inception" returns movies with similar genres, themes, and cast.

---

## 📜 License

- This project is licensed under the MIT License – see the LICENSE file for details.

---

# 🙌 Acknowledgements

- Dataset Source: Kaggle
- Libraries: Scikit-Learn, Pandas, NumPy

---

## 👤 Author

**Ashish Raj**

---

## 🤝 Connect With Me

If you found this project useful, interesting, or inspiring — let's connect!

| Platform | Link |
|----|----|
| 💼 LinkedIn | [Ashish Raj](https://www.linkedin.com/in/ashish-raj-ashishraj/) |
| 🐙 GitHub | [Ashish Raj](https://github.com/ashishraj-hub)  |

---

## ⭐ Support This Project

If this README or project helped you:
- **Star** ⭐ this repository
- **Fork** 🍴 it and build your own version
- **Share** it with someone who is learning Data Science or AI/ML

---
