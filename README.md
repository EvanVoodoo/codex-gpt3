# codex-gpt3
An AI :robot: tool made using GPT-3. This was made by following this [YouTube tutorial](https://youtu.be/2FeymQoKvrk), and then changed and expanded upon by myself.

## Instructions:
### Setup
1. Make sure to run "npm install" in client and server to get all the dependencies.
2. Get your own API key from https://platform.openai.com.
3. Once you have it, create a .env file in the server folder and add this line: OPENAI_API_KEY="[your api key here]"
4. While in their respective directories, use "npm run dev" to start the client, and "npm run server" to boot the server.

### Using the app
* Ask the AI almost anything by using the message box at the bottom.
* Add the tag IMG (case sensitive) anywhere in your message to get a generated image based on your prompt.
* !!! Quick reminder that using the API isn't free. According to [the OpenAI team](https://openai.com/api/pricing/): "Prices are per 1,000 tokens. You can think of tokens as pieces of words, where 1,000 tokens is about 750 words. This paragraph is 35 tokens.". Using the text generation costs $0.02 per 1K tokens, and using the image generation costs $0.018 per image.
