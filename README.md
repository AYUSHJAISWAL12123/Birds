# Balcony Birds

Balcony Birds is a lightweight, single-page web application designed to help you plan your balcony to attract and support local birds in India. 

Based on your region, balcony sunlight, space, and floor level, it generates a custom plan including:
- **Which birds** can realistically visit and breed during the current season.
- **What to plant** in pots to provide food (seeds, fruit, nectar) and cover.
- **Nesting box specifications** tailored to the birds that might visit your floor.
- **A weekly to-do list** to get your balcony ready.

## Features

- **No server required**: Runs entirely in your browser. Just open `balcony-birds.html`.
- **Customizable**: Built with plain JavaScript data objects at the top of the script, so you can easily edit the regions, birds, and plants for your specific local area.
- **Printable**: Generates a clean, print-friendly layout so you can take the sheet outside.
- **Optional Local AI**: Integrates with [Ollama](https://ollama.com/) to provide a warm, plain-language explanation of your plan using a local open-weight model (e.g., `qwen3:4b`). Your data never leaves your computer.

## Usage

1. Open `balcony-birds.html` in any modern web browser.
2. Select your region, balcony sunlight, space for pots, and floor level.
3. Click **Plan my balcony**.
4. Read the generated plan, print it, and start setting up!

## Local AI Setup (Optional)

If you want the AI to explain your plan:
1. Install [Ollama](https://ollama.com/).
2. Pull a small model, for example: `ollama pull qwen3:4b`.
3. Start the Ollama server allowing cross-origin requests: `OLLAMA_ORIGINS="*" ollama serve`.
4. Click the "Explain it with my local AI" button on the generated plan.

## License

This project is open-source and free to use and modify.
