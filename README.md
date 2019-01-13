Example CloudFormation Template for Publishing an Alexa Skill
---

This is a simple example of a CloudFormation template that can be used to publish an Alexa skill.

## Steps

1. Login to [developer.amazon.com](https://developer.amazon.com)
2. Get your 'vendor ID' from [https://developer.amazon.com/mycid.html](https://developer.amazon.com/mycid.html)
3. Setup a security profile for [Login With Amazon](https://developer.amazon.com/login-with-amazon)
4. Use the [ASK CLI]() to [get an Access Code and Refresh Token](https://developer.amazon.com/docs/smapi/ask-cli-command-reference.html#generate-lwa-tokens)
5. Create a .zip with the skill Lambda files
6. Store the .zip in an S3 bucket
7. Create a CloudFormation template
8. Execute template

