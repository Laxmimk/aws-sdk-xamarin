# The AWS Mobile SDK for Xamarin - DEVELOPER PREVIEW Released 

## **UPDATE 07/28/2015**: 

**The AWS Mobile SDK Xamarin Beta has been updated to an official Developer Preview release and can be located as a part of the AWS .NET SDK.**  The Source is located [https://github.com/aws/aws-sdk-net][1]. With the update and migration of the AWS Mobile SDK for Xamarin into the AWS .NET SDK it has also been modularized by services, therefore the NuGet packages for the individual AWS services can be retrieved here: [https://github.com/aws/aws-sdk-net#nuget-packages][2]
This SDK repo is now for historical purposes only and was last updated 05/2015.  For current AWS Xamarin SDK functionality, please leverage links and information provided at links above. 

__________
We are making the AWS Mobile SDK for Xamarin available as a beta for you to evaluate and provide us feedback. Now you can use Xamarin to build cross platform apps that use AWS services for identity management ([Amazon Cognito](http://aws.amazon.com/cognito/)), cloud storage ([Amazon S3](http://aws.amazon.com/s3/)), a fully-managed NoSQL database ([Amazon DynamoDB](http://aws.amazon.com/dynamodb/)), and push notifications ([Amazon SNS Mobile Push](http://aws.amazon.com/sns/)).

The SDK is available on AWSLabs [here](https://github.com/awslabs/aws-sdk-xamarin) and is in early stage development. The current version of the SDK (v3)  has been updated to provide more features and services for evaluation.  We plan to make improvements based on your feedback, so be sure to let us know if you have questions, issues or ideas [here](https://github.com/awslabs/aws-sdk-xamarin/issues).

## Highlights

 * Included iOS Unified library in addition to Classic iOS project for iOS 64 Apple requirement and Xamarin Unified API. iOS project is Unified API to be used with iOS 64 and iOS-Classic is classic Xamarin library API.

 * **Amazon Cognito (Identity)**: With [Amazon Cognito](http://aws.amazon.com/cognito/), you can create unique end user identifiers for accessing AWS cloud services by using public login providers such as Amazon, Facebook, and Google, or by using your own user identity system and generate temporary, limited-privilege credentials for accessing AWS resources eliminating the need to embed AWS credentials in the app. With Amazon Cognito Identity, you can also set granular access permissions on your existing AWS resources.

 * **Amazon Cognito (Sync)**: With [Amazon Cognito](http://aws.amazon.com/cognito/), allows you to store user data for your apps, such as user preferences and game state, in the Amazon Cognito sync store. You can then sync this data across a user’s devices to help make their experience consistent across their devices. Updated in v2 of SDK.

 * **Amazon S3 Cloud Storage**: [Amazon S3](http://aws.amazon.com/s3/) provides a simple web-services interface to store and retrieve any amount of data, at any time, from anywhere on the web.. The AWS Mobile SDK for Xamarin helps you access Amazon S3 from your mobile app while optimizing for performance and reliability. It hides the complexity of transferring files behind an extremely simple API. Whenever possible, uploads are broken up into multiple pieces, so that several pieces can be sent in parallel to provide better throughput.

 * **Amazon DynamoDB (NoSQL Database)**: [Amazon DynamoDB](http://aws.amazon.com/dynamodb/) is a fast, fully managed NoSQL database service that makes it simple and cost-effective to store and retrieve any amount of data, and serve any level of request traffic. The Object Persistence Framework in the AWS Mobile SDK for Xamarin, eliminates the need for application-level data conversions and custom middle-ware solutions by mapping .NET classes to Amazon DB items to store and retrieve data.

 * **Amazon SNS Mobile Push**: [Amazon SNS Mobile Push](http://aws.amazon.com/sns/) is a fast, flexible, fully managed push messaging service. Amazon SNS makes it simple and cost-effective to push notifications to Apple, Google, Fire OS, and Windows devices, as well as Android devices in China with Baidu Cloud Push.


 * **AWS Lambda (preview)**: [AWS Lambda][3] is a AWS Lambda is a compute service that runs your code in response to events and automatically manages the compute resources for you, making it easy to build applications that respond quickly to new information. Newly added in v2 of the SDK

 * **AWS Key Management Service (KMS)**: [AWS Key Management](http://aws.amazon.com/kms/) is a managed service that makes it easy for you to create and control the encryption keys used to encrypt your data, and uses Hardware Security Modules (HSMs) to protect the security of your keys.  Newly added in v2 of the SDK.

## Resources

Here are some resources that can help you get started:

* [AWSLabs GitHub Repo for AWS Mobile SDK for Xamarin](https://github.com/awslabs/aws-sdk-xamarin)
* [AWS .Net SDK Guide](http://docs.aws.amazon.com/AWSSdkDocsNET/latest/DeveloperGuide/)
* [AWS .Net API Reference Guide](http://docs.aws.amazon.com/sdkfornet/latest/apidocs/Index.html)
* [Amazon S3 Developer Guide](http://docs.aws.amazon.com/AmazonS3/latest/dev/)
* [Amazon DynamoDB Developer Guide](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/)
* [Amazon SNS Developer Guide](http://docs.aws.amazon.com/sns/latest/dg/)
* [AWS Xamarin SDK NuGet Package](https://www.nuget.org/packages/AWS-Mobile-SDK-Xamarin-Beta/)


  [1]: https://github.com/aws/aws-sdk-net "https://github.com/aws/aws-sdk-net"
  [2]: https://github.com/aws/aws-sdk-net#nuget-packages "https://github.com/aws/aws-sdk-net#nuget-packages"
  [3]: http://aws.amazon.com/lambda/ "AWS Lambda"
