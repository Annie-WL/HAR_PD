# Human Activity Recognition in People with Parkinson’s Disease Using Dual Inertial Measurement Units

**Dataset:** Abbvie_Lab_Trials dataset 

**Sensors (Xsens):** 
- ID 00B4381A on the most affected wrist   
- ID 00B43876 on the most affected ankle
                 
**Activities:**
- M5 - ADL TASKS, filling a cup with water (x3)
- M6 - ADL TASKS, placing sheet in a binder (x3) (organizing 3 sheets in a folder)
- M7 - ADL TASKS, assembling nuts and bolts (x3) (90 seconds limit)
- M8 - ADL TASKS, typing on a keyboard
- M9 - ADL TASKS, folding a sheet (x2)
- M10 - 10M WALK TEST (WT) (x6)
- M11 - ADL TASKS, climbing up and down stairs/steps (x3)

**Each file is structured as:**
-	PacketCounter (to act as counter. Sampling rate is fixed at 40 Hz);
-	Acc_X, Acc_Y, Acc_Z as the tri-axial accelerometer data;
-	FreeAcc_X, FreeAcc_Y, FreeAcc_Z as the free acceleration data provided by the system;
-	Gyr_X, Gyr_Y, Gyr_Z as the tri-axial gyroscope data;
-	Q0, q1, q2, q3 are the four variables of the quaternion indicating the orientation of the IMU;
-	Roll, pitch, and yaw, are Euler angles obtained from the quaternions.

