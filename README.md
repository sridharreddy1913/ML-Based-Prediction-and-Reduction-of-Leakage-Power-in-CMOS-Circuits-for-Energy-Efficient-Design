# ML-Based-Prediction-and-Reduction-of-Leakage-Power-in-CMOS-Circuits-for-Energy-Efficient-Design

As CMOS technology has been addressed at a low scale, leakage power has attained a
great concern disturbing the energy efficiency as well as thermal stability of electronic
systems. This project implements machine learning (ML) techniques to forecast leakage
power in CMOS layouts and thus reduce it by using various design parameters. Among all
the researched models the Random Forest and Gradient Boosting defined the highest level
of precision. The project aims to design a framework that shall enhance future CMOS circuit
designs for low power applications.
# How to Run
Open Google Colab or any other necessary platform, upload the .ipynb and .csv files, and run the code.


![Screenshot 2025-02-17 at 5 08 48 PM](https://github.com/user-attachments/assets/dce2a5ed-161d-406d-96b9-54fa0f3d7839)
![Screenshot 2025-02-17 at 5 09 11 PM](https://github.com/user-attachments/assets/d74c60f8-2a4a-4c3f-a3e5-3a653fb53f38)
![Screenshot 2025-02-17 at 5 09 29 PM](https://github.com/user-attachments/assets/d1df8338-acb2-456b-8062-77572874015d)


The implemented machine learning model effectively predicts leakage power in CMOS
circuits, with Random Forest and Gradient Boosting showing the best performance. The
feature importance analysis reveals that Length and Supply Voltage are the most critical
features affecting leakage power, which provides valuable insights for circuit design
optimization. The model’s accuracy is further supported by the close alignment in the actual
vs. predicted plot, low error metrics (MAE, RMSE), and the minimal, normally distributed
residuals. Some deviations at extreme values indicate areas for potential improvement, but
overall, the model is suitable for accurate leakage power prediction in CMOS circuits.
This detailed analysis illustrates that the model not only provides accurate predictions but
also offers insights into the primary factors influencing leakage power, which can be utilized
in future design and optimization efforts for energy-efficient CMOS circuits.
