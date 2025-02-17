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
# Results
![Screenshot 2025-02-17 at 5 09 29 PM](https://github.com/user-attachments/assets/6b3ad78a-c316-4d84-b76d-9e828727e53c)
![Screenshot 2025-02-17 at 5 09 11 PM](https://github.com/user-attachments/assets/cfc45957-331d-4372-9dc2-0217aaba868d)
![Screenshot 2025-02-17 at 5 08 48 PM](https://github.com/user-attachments/assets/8334b3a1-5904-4e65-8a83-c3fda65f2eee)


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
