### GEN AI
Generative AI (GenAI) creates new content—such as text, images, code, or music—by learning patterns from existing data.
In contrast, Non-Generative (Traditional) AI analyzes data, recognizes patterns, and makes predictions or decisions based on predefined rules.
<img width="649" height="268" alt="image" src="https://github.com/user-attachments/assets/826b2b36-006c-4e62-a2ae-6b6f60c56d91" />

### Learning Gen Ai Concepts Wise:
#### PHASE 1: AI & ML Fundamentals
#### PHASE 2: Neural Networks & NLP Basics
#### PHASE 3: Transformers & LLMs
#### PHASE 4: Generative AI Core Concepts
#### PHASE 5: Embeddings & Vector Databases
#### PHASE 6: RAG (Retrieval Augmented Generation)
#### PHASE 7: Prompt Engineering
#### PHASE 8: Fine-Tuning & Model Customization
#### PHASE 9: Multimodal AI
#### PHASE 10: Deployment & Cloud GenAI

-------------------------------------------------------------------------------------------------------------------------------------------

### AI & ML Fundamentals:
#### AI(Artificial Intelligence):
Artificial Intelligence is the ability of machines to simulate human intelligence.
 That includes:
* Learning
* Reasoning
* Problem solving
* Understanding language
* Perception (vision/speech)

<img width="380" height="355" alt="image" src="https://github.com/user-attachments/assets/8ed7fb33-0e37-49e4-a661-89e014b8cc83" />

AI is based on core concepts and technologies that enable machines to learn, reason and make decisions on their own.
1.Machine Learning

2.Generative AI

3.Natural Language Processing

4.Expert Systems.

<img width="692" height="348" alt="image" src="https://github.com/user-attachments/assets/8482c558-5b06-41fb-b944-f459c33fe986" />

#### Types of AI are divided into two category
1.Based on Capabilities
2.Based on Functionality

-----------------------------------------------------------------------------------------------------------------------------

### Based on Capabilities: This classification defines how human-like the AI is, focusing on its ability to reason and perform tasks. 
1️⃣ Narrow AI (Weak AI):
* Narrow AI is a type of AI Which is able to perform a dedicated task with intelligence.The most common and currently available AI is Narrow AI in the world of AI.
* Narrow AI cannot perform beyond its field or limitations, as it is only trained for one specific task. Hence it is also termed as weak AI. Narrow AI can fail in unpredictable ways if it goes beyond its limits.
* Ex: Apple Siris, IBM's Watson supercomputer, ChatGPT, AI are playing chess, purchasing suggestions on e-commerce site, self-driving cars, speech recognition and image recognition. 

2️⃣ General AI (AGI)
* General AI is a type of intelligence which could perform any intellectual task with efficiency like a human.
* The idea behind the general AI to make such a system which could be smarter and think like a human by its own.
* Currently, Not yet exist. On researching.

3️⃣ Super AI
* Smarter than humans in all aspects. Means level of Intelligence of systems at which machines could surpass human intelligence, and can perform any task better than human with cognitive properties. It iis an outcome of general AI.
* Completely hypothetical,including creativity and social skills.
-----------------------------------------------------------------------------------------------------------------------------
### Based on Functionality: AI can be classified based on functionality (how it behaves and what it can do) into 4 main types.
1️⃣ Reactive Machines
* Purely reactive machines are the most basic types of AI.
* Such AI systems do not store memories or past experiences for future acrions.
* These machines only focus on current scenarios and react on it as per possible best acrion.
  
🔹 Characteristics:
✔ No memory
✔ No learning
✔ No self-awareness
✔ Respond only to present data

🔹 Example
IBM Deep Blue
It defeated:
Garry Kasparov
Deep Blue:
Could analyze chess moves
Could not remember previous games
Could not improve by learning

🔹 Real-Life Example
A simple chatbot that:
Matches keywords
Gives predefined answers
Does not remember conversation

2️⃣ Limited Memory AI
* Limitedt memory machines can store past experiences or some data for a short period of time.
* These machines can use stored data for a limited time period only.
  
🔹 Characteristics
✔ Uses historical data
✔ Improves over time
✔ Learns from experience
✔ Not self-aware

