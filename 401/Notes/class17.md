# Class 17 Reading notes

(https://aws.amazon.com/s3/)

What is Amazon S3?
Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance. Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile apps. With cost-effective storage classes and easy-to-use management features, you can optimize costs, organize data, and configure fine-tuned access controls to meet specific business, organizational, and compliance requirements.
<br>

Name some use cases for Amazon S3.
nuilding a Data Lake, Backing up Data, low cost archives, running cloud native apps.
<br>

Name some benefits of using Amazon S3.
You can move data, store it, and analyze it.
<br>

(https://www.serverless.com/aws-lambda)

What is AWS Lambda?
AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.
<br>

Name some use cases for AWS Lambdas.
individual tasks run for a short time, each task is generally self-contained, there is a large difference between the lowest and highest levels in the workload of the application.
<br>

Describe “serverless” to a non-technical friend.
Serverless means that the data is store in a cluster of servers, so servers are still involved its just not dedicated to one server.
<br>

(https://cyberhoot.com/cybrary/content-delivery-network-cdn/)

What is a CDN?
A Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast delivery of Internet content. A CDN allows for the fast transfer of data needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos.
<br>

How does a CDN work with relation to the website visitor?
CDNs work through servers nearest to the website visitor respond to the request. The content delivery network copies the pages of a website to a network of servers that are spread out at geographically different locations, caching the contents of the page. When a user requests a webpage that is part of a content delivery network, the CDN will redirect the request from the originating site’s server to a server in the CDN that is closest to the user and deliver the cached content. CDNs will also communicate with the originating server to deliver any content that has not been previously cached. In turn, the speed is improved by distributing content closer to the website visitors by using a nearby CDN server, causing visitors to experience faster page loading times. In simpler terms, for example, instead of a user in London trying to access a server in LA, which can cause slower Internet speeds, the user would be redirected through a CDN that is geographically closest to them (London, Paris, Stockholm, etc). As of today, the majority of web traffic goes through through CDNs, including traffic from major sites like Facebook, Netflix, and Amazon.
<br>

What are the benefits of employing a CDN?
Employing a CDN doesn’t only speed up the delivery of Internet content, it helps protect your website against certain forms of cyber attacks, such as Denial of Service attacks. It protects against these threats because CDNs allow for the handling of more traffic and withstanding hardware failure better than many origin servers. 
