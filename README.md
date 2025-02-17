# -Chatbot-with-Large-Language-Model-

---

# Chatbot Web Application

This project consists of a **Flask web application** with an integrated **chatbot**. The chatbot utilizes a fine-tuned language model, which processes user input and provides intelligent responses.

## Requirements

Make sure you have the following libraries installed:

- Flask
- torch
- datasets
- transformers
- peft
- trl
- GPTQ (for quantized models)

You can install these requirements using:

```bash
pip install Flask torch datasets transformers peft trl
```

## File Structure

- **app.py**: Main Flask application to run the server.
- **chat.html**: Frontend file to render the chat interface.
- **chatbot.py**: Contains the chatbot function to process user messages.
- **training_script.py**: Script for fine-tuning the language model with the Alpaca dataset using a LORA-based PEFT configuration.

## Usage

1. **Start the Flask Application**:

   Run the main Flask application to start the server.

2. **Interact with the Chatbot**:

   Open the web interface to chat with the chatbot, powered by a fine-tuned language model.

## Fine-tuning the Model

The fine-tuning script uses a specialized model, which is trained on the **Alpaca dataset**. It leverages **PEFT** (parameter-efficient fine-tuning) for efficient and resource-friendly training. The model is optimized using **GPTQ quantization** for improved performance on smaller devices or lower resource environments.

## Conclusion

This project enables users to interact with an AI chatbot, powered by a state-of-the-art language model fine-tuned on a diverse dataset. It also provides an efficient training pipeline for further improving the model using **PEFT**.

Feel free to explore, modify, or extend the application as per your requirements.
