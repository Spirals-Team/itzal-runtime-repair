# BikiniRepair


This is the repository of BikiniRepair.

BikiniRepair is a system that generates patches and validate them in production developed at Inria Lille.

This code is research code, released under the GPL licence.


## Getting Started


### Run the evaluation

1. Gets the Shadow Dataset: https://github.com/Spirals-Team/shadow-dataset
2. Builds each docker image on your system
3. Start BikiniRepair `java -cp target/classes:target/test-classes fr.inria.lille.spirals.bikinirepair.Evaluation` 
4. BikiniRepair is now available at http://localhost:8080
5. Use the python script in the Dataset to reproduce the failure
