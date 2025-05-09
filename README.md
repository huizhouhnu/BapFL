We alert the FL community that even pFL methods with parameter decoupling are still highly vulnerable to backdoor attacks.
The resistance of pFL methods with parameter decoupling is attributed to the heterogeneous classifiers between
malicious clients and benign counterparts. We analyze two direct causes of the heterogeneous classifiers:
(1) data heterogeneity inherently exists among clients and (2) poisoning by malicious clients further exac
erbates the data heterogeneity. To address these issues, we propose a two-pronged attack method, BapFL,
which comprises two simple yet effective strategies: (1) poisoning only the feature encoder while keeping
the classifier fixed and (2) diversifying the classifier through noise introduction to simulate that of the benign 
clients. Extensive experiments on three benchmark datasets under varying conditions demonstrate the
effectiveness of our proposed attack. Additionally, we evaluate the effectiveness of six widely used defense
methods and find that BapFL still poses a significant threat even in the presence of the best defense, Multi-Krum.
![image](https://github.com/user-attachments/assets/ec7dc003-95fa-485b-bc2c-4f3a9317ef64)
![image](https://github.com/user-attachments/assets/898ecf65-7d37-42c7-9861-677ea5989e1e)

