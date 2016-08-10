# Info heap

Serverless architecture replaces long-running virtual machines with ephemeral compute power that comes into existence on request and disappears immediately after use. Examples include Firebase and AWS Lambda. Use of this architecture can mitigate some security concerns such as security patching and SSH access control, and can make much more efficient use of compute resources. These systems cost very little to operate and can have inbuilt scaling features (this is especially true for AWS Lambda). An example architecture could be a JavaScript app with static assets served by a CDN or S3 coupled with AJAX calls served by the API Gateway and Lambda. While serverless architectures have significant benefits, there are drawbacks too: Deploying, managing and sharing code across services is more complex, and local or offline testing is more difficult if not impossible.

## Books

* [Serverless](https://leanpub.com/serverless)
* [Serverless Single Page Apps: Fast, Scalable, and Available](https://www.amazon.com/gp/product/1680501496?ie=UTF8&tag=martinfowlerc-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=1680501496) (1st Edition)


## Reading

* [Serverless Architectures](http://martinfowler.com/articles/serverless.html)
* [Abstracting the Back-end with FaaS](https://serverless.zone/abstracting-the-back-end-with-faas-e5e80e837362#.q5obnmio6)
* [Just serverless blog](http://justserverless.com/blog/)


## Solutions

* [Webtask](https://webtask.io/)
* [Parse](http://www.parse.com/)
* [The Serverless Framework ](https://github.com/serverless/serverless) 9k+ stars
