While looking for a senior data scientist/ML engineer position this summer, I had many behavioral and technical interviews with such companies as eBay, Uber, TomTom, Booking.com, Nebius and, of course, ING. Here are my takeaways that can help especially those who is just starting looking for a job in industry (e.g., after finishing their PhD). Many thanks to Yury Kashnitsky, Ph.D. for recommending some of the resources mentioned below.

Behavioral: learn the STAR method and prepare a few stories using it. As a resource, I used the following book but any other resources are fine as well: Martha Gage, The Power of STAR Method: How to Succeed at Behavioral Job Interview (2022).

Coding:
- Surprisingly, many companies still expect you to solve leetcode-type tasks, even though they are marginally (if at all) relevant to your future responsibilities. So practice those, preferably, on the intermediate level. Pay attention to the algorithmic side of each problem, try to solve it as efficiently as possible in terms of both space and time. Always try to find a linear or O(n*log(n)) solution in terms of time complexity.
- Refresh advanced Python, e.g., decorators, abc and typing packages, list comprehension, map and reduce operators, etc. For this, I found this collection of learning materials useful: https://lnkd.in/enFU3WJs.

Classical ML:
- Definitely refresh the basics, even if you think you know them: discriminative vs. generative models, gradient descent, p-value, standard metrics (accuracy, precision, recall, F1, ROC, AUC).
- Refresh your knowledge of the scikit-learn and pandas packages.
- Practice doing some data analysis and modelling tasks.
- Ideally (I did not do this myself, but I wish I had time for that), implement some basic ML models from scratch, e.g., linear regression, classification, etc.

LLM/GenAI:
- Again, refresh the basics. I found this course from deeplearning.ai useful: https://lnkd.in/eDN2H5nq.
- Learn and really understand the Transformer architecture: read the original paper (https://lnkd.in/eSFxZMK5) and, of course, the awesome visualizations by Jay Alammar (https://lnkd.in/ew4C65xb).
- Understand how attention is computed using matrices Q, K, V.
- Look into prompt engineering techniques.
- Refresh evaluation basics, e.g., BLEU and ROUGE.
- It is a plus, if you know about guardrails, distillation, quantization and other advanced topics.

Additional topics as a plus:
- MLOps: CI/CD, GCP, Azure, AWS, Terraform.
- System design: Learn basic concepts, e.g., functional vs. non-functional requirements, load balancer, queue, etc. Practice by creating designs for a few systems. I checked several resources and mostly used these two: https://lnkd.in/e_gjFPdW and https://lnkd.in/e6R4Md4R.