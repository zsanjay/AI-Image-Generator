# 🧠🎨 AI Image Generator with OpenAI and Node.js
This is a simple web application that uses the OpenAI API to generate images from text prompts using the DALL·E model. Built with Node.js, Express, and a lightweight frontend to allow users to enter prompts and view generated images.

----

# 🚀 Features

#### Generate images from custom prompts using OpenAI's DALL·E API
#### Display loading/progress states for each image
#### Show image or failure message for each request
#### Simple frontend using HTML, CSS, and vanilla JavaScript

----

# 📦 Tech Stack

Backend: Node.js, Express
Frontend: HTML, CSS, JavaScript
AI Provider: OpenAI API (DALL·E image generation)

----

# 🛠️ Getting Started

✅ Prerequisites

Node.js v16+
OpenAI API Key (get one from platform.openai.com)

----

# 🔧 Installation

Clone the repository

```bash
git clone https://github.com/zsanjay/AI-Image-Generator
cd AI-Image-Generator
```

Install dependencies

```bash
npm install
```

Create .env file

```env
OPENAI_API_KEY=your-openai-api-key
PORT=3000
```

Run the app

```bash
npm start
```

Visit http://localhost:3000 in your browser.

----

# ✨ Usage

<ul>
  <li>Enter a creative prompt like: "a futuristic city on Mars in Van Gogh style"</li>
  <li>Click Generate Image</li>
  <li>Wait for the image to appear or an error message to be displayed</li>
</ul>

----

# 🧠 How It Works

The frontend sends a POST request with the prompt to /api/generate
The Express backend uses OpenAI's API to generate an image URL using the prompt
The image is returned to the frontend and displayed in the UI

----

# ❗ Troubleshooting

API key invalid or missing: Double-check your .env file
Image not displaying: Check the browser console and network tab for errors
Rate limit: OpenAI has usage quotas. Monitor your API usage

----
# 🤝 Contributing
PRs and feedback welcome! If you have improvements for error handling, progress UI, or prompt enhancements — open an issue or submit a pull request.

----

# 🙌 Credits

OpenAI DALL·E API
Node.js and Express community
