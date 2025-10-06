 🌳 Task 5: Decision Trees and Random Forests

 📌 Objective  
The goal of this task is to understand and implement tree-based machine learning models for both classification and regression.  
We focus on training Decision Trees, visualizing them, analyzing overfitting, and improving performance using Random Forests.

 🛠 Tools & Libraries  
- 🐍 Python  
- 📚 Scikit-learn (sklearn)  
- 📊 Matplotlib
- 🧾 Pandas

 🧪 Steps Performed  

1. ✅ Loaded Dataset  
   - Used the Breast Cancer dataset from `sklearn.datasets` for classification tasks.

2. 🌲 Trained a Decision Tree Classifier  
   - Built a basic model using `DecisionTreeClassifier`.  
   - Visualized the tree structure to understand decision splits.

3. ✂️ Analyzed Overfitting
   - Compared training and testing accuracy.  
   - Controlled complexity using parameters like `max_depth`.

4. 🌿 Trained a Random Forest Model 
   - Implemented `RandomForestClassifier` for better accuracy and generalization.  
   - Compared its performance with the single decision tree.

5. 🧠 Interpreted Feature Importances 
   - Identified the top important features that impact predictions.

6. 🔁 Evaluated Using Cross-Validation  
   - Performed 5-fold cross-validation for more reliable accuracy results.
     
 📈 Results  

- 🌲 Decision Tree showed high training accuracy but slightly lower test accuracy → **sign of overfitting**.  
- ✂️ Pruned trees (limited depth) improved model generalization.  
- 🌿 Random Forest gave better accuracy and stability by combining multiple trees.  
- 📊 Feature Importance*highlighted the key predictors in the dataset.

 📝 Key Learnings  

- ✅ Decision Trees are simple and easy to interpret.  
- ✨ Controlling tree depth helps prevent overfitting.  
- 🌿 Random Forest is a powerful ensemble method that improves accuracy.  
- 📌 Cross-validation gives more trustworthy evaluation metrics.
