# ZenChat : Your Oasis for Mental Wellness (Mental-Health-Therapist-ChatBot)
Upgrade your conversations with our smart chatbot, powered by NLP and Machine Learning. It adapts, understands context, and gives intelligent responses. Train it easily with a curated dataset and enjoy seamless interaction through a user-friendly interface.

## Overview

This project introduces an advanced chatbot system designed to enhance human-computer interactions using cutting-edge Natural Language Processing (NLP) and Machine Learning techniques. Unlike conventional chatbots, this system goes beyond scripted responses, providing users with intuitive, informative, and enjoyable conversational experiences. The primary focus lies in dynamic adaptation and context awareness, enabling the chatbot to generate coherent, contextually relevant responses.

## Key Features

### Architecture

The system adopts a fusion of foundational NLP techniques and advanced deep learning principles. At its core is a meticulously designed sequential neural network model capable of comprehending and responding intelligently to user queries.

### Data Collection

The system relies on a carefully curated dataset (`Intents.json`) containing predefined patterns associated with specific tags and responses. Styling and presentation aspects are managed by `Style.css`, and the front-end interface is implemented using `Index.html`.

### Preprocessing

The preprocessing pipeline involves tokenization and lemmatization to break down sentences into individual words and reduce them to their base or root form, crucial for creating a training dataset used to train the chatbot.

### Model Architecture

The sequential model, created using the Keras library, incorporates dense layers, dropout layers, and softmax activation to ensure the generation of contextually relevant responses. The model is optimized using Stochastic Gradient Descent (SGD) with Nesterov accelerated gradient and trained using categorical crossentropy loss.

### Optimization and Compilation

The model's parameters are optimized during training using SGD, and categorical crossentropy loss guides the optimization process. The model is prepared for training by specifying the optimizer, loss function, and evaluation metric.

### User Interaction

The front-end interface (`Index.html`) provides a user-friendly platform for interacting with the chatbot, displaying chat history, input/output sections, and ensuring a seamless conversational experience.

## Repository Structure

- `data/`: Contains the dataset (`Intents.json`) and related files.
- `src/`: Includes the source code, including preprocessing scripts (`Training.ipynb` and `Training.py`) and the main model architecture (`Model.py`).
- `frontend/`: Manages the front-end interface (`Index.html` and `Style.css`).
- `docs/`: Documentation files and project-related resources.
- `requirements.txt`: Lists the dependencies required to run the project.

## Getting Started

1. Clone this repository

```
git clone https://github.com/Tulika-aa3696/Mental-Health-Therapist-ChatBot.git
```

2. Create and activate virtual environment 

```
python -m venv venv
```
on Linux system
```
source venv/bin/activate
```
on Windows system
```
.\venv\Scripts\activate.bat
```
3. Install requirements

```
pip install  -r requirements.txt
```

4. Run the 
```
flask --app app --debug run

```
#### Happy

![Happy](static/img/happy.png)

#### Neutral

![Neutral](static/img/neutral.png)

#### Anxious

![Anxious](static/img/anxious.png)

#### Depressed

![Depressed](static/img/depressed.png)



