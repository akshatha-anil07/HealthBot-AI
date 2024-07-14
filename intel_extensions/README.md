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

# Example Usage
![image](https://github.com/user-attachments/assets/1c17ca7a-6c33-445c-abd3-5f341a6d5588)
![image](https://github.com/user-attachments/assets/bf7b9198-a581-483a-b6a5-6d6abf7a1a74)
![image](https://github.com/user-attachments/assets/31b2c646-c67b-4587-b9e0-b6749efa4fc3)
