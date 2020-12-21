# LAAD
LSTM-based Autoencoder Anomaly Detection (LAAD) is primarily developed to detect abnormal resting heart rate (RHR) during the Coronavirus (SARS-CoV-2) infectious period.. 


### Usage

```
python laad_covid19.py  --heart_rate data/ASFODQR_hr.csv --steps data/ASFODQR_steps.csv --myphd_id ASFODQR --symptom_date 2024-08-14
```



### LAAD architecture

<p align="center">
<img width="800" alt="LAAD" src="https://user-images.githubusercontent.com/3885659/102735228-b4583600-42f6-11eb-9c2f-5af2ae614dab.png">
</p>



### Results

<p align="middle">
<img width="333" alt="s_training" src="https://user-images.githubusercontent.com/3885659/102735598-bf5f9600-42f7-11eb-925d-7eb6c411c95a.png">
<img width="373" alt="s_pred_loss" src="https://user-images.githubusercontent.com/3885659/102735600-c25a8680-42f7-11eb-82a9-b23cc06965b6.png">
<br/><br/>
<img width="904" alt="s_results" src="https://user-images.githubusercontent.com/3885659/102735609-c5ee0d80-42f7-11eb-90ab-60010336e74d.png">
</p>

