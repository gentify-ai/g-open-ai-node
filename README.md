# Gentify OpenAI Node

A node for interacting with OpenAI's Chat API. This node enables you to make calls to OpenAI's language models and receive responses.

## Functions

### callModel

Makes a call to OpenAI's chat completion API.

#### Input Parameters

- **apiKey** (required)

  - Your OpenAI API key for authentication

- **model** (required)

  - Available options:
    - `gpt-4o`: GPT-4o model
    - `gpt-4o-mini`: GPT-4o Mini model
    - `gpt-4o-2024-08-06`: GPT-4o 2024-08-06 model

- **messages** (required)
  - An array of message objects that form the conversation
  - Each message must contain:
    - **role**: `system`, `user`, or `assistant`
    - **content**: The message text

#### Response

Returns an object containing the AI-generated response content.
