# aws

.  ABP News Case Study
ABP News is an Indian Hindi news channel owned by ABP Group. It is a free to air TV channel founded in 1998. It was formerly known as STAR News before being acquired by ABP Group. 
ABP News Network (ANN)—one of the largest TV networks in India—operates five news channels in Indian languages such as Hindi, Marathi, Bengali, Punjabi, and Gujarati, and reaches out to more than 150 million TV audiences per week.
Challenges Faced by ABP.
News in India can occur in a more dynamic, volatile, and unpredictable way compared to other international markets. This means spikes in traffic to digital and mobile news services can occur at any time of the day with minimal warning. A major breaking news story can increase traffic by three times, rising to six times for elections that may occur as often as once a year.
It was therefore extremely important for ANN to scale the technology infrastructure quickly to support these traffic spikes.
In 2013, ANN predicted extending its digital presence from a single website to a range of services could increase its page views from 150 million to over 500 million. The business had to sustain this growth cost-effectively while delivering the responsiveness and reliability that digital consumers demanded. “Considering all the factors in play, we wanted a robust, cost-optimized infrastructure that was reliable and highly scalable.
1.  Unfortunately, ANN’ existing managed service provider technology infrastructure could not meet these challenges.
2.  ANN could not gain the visibility to control and optimize its use of infrastructure resources.
3.  ANN risked not being able to deliver news quickly to meet viewer demands for immediacy and secure a strong position in the competitive digital news market in India.
Why Amazon Web Services
ANN brought its web infrastructure back into an on-premises data center as an intermediate step toward moving to a public cloud. To prepare for that move, the company started conducting due diligence on leading public cloud services with Amazon Web Services (AWS).
In 2014, the company decided to migrate its infrastructure, applications, and services to AWS.
“We selected AWS because of the flexibility to align our infrastructure costs and consumption with demand, and the ease and simplicity with which we could move to the AWS Cloud,” says Gondal. “AWS also specializes in infrastructure services that enable businesses like ours to distribute video content and mobile applications to users’ smartphones, tablets, and personal computers.”
ANN completed its initial migration to AWS in only four months and has continued to expand the services running in the public cloud architecture to include additional websites, mobile applications, and a video content management system.
ANN uses Amazon Simple Storage Service(Amazon S3) to store video files and Amazon Elastic Compute Cloud (Amazon EC2) to run the system used to manage the video content. Amazon Elastic Transcoder converts ANN’ video files from source to different formats for viewing on a range of devices.
 ANN elected to use AWS Lambda to deliver an architecture that seamlessly updates content feeds served from Amazon S3 to mobile users without requiring the management and maintenance of a single server.
