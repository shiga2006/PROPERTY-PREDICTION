PROJECT TITLE: PROPERTY PREDICTION

This project aims to enhance mechanical properties—such as tensile strength, hardness, and compressive strength—of 3D-printed parts by predicting optimal print parameters using machine learning. The system is powered by a Random Forest model trained on real-world experimental data, making it a powerful tool for quality control and performance optimization in additive manufacturing.


🧩 Objective
Predict and optimize mechanical properties in additive manufacturing using machine learning.

Minimize trial-and-error by intelligently recommending parameters like layer height, infill density, infill pattern, and raster orientation.

Reduce material waste and manufacturing time.

Ensure high strength, precision, and durability for applications in aerospace, automotive, and medical industries.

Provide an educational tool for understanding relationships between 3D printing parameters and output properties.

🏗️ System Overview
Given a set of input parameters, the system predicts:

Tensile Strength: Resistance to breaking under tension.

Hardness: Resistance to surface deformation and wear.

Compressive Strength: Ability to withstand loads that reduce size.

The model learns from historical 3D printing data to deliver accurate predictions and recommend print settings to match user-specified property goals.

📥 Input Parameters


| Parameter              | Description                                                                   |
| ---------------------- | ----------------------------------------------------------------------------- |
| **Material**           | Material type used for printing (e.g., PLA, ABS). Each behaves differently.   |
| **Layer Height**       | Thickness of each printed layer. Smaller values = better surface finish.      |
| **Infill Density**     | Internal fill percentage of the model. Higher = stronger but slower prints.   |
| **Infill Pattern**     | Geometric pattern used inside the print (e.g., grid, cubic, triangle).        |
| **Raster Orientation** | Direction of material deposition, crucial for strength and stress resistance. |

⚙️Technologies Used
Python
Scikit-learn – ML model development (XGBoost)
Pandas, NumPy – Data preprocessing
Matplotlib/Seaborn – Visualization

🌍 Applications
High-performance industrial components

Medical implants with strict property requirements

Educational tool for students and researchers in additive manufacturing

Reducing errors and costs in rapid prototyping


Snapshots:

<img width="327" alt="image" src="https://github.com/user-attachments/assets/6fd8d544-fe9f-465c-ad66-b3d946c15739" />

<img width="168" alt="image" src="https://github.com/user-attachments/assets/c8abc56a-fd24-4e19-a9fb-856e3943e1a3" />

<img width="156" alt="image" src="https://github.com/user-attachments/assets/6541091b-0542-48d3-84ed-ddb68b57e387" />

<img width="163" alt="image" src="https://github.com/user-attachments/assets/ada3a40c-91ed-4135-bd78-de3ed3482283" />

<img width="207" alt="image" src="https://github.com/user-attachments/assets/df55d616-454e-4dc9-9372-8fd16350c34d" />

<img width="177" alt="image" src="https://github.com/user-attachments/assets/11de3d59-7826-497e-8db8-1ca3d1cf4025" />
