# Voice agent using Deepgram, Twilio and Python app server
## Signup with Twilio, Deepgram and Ngrok, after creating accounts
## Grab Deppgram key DEEPGRAM_API_KEY from from the portal and use it in env
## From Twilio Home dashboard Buy a number e.g (1 229 329 1452) and add a verified caller (number from which call will be made) as only voice is to be used
## Use ngrok key, Run the ngrok using ngrok http 5000
## Use ngrok provided public link for TwiML Bins after searching for Twimlbins from search box of the Twilio portal
## Use it in the TwiML Bin <Stream url="wss://xxxxxx.ngrok-free.app/twilio" /> with wss as websocket is being used
## Save the TwiML bin file and give a friendly name, select TwiML and friendly name twice, leave webhook and other configurations AS IS.
## Dial  e.g (1 229 329 1452) after running the python code as ngrok is also running
## Test with the voice commands


