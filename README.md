# Amazon Rekognition code examples for the SDK for Python

## Overview

Shows how to use the AWS SDK for Python (Boto3) to work with Amazon Rekognition.

<!--custom.overview.start-->
Also includes a [utility](custom_labels_csv_to_manifest.py) that you can use to create a custom label image-level manifest 
file from a CSV file.
<!--custom.overview.end-->

_Amazon Rekognition makes it easy to add image and video analysis to your applications._

## ⚠ Important

* Running this code might result in charges to your AWS account. For more details, see [AWS Pricing](https://aws.amazon.com/pricing/) and [Free Tier](https://aws.amazon.com/free/).
* Running the tests might result in charges to your AWS account.
* We recommend that you grant your code least privilege. At most, grant only the minimum permissions required to perform the task. For more information, see [Grant least privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).
* This code is not tested in every AWS Region. For more information, see [AWS Regional Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services).

<!--custom.important.start-->
<!--custom.important.end-->

## Code examples

### Prerequisites

For prerequisites, see the [README](../../README.md#Prerequisites) in the `python` folder.

Install the packages required by these examples by running the following in a virtual environment:

```
python -m pip install -r requirements.txt
```

<!--custom.prerequisites.start-->
<!--custom.prerequisites.end-->

### Single actions

Code excerpts that show you how to call individual service functions.

- [Compare faces in an image against a reference image](rekognition_image_detection.py#L117) (`CompareFaces`)
- [Create a collection](rekognition_collections.py#L323) (`CreateCollection`)
- [Delete a collection](rekognition_collections.py#L111) (`DeleteCollection`)
- [Delete faces from a collection](rekognition_collections.py#L280) (`DeleteFaces`)
- [Describe a collection](rekognition_collections.py#L84) (`DescribeCollection`)
- [Detect faces in an image](rekognition_image_detection.py#L96) (`DetectFaces`)
- [Detect labels in an image](rekognition_image_detection.py#L156) (`DetectLabels`)
- [Detect moderation labels in an image](rekognition_image_detection.py#L178) (`DetectModerationLabels`)
- [Detect text in an image](rekognition_image_detection.py#L207) (`DetectText`)
- [Index faces to a collection](rekognition_collections.py#L126) (`IndexFaces`)
- [List collections](rekognition_collections.py#L346) (`ListCollections`)
- [List faces in a collection](rekognition_collections.py#L167) (`ListFaces`)
- [Recognize celebrities in an image](rekognition_image_detection.py#L226) (`RecognizeCelebrities`)
- [Search for faces in a collection](rekognition_collections.py#L241) (`SearchFaces`)
- [Search for faces in a collection compared to a reference image](rekognition_collections.py#L193) (`SearchFacesByImage`)

### Scenarios

Code examples that show you how to accomplish a specific task by calling multiple
functions within the same service.

- [Build a collection and find faces in it](rekognition_objects.py)
- [Detect and display elements in images](rekognition_image_detection.py)

### Cross-service examples

Sample applications that work across multiple AWS services.

- [Detect objects in images](../../cross_service/photo_analyzer)
- [Detect people and objects in a video](../../example_code/rekognition)


<!--custom.examples.start-->
<!--custom.examples.end-->

## Run the examples

### Instructions


<!--custom.instructions.start-->
<!--custom.instructions.end-->



#### Build a collection and find faces in it

This example shows you how to do the following:

- Create an Amazon Rekognition collection.
- Add images to the collection and detect faces in it.
- Search the collection for faces that match a reference image.
- Delete a collection.

<!--custom.scenario_prereqs.rekognition_Usage_FindFacesInCollection.start-->
<!--custom.scenario_prereqs.rekognition_Usage_FindFacesInCollection.end-->

Start the example by running the following at a command prompt:

```
python rekognition_objects.py
```


<!--custom.scenarios.rekognition_Usage_FindFacesInCollection.start-->
<!--custom.scenarios.rekognition_Usage_FindFacesInCollection.end-->

#### Detect and display elements in images

This example shows you how to do the following:

- Detect elements in images by using Amazon Rekognition.
- Display images and draw bounding boxes around detected elements.

<!--custom.scenario_prereqs.rekognition_Usage_DetectAndDisplayImage.start-->
<!--custom.scenario_prereqs.rekognition_Usage_DetectAndDisplayImage.end-->

Start the example by running the following at a command prompt:

```
python rekognition_image_detection.py
```


<!--custom.scenarios.rekognition_Usage_DetectAndDisplayImage.start-->
<!--custom.scenarios.rekognition_Usage_DetectAndDisplayImage.end-->

### Tests

⚠ Running tests might result in charges to your AWS account.


To find instructions for running these tests, see the [README](../../README.md#Tests)
in the `python` folder.



<!--custom.tests.start-->
<!--custom.tests.end-->

## Additional resources

- [Amazon Rekognition Developer Guide](https://docs.aws.amazon.com/rekognition/latest/dg/what-is.html)
- [Amazon Rekognition API Reference](https://docs.aws.amazon.com/rekognition/latest/APIReference/Welcome.html)
- [SDK for Python Amazon Rekognition reference](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html)

<!--custom.resources.start-->
<!--custom.resources.end-->

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: Apache-2.0# Object-Detection
