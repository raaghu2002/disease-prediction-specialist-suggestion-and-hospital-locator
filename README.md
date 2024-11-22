

### **Disease Prediction, Specialist Suggestion, and Hospital Locator**

#### **Overview**
This application predicts diseases based on symptoms, suggests relevant specialists, and displays nearby hospitals using API integration. It leverages **Node.js**, **Python**, **EJS**, and **Machine Learning** for a seamless and user-friendly experience.

---

### **Features**
- **Disease Prediction:** Utilizes a trained DecisionTreeClassifier model.
- **Specialist Recommendation:** Suggests specialists based on the predicted disease.
- **Nearby Hospital Finder:** Integrates APIs to fetch hospital data.
- **Interactive Front-End:** Responsive design using EJS and CSS.

---

### **Project Structure**
```plaintext
project-folder/
│
├── index.js           # Main server file
├── predict.py         # Python script for ML predictions
├── Training.csv       # Dataset for training the ML model
├── filter.js          # API data filtering logic
├── run.js             # API integration logic
├── views/             # EJS templates for front-end
├── public/            # Static assets (images, CSS)
│   ├── images/        # Photos for the UI
│   ├── styles.css     # Styling
```

---

### **Requirements**
#### **Software**
- **Node.js** (Includes NPM)
- **Python 3**

#### **Libraries**
1. **Python**: `pandas`, `sklearn`
2. **Node.js**: `express`, `body-parser`, `axios`, `ejs`

---

### **Setup**
1. **Install Dependencies:**
   - Node.js & NPM: [Node.js Downloads](https://nodejs.org)
   - Python Libraries:  
     ```bash
     pip install pandas sklearn
     ```

2. **Clone Repository:**
   ```bash
   git clone https://github.com/your-username/project-name.git
   cd project-name
   ```

3. **Install Node.js Dependencies:**
   ```bash
   npm install
   ```

4. **Run the Application:**
   - Start Python Script:  
     ```bash
     python predict.py
     ```
   - Start Node.js Server:  
     ```bash
     node index.js
     ```

5. **Access the App:**  
   Navigate to [http://localhost:3000](http://localhost:3000).

---

### **Files Breakdown**
- **`index.js`**: Main server logic and routing.
- **`predict.py`**: Implements ML model for disease prediction.
- **`Training.csv`**: Dataset for training the ML model.
- **`filter.js`**: Filters API data for hospitals.
- **`run.js`**: Handles API calls for fetching hospital data.
- **`views/`**: Contains EJS templates for UI.
- **`public/`**: Static assets for styling and visuals.

---

### **Usage**
1. Enter symptoms into the app.
2. View predicted disease and suggested specialists.
3. See nearby hospitals.

---

### **Future Enhancements**
- Real-time hospital availability tracking.
- Enhanced prediction accuracy with advanced models.
- User authentication for personalized services.

