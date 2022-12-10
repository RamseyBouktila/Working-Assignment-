# Ramsey Bouktila 10582121, CA Report-B9MG119 

Introduction: This is report we will review the current IT set up of a small but rapidly growing drinks manufacturer and recommend a cloud strategy appropriate with a business of this size and scope. Underpinning our analysis and recommendations will be cost considerations, resource allocation, security, and scalability. 

We will start by providing a short background to the company, Boann Distillery, before addressing the current IT set up and providing recommendations on future deployement. The areas areas of focus of this report will be Customer Relationship Management, Company Website, Ecommerce function/Online store and email communication. 

## **Boann Distillery-Company Background:** 

Boann Distillery is a modern whiskey distillery located in Drogheda, Co. Meath. The 50,000ft2 facility contains a whiskey distillery, craft beer brewery and taphouse, visitor centre bar and onsite restaurant. 

Outside the brick and mortar, Boann Distillery is also an online business with a growing portion of the business done through the online store which is accessed through the company website. 

Established in 2015 by the Cooney family Boann Distillery employees around 80 people and sells a niche range of whiskies, craft beer and gins. 

Boann Distillery has ambitions to become the leading independent distillery and craft brewery in Ireland.

## **Current IT Set up and recommendations:** 

In this section we look at components of the current IT set up and make recommendations on future deployments. With each recommendation we aim to provide rationale and sound justification based on cost, security, scalability, and resource allocation. 

Of the three types of standard services available on the cloud, Infrastructure as a service (IaaS), Platform as a service (PaaS) and Software as a service (SaaS) we will focus primarily on SaaS as that is the most appropriate and obvious way for to realize the benefits of cloud computing for a business the size and complexity of Boann. (Srinivasan, 2014). PaaS and IaaS are primarily better utilized by larger more complex organizations. The benefits a smaller organization has is that adoption of cloud services enable agility and flexibility. 

## **Customer Relationship Management**: 

Boann currently utilize a homegrown CRM backend system on a server on site. The CRM is configured provisioned to provide user access. This necessitates that all employees who need access have all relevant software installed on their desktops. This involves dedicated IT administration resources to track, update and support the software. 

While this approach has worked so far as the customer base grows and more customer information is being collected there is a potential to utilize that information to provide better customer service and to inform marketing campaigns and support sales. Capitializing on these opportunities will create additional demands on internal resources and there is also a lack of true expertise on the team. 

Other challenges include underutilization of the hardware (server). 

Backing up customer data is laborious and needs to be kept off site for security and risk mitigation purposes. 

Another challenge is remote access. Confidential Business data on laptops and other devices maybe at risk. 

### *CRM Recommendation* 

Move to SaaS, like Saleforce.com. Salesforce are the world's leading CRM provider, and they have offerings specifically tailored to small and growing businesses. 

An added benefit to this approach is because it is offered on public cloud it is relatively cost effective as public cloud benefits greatly from economies of scale and can be offered on a pay-per-usage basis which will eliminate redundancies and free up internal resources. 

The subscription model also provides an opportunity to absorb the cost as an operating expense rather than an upfront capital expense which will be important as Boann continues to grow and the need for capital funds grows with expansion plans. 

## **Company website:** 

Currently the website is hosted on a dedicated web server which was configured with the requirement in mind to handle customer traffic during peak periods. As Boann is a business with growth aspirations and a degree of seasonality, the servers are provisioned to accommodate the high traffic of the busy period. Therefore, the capacity is often underutilized.

### *Recommendation*: 

We recommend the company website moves to the cloud hosted on Azure, this will allow for scalability while experiencing growth as compute power can be added easily. 

## **Online store:**

Currently using self-hosted platform Magento, this is maintained in house on internal servers. These servers need to be maintained and upgraded regularly. 

The online store is becoming increasing burdened as the business and traffic grows and now online sales now represents a significant portion of revenue generation. 

The team who designed and maintain the online store are not e-commerce experts and development and enhancements are costly. There were also incidents where the online store was running slow during periods of heavy traffic.  

The current set up also represents a security risk as the eCommerce store is dealing with sensitive customer information such as credit cards. 

### *Recommendation*: 

Move to cloud platform like Shopify, this outsources this vital component of Boann's business to subject matter experts who can help design and optimize the online store which can result in higher sales. Also frees up resources internally and allows the business to scale more efficiently. 

The cloud hosted solution will also provide reliability as the provider can take care of all server maintenance and upgrades to keep the store available at all times and running in a fast and secure manner. 

It is highly unlike Boann can provide this level of security and service alone given IT and resource constraints. We recommend it is better to focus on Boann's core business in this instance. 

In the area of security; It is important to note however that Cloud Service providers do not assume the responsibility to protect and secure customer data, Boann as the cloud customer is responsible for protecting this information (Weinman 2012, Gellman 2009). Encryption can be used to mitigate this risk. 

## **Email:** 

Currently using Office 365. This allows the business to communicate internally and externally quickly and easily. We would recommend keeping this service on the cloud as the cost and effort to maintain and manage an Exchange server to high (Srinivasan, 2014). Subscription to the service allows Boann to pay for what they use and avoid cost and complexity. 

### *Recommendation* 

No change.

## **Final Thoughts** 

While a small business today. Given its growth ambitions a cloud strategy would be recommended this is partly due to the high level of automation built into service provisioning, this is beneficial as Boann can configure and their cloud service rapidly and deploy them quickly. Infrastructure capacity and resource availability also favours cloud service providers to restore service faster than a single customer managing their own data centre. (Srinivasan, 2014).

### *Summary of additional benefits and disadvantages* 

Advantages   | Disadvantages 
------------- | -------------
Service relability  | Lack of control over computing infrastructre 
Service availability  | Possibility of data leakage during processing
Business continuity   | Privacy concerns and security controls
Ability to pay as you go |Cloud outages and service disruption risk, note, this exists and is more prevalent in in-house companies
High end computing services on demand |

### *References* 

Srinivasan, S 2014, Cloud Computing Basics, Springer New York, New York, NY. Available from: ProQuest Ebook Central. [10 December 2022].

Weinman, J. (2012). Cloudonomics: The business value of cloud computing . New York: Wiley.Available from: ProQuest Ebook Central. [06 December 2022].




