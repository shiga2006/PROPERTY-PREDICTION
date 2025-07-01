PROJECT TITLE: Intelligent Forecasting in 3D Printing
(A Machine Learning-powered solution to predict and enhance mechanical properties in additive manufacturing.)

What if you could print stronger, better 3D parts without all the guesswork?
This project helps you do just that—using machine learning to predict mechanical properties like tensile strength, hardness, and compressive strength, based on how you set your print parameters.


🎯 Why This Matters
3D printing is powerful—but tuning it for strength and precision often feels like trial and error. Our system learns from real-world data to take the guesswork out of the equation and helps you:

🔍 Predict how your 3D part will perform before you even hit “print”

🎯 Get smart suggestions for layer height, infill, and other settings

♻️ Reduce material waste and printing time

🛠️ Build parts with better strength, durability, and accuracy

📚 Understand how printing parameters really affect your results

 How It Works
We’ve trained a Random Forest model (with some help from XGBoost) on real experimental data. Feed it your desired print settings, and it predicts:
|    Property              | What it Tells You                           |
| ------------------------ | ------------------------------------------- |
| **Tensile Strength**     | Will it resist breaking when pulled?        |
| **Hardness**             | Can it handle wear and tear on the surface? |
| **Compressive Strength** | Will it stand strong under pressure?        |


Input Parameters
Here’s what the system needs from you:
| 🔧 Parameter           | 📖 Description                                        |
| ---------------------- | ----------------------------------------------------- |
| **Material**           | PLA, ABS, etc.—each behaves differently.              |
| **Layer Height**       | Smaller = smoother finish, but longer print time.     |
| **Infill Density**     | How solid the part is on the inside. More = stronger. |
| **Infill Pattern**     | Grid, cubic, triangle—affects strength and speed.     |
| **Raster Orientation** | Direction of printing—key to stress resistance.       |

⚙️ Tech Stack
Python for the core logic

Scikit-learn, XGBoost for model training

Pandas, NumPy for data preprocessing

Matplotlib, Seaborn for visual insights

Real-World Impact
This isn’t just theory. It’s useful for:

🏭 Industrial Parts – Stronger, optimized prints for real use

🏥 Medical Devices – When failure is not an option

🧪 Education & Research – Hands-on learning about materials science

🚀 Prototyping – Cut down on cost and time while increasing accuracy


Snapshots:

<img width="327" alt="image" src="https://github.com/user-attachments/assets/6fd8d544-fe9f-465c-ad66-b3d946c15739" />



<img width="168" alt="image" src="https://github.com/user-attachments/assets/c8abc56a-fd24-4e19-a9fb-856e3943e1a3" />



<img width="156" alt="image" src="https://github.com/user-attachments/assets/6541091b-0542-48d3-84ed-ddb68b57e387" />


<img width="163" alt="image" src="https://github.com/user-attachments/assets/ada3a40c-91ed-4135-bd78-de3ed3482283" />


<img width="207" alt="image" src="https://github.com/user-attachments/assets/df55d616-454e-4dc9-9372-8fd16350c34d" />


<img width="177" alt="image" src="https://github.com/user-attachments/assets/11de3d59-7826-497e-8db8-1ca3d1cf4025" />

🙌 Let’s Make 3D Printing Smarter
Whether you're an engineer, student, researcher, or just a 3D printing enthusiast—this tool helps you make better prints, faster. All with the power of data.