Key to ANN’ success is its choice of AWS services to run its mobile applications. 
Benefits.
·       Using AWS has enabled ANN to support its increase in page views from 150 million to 500 million and accommodate sharp spikes in traffic with high performance when significant news events, including elections, occur.
·       ANN has also successfully extended its portfolio of products and services from a single website to several websites, video content and a mobile application, since migrating to the AWS Cloud. 
·       Furthermore, through competitive pricing offered by AWS, including regular reductions and being able to pay only for the infrastructure resources used, ANN has been able to control costs and budget effectively.
·       Using AWS has given ANN the confidence to evaluate using advanced tools such as machine learning and artificial intelligence to deliver on a range of new products. 
2.   Buzzdial Case Study
Founded in 2013, Buzzdial builds technologies that enable publishers and broadcasters, as well as brands, to supplement television shows with a cross-screen digital experience that can be accessed on viewers’ computers, tablets and mobile phones, and integrated with the broadcast.
The Challenge
Buzzdial needed to launch onto an infrastructure that could keep costs low during the business’s establishment stage, and increase expenditure as more clients started using the service. The organization also wanted to pay for infrastructure on demand rather than invest in servers, storage, and networking resources that would remain underutilized except during traffic peaks for an hour or two during high-profile broadcast events. The infrastructure had to be highly available and scalable to support traffic during these events. In addition, the infrastructure also had to support Buzzdial’s plans to operate in several markets, and locate its services in data centers close to prospective clients and viewers to minimize latency that could disrupt the viewers’ second screen experience during television programs.
Why Amazon Web Services
Buzzdial selected Amazon Web Services (AWS) as a cloud service provider that could meet its needs. The business worked closely with AWS solution architects in New Zealand to determine the best architecture for its service. To boost Buzzdial’s confidence, AWS shared stories about successful AWS customers, provided access to businesses that were undertaking similar projects, and demonstrated deep technical knowledge.
Buzzdial then developed the first stage of its service and created the supporting AWS architecture in four weeks. Initially the business created a monolithic web application that was not optimized for continuous development. As Buzzdial learned more about how AWS performed, its engineers opted to break the application up into a series of smaller, interoperating pieces. This process has enabled Buzzdial to pursue an agile software development process over the last 18 months, involving regular releases and continuous development.
Buzzdial’s application now runs in Amazon Elastic Compute Cloud (Amazon EC2) instances residing behind Elastic Load Balancing to distribute incoming traffic in such a way as to maximize fault tolerance and minimize latency. The application is distributed across discrete application programming interface, web delivery, caching, and database layers. Amazon Route 53 provides domain name services (DNS) that connect viewers with the required resources in AWS, while Amazon Relational Database Service (Amazon RDS) for MySQL provides a relational database engine to support the service.
Other services used include Amazon Simple Storage Service (Amazon S3) and Amazon CloudFront which provide a content delivery network for all static web resources including images, scripts, and style sheets. This significantly decreases load on the Amazon EC2 instances.
The Benefits
·       Buzzdial is now delivering a service that meets the demanding requirements of prominent broadcasters, brands, and rights-holders such as the Seven, Ten, and SBS television networks in Australia, ITV in Britain, the New Zealand Herald newspaper, and the All Blacks rugby union team.
·       The caliber of clients and importance of its second-screen service to their businesses requires Buzzdial to undertake detailed monitoring and quality assurance processes. 
·       Buzzdial can provision resources to support hundreds of thousands of concurrent users coming onboard in a 10-minute period, and scale further if needed. If a customer conducts a broadcast event but fails to notify Buzzdial, the service provider can still scale in 10 to 15 minutes to support 10s of thousands of concurrent users.
·       Buzzdial calculates that its capital and operating costs for infrastructure are 96 percent lower over two to three years than they would be with a physical infrastructure in a collocated data center.
·       Buzzdial plans to add new AWS services in future as business grows.
 
 
 
 
 
 
 
 
 
 
 
3.   Classle Case Study
Classle is a cloud-based social learning platform that allows students to connect with other students as well as experts and professionals from academic, research institutes and industry. The goal of the company’s platform is to assist students pursuing higher education learn and develop skills in a manner unencumbered by socio-economic, location and resource barriers. Classle, a social enterprise, is currently focusing on rural regions of India where students struggle with resource limitations.
Why Amazon Web Services
Amazon Web Services (AWS) has been the foundation of Classle’s infrastructure since the company’s inception. Vaidya Nathan, Founder and CEO-Classle, explains that AWS allowed the company to begin operations six months ahead of schedule and more economically than had been anticipated. Classle is also impressed with the growing list of additional services offered by AWS, which the company has embraced to help further its own expansion.
Over the past two years, other services coming from AWS like Amazon Relational Database Service (Amazon RDS), Amazon CloudFront, Amazon CloudWatch, Elastic Load Balancing, and Amazon Route 53 confirm that the decision was the right one. As a startup, we have to worry about balancing scalability with cash preservation, and we get the best of both worlds with AWS. We see AWS as a strategic fit for our long-term business strategy.”
Classle uses Amazon Elastic Compute Cloud (Amazon EC2), with the Amazon Elastic Load Balancing (Amazon ELB), Auto Scaling, and Amazon Elastic Block Storage (Amazon EBS) features, to handle its application and analytics server needs. Amazon RDS acts as Classle’s data warehouse and transactional database.
Amazon Simple Storage Service (Amazon S3), with the Reduced Redundancy Storage (RRS) feature, serves the dual function of providing Classle’s content downloads and acting as an origin server for Amazon CloudFront. The company has established Amazon’s content delivery service Amazon CloudFront as an edge server for streaming files and delivering the learning platform’s most requested video downloads
The company monitors its AWS infrastructure with Amazon CloudWatch and uses Amazon Simple Notification Service (Amazon SNS) to delivery system load alerts to its developers. Additionally, Classle routes its users to its websites with Amazon’s Domain Name System (DNS) service, Amazon Route 53.
The Benefits
·      Able to expand social learning platform globally
·      Reduced webpage load times by 180 per cent
·      Reduced time-to-market to just two days
 
