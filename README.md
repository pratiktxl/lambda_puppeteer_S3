# Lambda + Puppeteer + S3
This function takes screenshot of the website given as input and saves to S3

# Layer Information
Below code snippet is tested in Amazon Linux 2 EC2 instance. 
It creates zip file of the layer. 

"""

git clone --depth=1 https://github.com/alixaxel/chrome-aws-lambda.git && \
cd chrome-aws-lambda && \
make chrome_aws_lambda.zip

"""

Source - https://www.npmjs.com/package/chrome-aws-lambda
