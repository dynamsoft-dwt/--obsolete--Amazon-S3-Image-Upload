Upload Images to Amazon S3
=========

The sample shows how to upload the document images, scanned by [Dynamic Web TWAIN][1], to Amazon Web service. 

Screenshots
-----------
![image](http://www.codepool.biz/wp-content/uploads/2014/09/web_twain_demo-300x273.png)
![image](http://www.codepool.biz/wp-content/uploads/2014/09/amazon_upload-300x115.png)

Resources 
-----------

* [Dynamic Web TWAIN v10.0.1][2]
* [Amazon S3][3]

Blog
----
[How to Upload Scanned Images to Amazon S3 Using Dynamic Web TWAIN][4]

How to Run:
-----------
1. open `online_demo_operation.js`, and specify `strActionPage = ""; // Your amazon s3 URL`
2. open `online_demo_scan.php`, and specify `$bucket = ""; $accesskey = ""; $secret = "";`
3. deploy the project to your Web server
4. visit `online_demo_scan.php` in your Web browser



[1]:http://www.dynamsoft.com/Products/WebTWAIN_Overview.aspx
[2]:http://www.dynamsoft.com/download/Dynamic%20Web%20TWAIN%2010.0.1%20TRIAL.exe
[3]:http://aws.amazon.com/s3
[4]:http://www.codepool.biz/ocr-barcode-twain/twain-sdk/upload-image-to-amazon-s3.html
