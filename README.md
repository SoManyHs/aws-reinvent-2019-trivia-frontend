## AWS re:Invent 2019 Trivia Game

Sample trivia game built with AWS Fargate and deployed with Amazon CodePipeline.  See [reinvent-trivia.com](https://www.reinvent-trivia.com) for a running example.

## Components

* **Static Site**: Web application page, backed by Amazon S3, Amazon CloudFront, and Amazon Route53.  See "static-site" folder
* **Continuous delivery**: Pipelines that deploy code and infrastructure for each of the components.  See "pipelines" folder.

## License Summary

This sample code is made available under the MIT license. See the LICENSE file.

## Credits

Static site based on [React Trivia](https://github.com/ccoenraets/react-trivia)
