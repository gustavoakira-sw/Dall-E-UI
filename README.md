# Dall-E UI

This is a user interface (UI) for interacting with the Dall-E model to generate images based on user prompts. The UI is built using HTML, CSS, and JavaScript (Vue.js) and allows users to input a prompt, select the Dall-E model version, and choose the image size.

## Features

- Submit a prompt and generate images using the Dall-E model.
- Select the Dall-E model version (Dall-E 2 or Dall-E 3).
- Choose the image size (256x256, 512x512, or 1024x1024).
- Dark mode switch for improved visibility.

## Getting Started

1. Clone the repository to your local machine.
2. Replace the `API_KEY` variable in the JavaScript code (`index.html`) with your actual API key.
3. Open the `index.html` file in a web browser.
4. Enter your prompt in the text area.
5. Select the desired Dall-E model version and image size.
6. Click the "Submit request" button to generate the image.
7. Switch between light and dark mode using the theme switch toggle.

## Usage

- **Prompt Input:** Enter your prompt in the text area provided. This could be a description or sentence to guide the image generation process.
- **Model Selection:** Choose the Dall-E model version (Dall-E 2 or Dall-E 3) from the dropdown menu.
- **Size Selection:** Select the image size (256x256, 512x512, or 1024x1024) from the dropdown menu.
- **Submit Request:** Click the "Submit request" button to send the prompt to the Dall-E model and generate the corresponding image.
- **Dark Mode:** Toggle the theme switch to enable dark mode for better visibility in low-light environments.

## Libraries

- Vue.js: [https://vuejs.org/](https://vuejs.org/)
- Bootstrap CSS: [https://getbootstrap.com/docs/4.5/getting-started/introduction/](https://getbootstrap.com/docs/4.5/getting-started/introduction/)

## API Integration

The UI integrates with the OpenAI API to send prompts and receive image responses from the Dall-E model. To use the API, you need to obtain an API key from OpenAI and replace the `API_KEY` variable in the JavaScript code with your actual API key. [https://github.com/gustavoakira-sw/Dall-E-UI/blob/5f7d4b584a95309b879e082d0e93d438ce3e5207/index.html#L179](You can find this in line 179.)

## Resources

- OpenAI API reference: [https://platform.openai.com/docs/api-reference/images](https://platform.openai.com/docs/api-reference/images)

## Contributing

Contributions are welcome! If you have suggestions, enhancements, or bug fixes, please submit a pull request or open an issue on GitHub.