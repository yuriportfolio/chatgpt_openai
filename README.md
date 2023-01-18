#  [Live demo](https://chatgpt-openai.vercel.app/)

![Vercel](https://vercelbadge.vercel.app/api/ZJW-92/chatgpt_openai)

A language model chatbot developed by OpenAI based on GPT 3.5. Users can interact with bot, require chatbot to write, debug code and explain almost everything. 

## Screenshot 
![screenshot](screenshot.png)

## Tech Stack
### Server: 
 - 1. ***[Node.js](https://nodejs.org/en/)***: _JavaScript runtime environment._
 - 2. ***[Express](https://expressjs.com/)***: _Node js web application framework._
 - 3. ***[OpenAIApi](https://openai.com/api/)***: _Performs a wide variety of natural language tasks, and Codex, which translates natural language to code._

### Client: 
- 1. ***HTML***
- 2. ***CSS***
- 3. ***JavasSript***
- 4. ***[Vite](https://vitejs.dev/)***: _Development environment for frameworks like Vue and React._


## Set up
Run `npm create vite@latest client --template vanilla` and choose vanilla as framework.

## Sign up account in [OpenAI](https://openai.com/api/) to get the secret OPENAI_API_KEY

## server && client
Run `npm install && npm run server`
Run `npm install && npm run dev`

## Deploy
- [Render](https://render.com/) to host server side and add OPENAI_API_KEY in the environment variable

- [Vercel](https://vercel.com/) to host the client side


## Issues and solutions
 > - 1. Error message 401: it means OPENAI_API_KEY in configruation is unauthorized
 >>Solution: make sure put the OPENAI_API_KEY in `.env` inside of server folder rather than the root directory. 

> - 2. Uncaught TypeError: fail to fetch at .... 
>> Solution: change the localhost 5000 link in script.js to the new server link from render and push again
 
> - 3. Free trial usage is $18 and API key will expire on May 1, 2023


