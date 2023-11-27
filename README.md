# Neuro-RPS Data Repository

## About the Repo
This repository, named neuro-rps-data, serves as the central hub for all data related to the Neuro-RPS project. Neuro-RPS is a machine learning classifier designed for Rock, Paper, Scissors, utilizing EMG data collected through a wristband. The repository also includes files used for data manipulation during the project.

## Data Storage
All data files are organized within the 'data' folder. The dataset comprises 20 .mat files, following the naming convention lsl_data_2023-# (where # ranges from 1 to 20).

## EMG Data Collection Hardware
The data collection process employed a wristband with similarities to a smartwatch. The wristband features a sensor equipped with 16 electrodes arranged in a 4 by 4 design beneath its surface. These electrodes excel in capturing surface signals, providing a real-time portrayal of intricate muscle movements.

Enabled with Bluetooth connectivity, the wristband wirelessly connects to a smartphone. The accompanying app visually displays live signals detected by the armband's sensors, offering dynamic insights into the collected data. The hardware provides access to additional data streams, including Analog to Digital Converter (ADC) data representing raw electrode signals, and Inertial Measurement Unit (IMU) data detailing the sensor's spatial position and accelerations.

## Data Collection Process
During data collection, the focus was on the ADC data stream, ensuring a meticulous representation of electrical activity at the electrode level.

### Initial Data Collection (lsl_data_2023-1 to lsl_data_2023-10)
The first ten files represent the initial round of data collection, with a primary goal of establishing a baseline dataset. The armband was positioned beneath the wrist area, with sensors in direct skin contact. Movements were confined to instances when the computer prompted a gesture, utilizing the same individual's non-dominant arm for all trials.

### Second Data Collection (lsl_data_2023-11 to lsl_data_2023-20)
The next ten files pertain to the second round of data collection, introducing a new participant using their dominant arm. The armband was strategically placed in the upper wrist area for continuous sensor-skin contact. Rigorous scrutiny of data analysis accounted for potential discrepancies influenced by these variations, ensuring the reliability of the collected data.

Feel free to explore the 'data' folder for detailed datasets and delve into the numbers behind our Neuro-RPS project.
