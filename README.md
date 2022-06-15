# SQSLambdaDynamoDB

This repo shows the power of simple event driven programs, triggering a lambda function to send messages from SQS to a DynamoDB table.
This repo consists of send_message.py which will send random messages from EC2 to SQS.
The inflow of messages on SQS will trigger the Lamba function.
The function lambda_function.py will then move write messages from the queue in SQS to a DynamoDB table.

For detailed steps, jump over to https://dev.to/neetumallan/triggering-a-lambda-function-using-sqs-to-populate-dynamodb-ola-temp-slug-519511?preview=1936735c7afb3699e9104306f97b43fe501ecd0776ba5be064e99996897287cfb28b3567d42b97cac0c7358a912eaf67203bf6b5c0eb857965c3dbbf
