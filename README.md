# trigger-test

🔥 Jenkins is top.
Let's do it again.

:smile: Great times are comming.

🎆 Have a happy new year!

## Next steps

I create a wook at github and also exposed my localhost url with https://ngrok.com/download.

I still working around to solve the build that's not happen.

It's more complicated then I imagine.

- How to install local
`snap install ngrok`
- Connecto to your account
`ngrok config add-authtoken TOKEN`
To start a HTTP tunnel forwarding to your local port 80, run this next:
`ngrok http 80`

This approach didn't work, then the other possibility was Localtunnel, you need to install it locally following the command. `npm install -g localtunnel`, after that expose the port when your application is running. `lt -p <portNumber> -s <myjenkins>`.

Still having problems with my connection
