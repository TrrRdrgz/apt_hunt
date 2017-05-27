# Apt Hunt 

This repo features the code needed to set up your own tinder-like swipe application to expedite the apartment hunt over Craigslist posts. 

## Getting Started
* [Configure](http://amunategui.github.io/idea-to-pitch/) an Apache2 server on an Amazon EC2 instance with read/write permissions to S3, DynamoDB, and SQS
* ssh into this server and clone the project repo into the home directory
* Run the setup.py script
* Edit the [configuration file](scraper/config.py)
* Allow the scraper to build a collection

## Usage
![Alt Text](https://s3-us-west-2.amazonaws.com/mayorquinmachines.ai/images/Apt_hunt.gif)

* Navigate to the EC2 server's IP address
* Register a new user
* Start Swiping!
