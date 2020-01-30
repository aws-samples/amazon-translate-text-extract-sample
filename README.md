# Serverless Document Translation

## Summary
This solution allows users to translate text documents from one language to another. You can use any of the supported *language pairs* offered by [Amazon Translate](https://docs.aws.amazon.com/translate/latest/dg/what-is.html).


## Workflow
The workflow for this app is very simple. It only involves three AWS services - Amazon S3, AWS Lambda and Amazon Translate. Amazon S3 is used to store the documents. AWS Lambda extracts text from the document and makes API call to Amazon Translate to translate the text and create a new document with translated text. At the end, the Lambda function uploads the translated document to the ouput S3 bucket.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

