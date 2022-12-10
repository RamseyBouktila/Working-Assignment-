# Ramsey Bouktila 10582121, CA Report-B9MG119 

Introduction: This is report we will review the current IT set up of a small but rapidly growing drinks manufacturer and recommend a cloud strategy appriopirate with a business of this size and scope. Underpinning our analysis and recommendations will be cost considerations, resource allocation, security and scalability. 

We will start by providing a short backgorund to the company, Boann Distillery, before working addressing the current IT set up and providing recommendations on the direction or potential to utilize and migrate those fuctions to the cloud. The areas of focus in this report on Customer Relationship Management, Company Website, Ecommerce function/Online store and email comunication. 

# **Boann Distillery-Company Background:** 

Boann Distillery is a modern whiskey distillery located in Drogheda, Co.Meath. The 50,000ft2 facility contains a whiskey distillery, craft beer brewery and taphouse, visitor centre bar and onsite restaurant. 

Outside the brick and mortar, Boann Distillery is also an online business with a growing portion of the business done through the online store which is accessed through the company website. 

Established in 2015 by the Cooney family Boann Distillery employees around 80 people and sells a niche range of whiskies, craft beer and gins. 

Boann Distillery has ambishions to become the leading independent distillery and craft brewry in Ireland and has received finanical support from Enterprise Ireland in recent years. (Ref)

## **Current IT Set up and recommendations:** 

In this section we look at components of the current IT set up and make recommendations on future delpoyments. With each recommendation we aim to provide rationale and sound justification based on cost, security, scalability and resource allocation. 

Of the three types of standard services available on the cloud, Infastructure as a service (IaaS), Platform as a service (PaaS) and Software as a service (SaaS) we will focus primarily on SaaS as that is the most apprioptate and obvious way for to realize the benfits of cloud computing for a business the size and complexity of Boann. (Srinivasan). PaaS and IaaS are primarily better utilized by larger more complex organizations. The benefits a smaller organization has is that adoption of cloud services enable agility and flexibility. 

### **Customer Relationship Management**: 

Boann currently utilize a homegrown CRM backend system on a server on site. The CRM is configured provisioned to provide user access. This nessesitates that all employees who need access have all relevant software installed on their desktops. This involves dedicated IT administration resources to track, update and support the software. While this apprach has worked so far as the customer base grows and more customer information can be collected and stored there is a potential to utilize that information to provide better customer service and to inform marketing campaigns. The additional opportunity however creates additional strain on internal resources and there is also a lack of true expertise on the team. 

Other challenges include underutilization of the hardware (server). Backing up customer data is also laborious and needs to be kept off site for security and risk midigation purposes. Another common challenge is the access to the data when offsite or away from the company issued devices. Confidential Business data on laptops and other devices maybe at risk. There is also a risk that the server represents a single point of failure. 

### *CRM Recommendation* 

Move to SaaS, like Saleforce.com. Salesforce are the world's leading CRM provider and they have offerings specifically tailored to small and growing buisnesses. 

An added benefit to this approach is because it is offered on public cloud it is relatively cost effective as public cloud benefits greatly from ecomonies of scale and can be offered on a pay-per-usage basis which will eliminate redundacies and free up internal resources. 

The subcription model also provides a opportunity to absort the cost as an operating expense rather than a capital expense which will be important as Boann continues to grow and the need for capital funds grows with expansion plans. 

## **Company website:** 

Currently the website is hosted on a dedicated web server which was configured with the requirement in mind to handle customer traffic during their peak period which coninsides with the Christmas period. As Boann is a business with growth aspriations and a degree of seasonality, the servers were provisioned to such scale to accomodate the high traffic of the busy period. Therefore the capacity is typical under utilized.

###*Recommendation*: 

We recommend the company website moves to the cloud hosted on Azure, this will allow for scalability while experiencing growth as compute power can be added easily. 

Advantages  | Disadvantages 
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

### ** Online store:**

Currently using self hosted platform Magento, this is maintained in house on internal servers. These servers need to be maintained and upgraded regularily. 

While the open source Megento platform was useful in the early days of Boann, the online store is becoming increasing burdened as the business grows and now represents a significant portion of revenue generation. 

The team which maintains the online store are not emcommerce experts and development is costly, furthermore our analysis revealed potential revenue loss due to abondoned shopping carts. Dedicated ecommerce providers such as Shopify offer services to track events like this and follow up with the customer potentially increasing reveue. There was also incidents where the online store was running slow during periods of heavy traffic.  

The current set up also represents a security risk as the eCommerce store is dealing with sensitive customer infomation such as credit cards. 

### *Recommendation*: 

Move to cloud platform like Shopify, this outsources this vital component of Boann's business to subject matter experts who can help design and optimize the online store which can result in higher sales. Also frees up resources internally and allows the business to scale more efficently. 

The cloud hosted solution will also provide reliability as the provider can take care of all server maintenance and upgrades to keep the store available at all time and running in a fast and secure manner. It is highly unlike Boann can provide this level of security and service alone given IT and resource contraints.  

## **Email:** 

Currently using Office 365. This allows the business to quickly and easily comminicate internally and externally. We would recommend to keep this service on the cloud as the cost and effort to maintain and manage an Exchange server to high. Subscription to the service allows Boann to pay for what they use and avoid cost and complexity. 

### *Recommendation* 

Do not change.

## **Accounting software**

Currently using Quickbooks desktop, this is working well and allows 

Advantages   | Disadvantages 
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

# **Final Thought** 

While a small business today. Given it’s growth ambishions a cloud strategy would be recommended this is partly due to the high level of automation built into service provisioning, this is benficial as Boann can configure and their cloud service rapidily and deploy them quickly. (Srinivasan, 2014)

To meet industry compliance, as a company in the food and beverage sector there are regulatory requirements which must be met. 

## *Other benefits*, 

service relability. Service availability. Business continuity. Ability to pay as you go. Meet demand elastisity. High end computing services on demand. 

# *Risks to cloud*: 

Lack of control over computing infastructure, the possibility of data leakage during processing. As a small business, the path to midigating this risk is not finacially or technologically viably and would include utilizing a private cloud enviroment. Another risk is privacy and security controls. Cloud Service providers do not assume the responsibility to protect and secure customer data, Boann as the cloud customer is responsible for protecting this information (Weinman 2012, Gellman 2009). Encryption can be used to midigate this risk with the encryption key stored at the customer site?

Cloud outages and service distruption risk, this exists and is more privilant in in-house companies. Infrastructure capacity and resource availability favors cloude service providers to restore service faster than a single customer managing their own data center. 

