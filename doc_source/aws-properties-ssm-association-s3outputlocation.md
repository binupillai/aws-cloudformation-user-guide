# AWS::SSM::Association S3OutputLocation<a name="aws-properties-ssm-association-s3outputlocation"></a>

An Amazon S3 bucket where you want to store the results of this request\.

## Syntax<a name="aws-properties-ssm-association-s3outputlocation-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-ssm-association-s3outputlocation-syntax.json"></a>

```
{
  "[OutputS3BucketName](#cfn-ssm-association-s3outputlocation-outputs3bucketname)" : String,
  "[OutputS3KeyPrefix](#cfn-ssm-association-s3outputlocation-outputs3keyprefix)" : String
}
```

### YAML<a name="aws-properties-ssm-association-s3outputlocation-syntax.yaml"></a>

```
﻿  [OutputS3BucketName](#cfn-ssm-association-s3outputlocation-outputs3bucketname) : String
﻿  [OutputS3KeyPrefix](#cfn-ssm-association-s3outputlocation-outputs3keyprefix) : String
```

## Properties<a name="aws-properties-ssm-association-s3outputlocation-properties"></a>

`OutputS3BucketName`  <a name="cfn-ssm-association-s3outputlocation-outputs3bucketname"></a>
The name of the Amazon S3 bucket\.  
*Required*: No  
*Type*: String  
*Minimum*: `3`  
*Maximum*: `63`  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`OutputS3KeyPrefix`  <a name="cfn-ssm-association-s3outputlocation-outputs3keyprefix"></a>
The Amazon S3 bucket subfolder\.  
*Required*: No  
*Type*: String  
*Maximum*: `500`  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)