🔹 Examples
Self-driving cars, Recommendation systems, Image recognition models, Most ML & Deep Learning models
Examples:
Tesla Autopilot, ChatGPT
They:
Use past data for predictions, Improve with training, But don’t have emotions or awareness

3️⃣ Theory of Mind AI
* Theory of Mind AI should understand the human emotions, people, beliefs and be able to interact socially like humans.
* This type does NOT exist yet.
  
🔹 What It Would Do
✔ Recognize emotional state
✔ Adapt behavior accordingly
✔ Understand social context.

Example (future):
Robot that understands if you are sad and responds emotionally.
🔹 Current Status
Still under research.
No fully developed system exists.

4️⃣ Self-Aware AI
* Self-awareness AI is the future of Aritifical Intelligence. These machines will be super intelligent, and will have their own consciousness, sentiments and self-awareness.
* These machines will be smarter than human mind.
* Slef-Awareness AI does not exist in reality still and it is a hypothetical concept.
  
🔹 Characteristics
✔ Consciousness
✔ Self-reflection
✔ Personal goals

🔹 Reality
Does NOT exist.
Only theoretical and seen in movies.
Examples in fiction:
Ultron
Jarvis

---------------------------------------------------------------------------------------------------------------------------------------------------------
### ML(Machine Learning):
Machine learning is a branch of Artificial Intelligence that focuses on developing models and algorithms that let computers learn from data without being explicitly programmed for every task.
In simple words, ML teaches systems to think and understand like humans by learning from the data.

<img width="624" height="273" alt="image" src="https://github.com/user-attachments/assets/eeb7dcad-0c39-4bf4-ae62-a5159bd42c1b" />


ML models:

Take input data

Learn patterns

Make predictions

Example:
Input: Past house prices
Output: Predicted new house price

<img width="1020" height="461" alt="image" src="https://github.com/user-attachments/assets/2f4b8cc2-e539-4d24-8400-c5a778c92f99" />

#### Types of Machine Learning
1.Supervised Learning
2.Unsupervised Learning
3.Reinforcement Learning
4.Semi-Supervised Learning
5.Self-Supervised Learning

#### 1.Supervised Learning:
Trains models on labeled data to predict or classify new, unseen data.
Supervised learning algorithms are generally categorized into two main types:

##### 1.Classification: where the goal is to predict discrete labels or categories 

Example:

Spam / Not Spam

Fraud / Not Fraud

Disease / No Disease

Algorithms:

##### Logistic Regression:
Logistic Regression predicts probability of a category.

Even though the name says "regression", it is used for classification.

It gives output between 0 and 1.

Example:

0.9 → Likely spam

0.1 → Not spam

*Uses a Sigmoid function to convert output into probability.

##### Decision Tree:

Decision Tree makes decisions using if-else conditions like a flowchart.
If:

Age > 18 → Adult

Age ≤ 18 → Minor

Tree structure:

<img width="234" height="139" alt="image" src="https://github.com/user-attachments/assets/7dcc106c-fc41-4787-98fe-0321b96d7b3b" />



##### Random Forest:
Random Forest is a group of many Decision Trees working together.
It combines their answers to give better prediction.

Example:

If 100 trees vote:

70 say Spam

30 say Not Spam

Final answer → Spam

##### KNN(K-Nearest Neighbors):
KNN predicts output based on closest data points.

It checks:
“Which data points are nearest to this new point?”
Example:

If most nearby neighbors are:

3 red balls

1 blue ball

New point → Red

##### SVM(Suport Vector Machine):
SVM finds the best boundary line that separates categories.

It tries to maximize distance between categories.
Example:

Imagine:

Red dots on one side

Blue dots on other side

SVM draws the best line between them.

##### 2.Regression: where the aim is to predict continuous numerical values.
Example:

House price

Temperature

Salary

Algorithm examples:

##### Linear Regression:
Linear Regression predicts a number using a straight-line relationship between input and output.
It tries to fit the best straight line through data points.
##### y=mx+b
Where:

x = input (e.g., house size)

y = output (price)

m = slope

b = intercept

When to Use:

✔ Relationship is roughly straight line
✔ Simple prediction problems

##### Polynomial Regression:
Polynomial Regression predicts a number using a curved relationship instead of a straight line.
It is like an advanced version of Linear Regression.
##### y = ax² + bx + c

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------






