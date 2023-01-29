# PersonalAI

> Build of a ChatGPT AI Application with Javascript and OpenAI API.

## Run it Locally

```
$ git clone https://github.com/nunomiguens/personalAI.git
$ cd server
$ npm run server
$ cd client
$ npm run dev
```

## Env Variables

Create a .env file in the server directory and add the following

```
OPENAI_API_KEY= your OpenAI API secret key
```

## Replace the URL in the script.js file
```
const response = await fetch(/*here >*/'http://localhost:5000', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json',
        },
        body: JSON.stringify({
            prompt: data.get('prompt')
        })
    })
```
