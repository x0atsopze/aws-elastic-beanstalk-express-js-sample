# AWS Elastic Beanstalk Node.js Sample App

This repository contains a sample Node.js web application built using [Express](https://expressjs.com/), meant to be used as part of the AWS DevOps Learning Path.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.



## Overview
I created a continuous delivery pipeline for a simple web application. I made use of github as the version control system to store the application source code. Then, I leveraged AWS CodeBuild as CI tool to package, build and test the application. AWS CodePipeline on the other hand helped me create a continuous delivery pipeline that automatically deployed the web application. I also integrated a manual approval process stage and configured a webook on the repository to trigger a new deployment whenever the source code is updated.



## Project Architecture

![image](https://github.com/x0atsopze/aws-elastic-beanstalk-express-js-sample/assets/109428762/621a49c8-fd44-4149-a45f-7c4570a9bf47)
