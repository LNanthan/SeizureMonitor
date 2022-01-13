Seizure Monitor
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Juvenile epilepsy is the most common neurological disease in children. These seizures often occur multiple times at night and tracking them in hospitals is especially
difficult during the COVID-19 pandemic.  Moreover, some of these seizures require caregivers to provide immediate medical attention. Due to this, we devloped an algorithim that continously uses brachial bicep EMG sensor data as input to provide constant seizure monitoring. 

Our program detects a generalized tonic-clonic seizure by comparing the number of half cycles per second to a threshold frequency indicating the occurence of the tonic phase (sustained muscle contractions). The program then tracks the tonic phase and looks for the start of the clonic phase (repeated & rapid muscle contractions) by comparing to muscle relaxtion periods to a minimum threshold. Since seizures longer than 5 minutes are medical emergencies, the device times the seizure and alerts the parents.

Also, having a detailed log of the electrical activity can improve diagnosis and treatment, so the program writes relevant data to a file. 
