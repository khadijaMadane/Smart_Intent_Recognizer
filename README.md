# Smart Intent Recognition

**Smart Intent Recognition** is an advanced natural language processing project designed to accurately classify user intents using a fine-tuned BERT model. This project is aimed at enhancing user experience in applications like chatbots and virtual assistants by providing precise intent detection.

- ## Dataset Overview

The **SNIPS Dataset** is a widely used benchmark for evaluating intent detection systems, comprising a collection of over 16,000 diverse user utterances categorized into various intents, such as "Book a Flight," "Get Weather Information," "Play Music," "Order Food," and "Get News Headlines." This dataset features a variety of phrases that users might say, reflecting different ways of expressing the same intent, which helps train robust models capable of generalizing well to real-world applications. Additionally, the SNIPS dataset is designed with a balanced distribution of intents to prevent bias toward any particular class during training. Each utterance is meticulously annotated with a corresponding intent, providing a clear mapping between user inputs and expected outputs. Utilizing this dataset enables the **Smart Intent Recognition** project to effectively comprehend user intents in conversational contexts and enhance the overall performance of NLP applications.
![dataset ](Images/dataset_presentation.png)


## Key Features

- **BERT-based Architecture**: Leverages the power of the BERT model for nuanced understanding of natural language.
- **Real-time Intent Prediction**: Provides instant predictions for user input, enhancing interactive applications.
- **Extensive Dataset**: Trained on the comprehensive SNIPS dataset, ensuring a wide range of intents are covered.
- **Customizable Interface**: Easy-to-use Gradio interface that allows for straightforward user interactions.
- **Detailed Performance Metrics**: Offers insights into model performance with precision, recall, and F1 scores for robust evaluation.
- **User-Centric Design**: Focuses on improving user experience by accurately identifying intents, leading to more relevant responses in applications.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/khadijaMadane/smart-intent-recognition.git
   cd smart-intent-recognition
   pip install -r requirements.txt

## Result
Here are sample predictions of different intents:

![result](Images/test1.png)
![result](Images/test2.png)
![result](Images/test3.png)
![result](Images/test4.png)

The images above showcase how accurately the model categorizes various user inputs.

## Contributing

We welcome contributions! Please feel free to submit issues or pull requests. If you have any questions or need support, feel free to reach out. We welcome any contributions that enhance the project's scope and impact.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

