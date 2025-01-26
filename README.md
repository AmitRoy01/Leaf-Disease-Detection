Here is a rewritten version of your **README.md** file:

---

# 🌿 **Agri Family - Plant Disease Detection & Cure**

Welcome to **Agri Family**, an innovative plant disease detection tool powered by machine learning! This project helps identify and diagnose plant leaf diseases by analyzing images of the leaves. Once a disease is detected, the system provides treatment recommendations to protect crops and ensure healthy growth. The tool is designed for farmers and agriculture experts, combining technology with agriculture for better crop management.

---

## 🚀 **Getting Started**

### **Prerequisites**

Before setting up the project, make sure you have **Python 3.8** or later installed on your system.

- Download Python from [here](https://www.python.org/downloads/)
- Verify the installation by running the following command in your terminal:
  ```bash
  python --version
  ```

### **Installation Steps**

Follow these steps to set up the project on your local machine:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/amitroy01/Leaf-Disease-Detection.git
   cd Leaf-Disease-Detection
   ```

2. **Set up a Python virtual environment**:
   ```bash
   python -m venv venv
   ```
   - For Windows: `venv\Scripts\activate`
   - For Linux/Mac: `source venv/bin/activate`

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the pre-trained model**:
   - Download the model file `plant_disease_model_1.pt` from [this link](https://drive.google.com/file/d/1JsUW38lrsyAYG0ORjqwQxQiRZpPIoc0c/view?usp=sharing).
   - Place the downloaded model in the `Flask Deployed App` directory.

5. **Run the application**:
   ```bash
   cd Flask\ Deployed\ App
   python app.py
   ```

6. **Access the application**:
   - Open your browser and go to `http://localhost:5000`
   - Start detecting plant diseases!

---

### **Optional: Explore the Model in Jupyter Notebook**
- Navigate to the `Model` directory.
- Open Jupyter Notebook to inspect the model's implementation and experiment with the code.

---

## 🔍 **Test Image Library**

- The `test_images` folder contains a curated collection of test images.
- Each image is labeled with its corresponding disease, allowing for easy verification of the model’s accuracy.
- Use this library to validate and test the model.

---

## 📸 **Application Previews**:

1. **Homepage**  
   ![Homepage](https://github.com/AmitRoy01/Leaf-Disease-Detection/blob/main/demo_images/1..PNG)

2. **Image Upload Interface**  
   ![Image Upload Interface](https://github.com/AmitRoy01/Leaf-Disease-Detection/blob/main/demo_images/2..PNG)

3. **Analysis Results**  
   ![Analysis Results](https://github.com/AmitRoy01/Leaf-Disease-Detection/blob/main/demo_images/2..PNG)

4. **Connect with Us**  
   ![Connect with Us](https://github.com/AmitRoy01/Leaf-Disease-Detection/blob/main/demo_images/2..PNG)

---

## 🤝 **Contributors**

- This project was developed by the **CTRL-ALT-DEFEAT TEAM** 🌱
  - [Amit Roy](https://github.com/AmitRoy01)
  - [Nasir Uddin](https://github.com/NasirUddin)
  - [Soumitra Paul ](https://github.com/soumitrapaul)

---

## 📝 **License**

This project is licensed under the MIT License. See the LICENSE file for more details.

---

### **Thank you for using the Agri Family Plant Disease Detection & Cure system!**
