
### CHATBot README

# CHATBot

CHATBot is a chatbot project using the Mistral 7B model fine-tuned with Wikipedia data.

## Project Description

This project aims to create a chatbot using the Mistral 7B model. The model has been fine-tuned with Wikipedia data and is capable of generating text.

## Requirements

The following libraries need to be installed:

- transformers
- bitsandbytes
- peft
- datasets
- accelerate
- trl
- huggingface_hub

To install the required libraries, run the following command:
```bash
!pip install -q -U transformers bitsandbytes peft datasets accelerate trl
```

## Model Training

The model training process is demonstrated in the `build_model.ipynb` file. This file loads the Mistral 7B model and trains it with Wikipedia data. Technologies such as bitsandbytes, peft, and accelerate were used to save memory and computational power. The model is currently hosted on Hugging Face: [Mesutby/mistral-7B-wikitext-finetuned](https://huggingface.co/Mesutby/mistral-7B-wikitext-finetuned).

### Running on Colab

This project was developed and run on Google Colab. Colab provides a suitable environment and powerful GPUs to run the project. If you want to run the project on your computer, make sure to set up a similar environment.

## Running the Chatbot

To run the chatbot, you first need to download the language model from Hugging Face and prepare it for text generation. To save memory, I preferred to use the tokenizer used for training the Mistral 7B model. To experience this process, use the `speech_sample.ipynb` file. This file loads the fine-tuned model and generates responses based on user inputs.

## Example Usage

1. Open the `speech_sample.ipynb` file to run the chatbot.
2. Enter a prompt and observe the chatbot's responses.

## Contributing

If you want to contribute to the project, please follow these steps:

1. Fork the project.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to your branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. For more information, see the [LICENSE](./LICENSE) file.

## Contact

If you have any questions, please contact: bymuhammedmesut@gmail.com
