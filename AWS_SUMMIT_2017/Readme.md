# [AWS SUMMIT 2017](https://aws.amazon.com/summits/chicago/)

Date: July 26-27, 2017
location: Chicago

## Scaling Up to Your First 10 Million Users
*by paul underwood*

- start with SQL rather than nosql - well known technology
- no need for SSL[https://www.digicert.com/ssl/], aws certi is enough
- Amazon **S3** for storage(<=5TB)
- Amazon **cloudFront**[photo3]
- **Elastic cache**
- **DynamoDB**
- Auto scaling
- Metrics to keep track of our app - **Host level metrics, log analysis, external site performance**


## Build an Alexa Skill using AWS Lambda
*by jeff blankenburg*

- Topic: **local attractions**
- Publishing(spoken language) is available in uk,usa, germany
- Create ALEXA SKILLS: aws(programming logic using lambda functions) + developer.amazon(voice user interface)
- Alexa skill sets - [photo1]
- you can create synonum
- language: javascript, json, ssml
- 

### Tutorial: 
[https://github.com/alexa/alexa-cookbook/tree/master/labs/LocalRecommendations]

**STEPS**
- [https://developer.amazon.com/edw/home.html#/skill/create/]
- launch builder
- Intent Schema
- copy- [https://github.com/alexa/alexa-cookbook/blob/master/labs/LocalRecommendations/speechAssets/InteractionModel.json]
- *apply changes* & *save model*
- *Build model* - this where we compile
- *COnfiguration*
- lambda on aws - eventdriven serverless computer service
- click on alexa-skill-kit-sdk-factskill
- set *n.virgina* on the region - bcz alexa only works on n.virgina
- set alexa skill set and press next
- note github has all the templates for the lambda function ode
- lambda function role =- create custom role
- next
- createfunction
- NOTE: if your skills is below 100$ alexa team pays you..no worries

- open src/index.js from that github
- paste it in code section and save
- copy ARN from top right corner
- paste it in the lambda endpoint/ northermerica
- Voice Simulator - just check out ssml tags link above
- Enter utterance - open Westerville stuff and then press ask westervill stuff button
- Enter utterance - coffee and then press ask westervill stuff button
Note the request changes

-[https://echosim.io/welcome]
- virtual device like echo dot
- 

other resources
- [https://github.com/alexa/skill-sample-nodejs-fact]
- [https://developer.amazon.com/alexa-skills-kit/alexa-developer-skill-promotion]


## Deep Learning at Cloud Scale and AI as a Service
*by Krishna Sumanth Muppalla*

- segnet model
- ssgd
- processors[photo1]
- DL FRAMEWORK[photo2]

tutorial
- mo25000 movie dataset from standford
- lstm modesl
- [https://github.com/krishnasumanthm/Movie_Rating_Prediction]
