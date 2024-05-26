# segmeno-gen

Project Link - https://www.diagnosishimaqsad.co/
(will take few mins to load, plz wait)

demo - https://youtu.be/5i_QVYOBngU


**Leukemia Cell Segmentation** uses pre-trained neural networks to segment cancer cells and calculate the rate proliferation.


**Problem Solving and Applications of Leukemia Cell Segmentation
** Problem Statement: Leukemia, a type of blood cancer, involves the abnormal proliferation of white blood cells (WBCs). However, accurately quantifying the percentage of leukemia cells within a sample of WBCs is challenging due to their morphological similarities.

**Solution Offered:
**
Leukemia Cell Segmentation: The project offers a solution by employing advanced image processing and machine learning algorithms to segment leukemia cells from the rest of the WBC population in microscopic images.
Proliferation Rate Calculation: By determining the percentage of leukemia cells within the sample, the project facilitates the calculation of the rate of proliferation, a crucial metric in understanding disease progression and response to treatment.

**Applications:
**
Medical Diagnosis and Monitoring: Oncologists and hematologists can use this technology for accurate diagnosis and monitoring of leukemia patients. It provides insights into disease severity and progression over time, aiding in treatment planning and assessment.

Drug Development and Testing: Pharmaceutical companies can utilize this tool to evaluate the efficacy of anti-leukemic drugs. By measuring the impact of drugs on leukemia cell proliferation rates, researchers can identify promising candidates for further development.

Research and Academic Studies: Researchers in the field of oncology and hematology can leverage this technology to conduct studies on leukemia pathogenesis, biomarker discovery, and therapeutic interventions. It enhances the efficiency and accuracy of research efforts aimed at understanding and combating leukemia.

Patient Care and Prognosis: Healthcare providers can use the proliferation rate data derived from this project to tailor personalized treatment plans for leukemia patients. It enables more informed decision-making and improves patient outcomes by optimizing therapy strategies.

**Challenges Encountered and Solutions Implemented-
**
Limited Computing Resources: Initially, the project encountered limitations in computing resources, hindering the training of the SAM (Segment Anything Model) due to its computational intensity.

**Time-Consuming Model Training:
**
Despite utilizing GPU acceleration for model training, the process consumed a significant amount of time, affecting project timelines and productivity.
To mitigate this challenge, the team employed strategies like distributed training across multiple GPUs and implementing parallel processing techniques to expedite the training process. They also fine-tuned hyperparameters to optimize model convergence and performance.

**Minor Bugs on Localhost:**
While developing and testing the application on localhost, the team encountered minor bugs that affected the functionality and user experience.
Through diligent debugging and troubleshooting, the team identified and resolved the bugs, ensuring smooth operation of the application on the local development environment.
Deployment Issues with Render and GitHub:

When deploying the application using Render, which relies on GitHub repositories, the team faced challenges due to the large size of the model files (exceeding 400 MB), preventing successful uploading to GitHub.
Despite attempts to compress or split the model files, the limitations imposed by GitHub persisted, impeding the deployment process. Alternative hosting solutions or model compression techniques were explored, but a satisfactory resolution was not achieved within the project timeframe.






