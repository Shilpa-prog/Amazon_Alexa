# Amazon_Alexa

The Skill

Cake Time is a skill that celebrates your birthday! Tell it your birthday to have it count down the days. Interact with the skill on your special day to hear a happy birthday message.


Requirements to build a skill:

a) Sign up for an account on the Alexa developer console. The console is where you will build and optimize your skill.

b) An internet-accessible endpoint for hosting your backend cloud-based service. Your backend skill code is usually a Lambda function.

c) Development environment appropriate for the programming language you plan to use. Lambda natively supports Java, Go, PowerShell, Node.js, C#, Python, and Ruby and provides a runtime API.

d) Publicly accessible website to host any images, audio files, or video files used in your skill. If you host your skill backend with the Alexa-hosted hosting option, an Amazon Simple Storage Service (Amazon S3) will be provisioned for you. If you use another hosting option, such as AWS Lambda, you may use Amazon S3 to host files used in your skill. 

e) (Optional) Alexa-enabled device for testing. Skills work with all Alexa-enabled devices, such as the Amazon Echo, Echo Dot, Fire TV Cube, and devices that use the Alexa Voice Service (AVS). If you don't have a device, you can use the Alexa simulator in the developer console. Through the simulator, you can see the display templates for Echo Show and Echo Spot, although the display is not interactive. 


The Steps to Build a Skill?

Step 1: Design the Voice User Interface
To provide a fluid and natural voice experience, it is important to script and then act out the different ways a user might talk to Alexa.  Also, if you have a multi-modal experience (voice and visual), you need to think of different workflows to navigate through your skill.

Step 2: Build
Once your interaction model is ready, build the utterances, intents, and slots in the Alexa developer console.

The interaction model is saved in JSON format, and you can edit the model with any edit tool. After your JSON interaction model is ready, build the backend Lambda function in the AWS Management Console.

Step 3: Test
The Alexa developer console has a built-in Alexa simulator, which is similar to testing on an actual Alexa-enabled device.

Step 4: Certification and launch
After beta testing your skill, submit it for certification. 
