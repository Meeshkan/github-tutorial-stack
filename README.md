# github-tutorial-stack

[![button](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=MeeshkanGitHubDeepLearningTutorial&templateURL=https://s3.amazonaws.com/meeshkan-github-tutorial/stack.yaml)

The AWS CloudFormation stack for the Meeshkan GitHub Deep Learning tutorial.  Launch this stack in your AWS by clicking the button above.

Note that the approximate charges for the tutorial is $10 a day running 20 simultaneous servers and one database.  You can turn the tutorial off at anytime simply by deleting the stack.

## Step By Step

If you do not have an AWS account yet, just head on over to https://console.aws.amazon.com to make one.

### 1.

After clicking on the `Launch Stack` button, you'll arrive at a page that looks like this.  You'll see that `Specify an Amazon S3 template URL` is prefilled with this template, so just click on **Next**.

![First Screen](https://s3.amazonaws.com/meeshkan-github-tutorial/Screen+Shot+2017-12-23+at+8.06.19.png)

### 2.

You'll be presented with a few parameters you can tweak.  None of them are required, but I would recommend always filling in the KeyName with a key so that you can SSH into your EC2 instance.  If you do not know what SSH is or what a key is, check out [this link](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html) to see how to make one.

The entire tutorial operates within the AWS ecosystem except for an optional [sentry.io](https://sentry.io) integration that will help you follow errors in realtime.

![Second Screen](https://s3.amazonaws.com/meeshkan-github-tutorial/Screen+Shot+2017-12-23+at+8.06.46.png)

### 3.

