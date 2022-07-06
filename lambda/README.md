
## Alexa Skills

I've created an skill of Alexa with nodeJS and Lamdba.

## Deployment

I've used Alexa-hosted in nodeJS:

Alexa will host skills in your account and get you started with a Node.js template. 
You will gain access to AWS Lambda endpoints in all Alexa service regions, 
a DynamoDB table for data persistence, 
and S3 for media storage

### Intents

I've created intents in a json file. 
The intents are necesary to trainning the bot. 

{
    "interactionModel": {
        "languageModel": {
            "invocationName": "toy story",
            "intents": [
                {
                    "name": "AMAZON.CancelIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.HelpIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.StopIntent",
                    "samples": []
                },
                {
                    "name": "BuzzIntent",
                    "slots": [],
                    "samples": [
                        "hasta el infinito"
                    ]
                },
                {
                    "name": "AMAZON.NavigateHomeIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.FallbackIntent",
                    "samples": []
                },
                {
                    "name": "WoodyIntent",
                    "slots": [],
                    "samples": [
                        "Hay una serpiente"
                    ]
                },
                {
                    "name": "FraseBuzz",
                    "slots": [],
                    "samples": [
                        "buzz lighyear",
                        "Buzz Lightyear",
                        "lightyear",
                        "buzz"
                    ]
                },
                {
                    "name": "FraseWoody",
                    "slots": [],
                    "samples": [
                        "vaquero",
                        "woody"
                    ]
                }
            ],
            "types": []
        }
    }
}

## Code

The code is a Lambda function in nodeJS.
