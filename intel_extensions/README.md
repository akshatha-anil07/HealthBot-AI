# To run this project, you need to install the following Python packages to enable Intel Extensions
- pip install --upgrade numpy
- pip uninstall scikit-learn-intelex daal4py -y
- pip install scikit-learn-intelex daal4py
- pip install modin[all]

# Usage
- To run the chatbot, execute the following command:
      python chatbot.py
- Intel extensions will be enables and a Local Ray instance will be started
- Follow the prompts to interact with the chatbot.
- Input the symptoms you are experiencing, and the chatbot will provide potential diagnoses along with precautionary measures.

## Why Intel Tools?
Intel extensions like Scikit-learnex and Modin significantly enhance performance compared to standard libraries, achieving speedups of 2-5 times for machine learning tasks, particularly with larger datasets. Modin’s ability to scale seamlessly from single machines to clusters allows for processing of datasets larger while reducing execution times by approximately 30% relative to standard Pandas library. This combination of rapid processing, scalability, and ease of use makes Intel extensions an ideal choice for applications that demand efficient and timely data insights.

# Example Usage
![image](https://github.com/user-attachments/assets/32b93b51-e419-434d-bde5-3f7390fb4a4a)

![image](https://github.com/user-attachments/assets/bf7b9198-a581-483a-b6a5-6d6abf7a1a74)
![image](https://github.com/user-attachments/assets/31b2c646-c67b-4587-b9e0-b6749efa4fc3)
