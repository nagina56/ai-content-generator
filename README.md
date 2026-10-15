# AI Content Generator — n8n + Ollama

An AI-powered content generation workflow built with **n8n**, **Ollama**, and **Gemma 3 4B**. This project allows users to generate customized content by submitting a form with their topic, content type, platform, tone, and additional instructions.

## Features

- **Form-Based Input:** Collects content requirements through an interactive form.
- **Multiple Content Types:** Generate social media posts, blog introductions, LinkedIn posts, and product descriptions.
- **Platform Selection:** Customize content for LinkedIn, Instagram, Facebook, blogs, and other platforms.
- **Customizable Tone:** Choose professional, friendly, creative, or persuasive writing.
- **Additional Instructions:** Provide extra requirements to personalize generated content.
- **Local AI Model:** Uses Ollama with Gemma 3 4B for local content generation.
- **Automated Workflow:** Processes user inputs and generates content automatically.
- **Final Screen Output:** Displays the generated content on the form's final screen.

## Technologies Used

- n8n
- Ollama
- Gemma 3 4B
- Prompt Engineering
- Workflow Automation
- Large Language Models (LLMs)

## Workflow

1. **Form Submission:** The user enters the topic, content type, platform, tone, and additional instructions.
2. **Basic LLM Chain:** Combines the submitted information into a structured prompt.
3. **Ollama Chat Model:** The Gemma 3 4B model generates content based on the prompt.
4. **Form Ending:** Displays the generated content to the user on the final screen.

## How to Run

### Prerequisites

- Install [n8n](https://n8n.io/).
- Install [Ollama](https://ollama.com/).
- Download the Gemma 3 4B model.

### Setup

1. Start Ollama on your computer.
2. Download the model by running:

   ```bash
   ollama pull gemma3:4b
   ```

3. Start your local n8n instance.
4. Import or recreate the workflow in n8n.
5. Configure the Ollama Chat Model node and connect it to the Basic LLM Chain.
6. Configure the form fields and final Form Ending node.
7. Execute the workflow, submit the form, and view the generated content.

## Screenshots

Add screenshots of your project below:

- **Workflow Overview:** `ai content generator.PNG`
- **Input Form:** `2.PNG`
- **Generated Content:** `ai content generator output.PNG`


## Use Cases

- Social media content creation
- LinkedIn post drafting
- Blog introduction writing
- Product description generation
- Personalized marketing content

## Learning Outcomes

This project helped me practice:

- Building automation workflows with n8n
- Connecting a local LLM using Ollama
- Writing structured prompts
- Passing dynamic form inputs into an AI workflow
- Displaying AI-generated results to users

## Future Improvements

- Add more content templates.
- Include a copy-to-clipboard option.
- Support additional languages.
- Add output length controls.
- Allow users to save generated content.

## Author

**Nagina Azhar**

Exploring Python, AI, and workflow automation by building practical projects.

