
# CODEX - Coding AI chatbot

This is a simple chatbot created with the OpenAI API: just like chat GPT!!!

The server is deployed with "render" and the frontend with "vercel".

Check "deployment" for the demo. Be aware that the server is not always running.


## Run Locally

Clone the project and insert your API key from openAI in a file .env.

You also need to install node.js

```bash
  git clone https://github.com/Emanuele-Sgroi/codex_ai_bot
```

Go to the project directory

```bash
  cd my-project/server
```

Install dependencies

```bash
  npm install cors dotenv express nodemon openai
```

To start the server, cd to the server folder

```bash
  npm run server
```

To start the application, cd to the client folder

```bash
  npm run dev
```


## Fetch localhost:5000 to run the server within the frontend

```javascript
const response = await fetch('https://localhost:5000/', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json'
        },
        body: JSON.stringify({
            prompt: data.get('prompt')
        })
    })
```



## Tech Stack

**Client:** Vanilla JavaScript

**Server:** Node, openAI


## Authors

- [@Emanuele Sgroi](https://emanuelesgroi.com/)

## GIVE IT A STAR

Thank you

