# Working-Assignment-

# **Company Background:** 

Boann Distillery is a modern whiskey distillery located in Drogheda, Co.Meath. The 50,000ft2 facility contains a whiskey distillery, craft beer brewery and taphouse, visitor centre bar and onsite restaurant. 

Outside the brick and mortar, Boann Distillery is also an online business with a portion of the business done through the online store available through the company website. 

Established in 2015 by the Cooney family Boann Distillery employees around 80 people and sells a range of whiskey craft beer and gins. 

Boann Distillery aims to become the leading independent distillery and craft brewry in Ireland and has received support from Enterprise Ireland. 

## **Current IT Set up and recommendations:** 

In this section we look at components of the current IT set up and make recommendations on future delpoyments. With each recommendation we aim to provide rationale and sound justification based on cost, security and resource allocation. 

### **Customer Relationship Management**: 

Homegrown CRM backend system on a server on site. The CRM is configured provisioned to provide user access. This nessesitates that all employees who need access have all relevant software installed on their desktops. This involves dedicated IT administration resources to track, update and support the software. The server (hardware) is also underutilized. Backing up customer data is also laborious and needs to be kept off site for security and risk midigation purposes. Another common challenge is the access to the data when offsite or away from the company issued devices. Confidential Business data on laptops and other devices maybe at risk. There is also a risk that the server represents a single point of failure. 

### *CRM Recommendation* 

Move to SaaS, like Saleforce.com Public Cloud is cost effective, 

Advantages  | Disadvantages
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

## **Company website:** 

Website is hosted on a dedicated web server which was configured with the requirement in mind to handle customer traffic during their peak period which is around the Christmas time. As a business with groth apriations and a degree of seasonality servers were provisioned and need to be miantained that of intentionally larger than required and are more often (hardware) underutilized. 

###*Recommendation*: 

We recommend the company website moves to the cloud hosted on Azure, this will allow for scalability while experiencing growth as compute power can be added easily. 

Advantages  | Disadvantages 
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

### ** Online store:**

Currently using homegrown ecommerce hosted on servers, 

### *Recommendation*: 

Move to cloud platform like Shopify, this outsources this vital component of Boann's business to subject matter experts who can help design and optimize the online store which can result in higher sales. Also frees up resources internally and allows the business to scale more efficently. 

Advantages  | Disadvantages 
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

## **Email:** 

Currently using Office 365. This allows the business to quickly and easily comminicate internally and externally. We would recommend to keep this service on the cloud as the cost and effort to maintain and manage an Exchange server to high. Subscription to the service allows Boann to pay for what they use and avoid cost and complexity. 

### *Recommendation* 

Do not change.

## **Accounting software**

Advantages   | Disadvantages 
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

## **Material Resource Planning** 

Currently using a on premise solution which aids in the planning and scheduling of manufacturing activities. 

# **Final Thought** 

While a small business today. Given it’s growth ambishions a cloud strategy would be recommended this is partly due to the high level of automation built into service provisioning, this is benficial as Boann can configure and their cloud service rapidily and deploy them quickly. (Srinivasan, 2014)

To meet industry compliance, as a company in the food and beverage sector there are regulatory requirements which must be met. 

## *Other benefits*, 

service relability. Service availability. Business continuity. Ability to pay as you go. Meet demand elastisity. High end computing services on demand. 

# *Risks to cloud*: 

Lack of control over computing infastructure, the possibility of data leakage during processing. As a small business, the path to midigating this risk is not finacially or technologically viably and would include utilizing a private cloud enviroment. Another risk is privacy and security controls. Cloud Service providers do not assume the responsibility to protect and secure customer data, Boann as the cloud customer is responsible for protecting this information (Weinman 2012, Gellman 2009). Encryption can be used to midigate this risk with the encryption key stored at the customer site?

Cloud outages and service distruption risk, this exists and is more privilant in in-house companies. Infrastructure capacity and resource availability favors cloude service providers to restore service faster than a single customer managing their own data center. 

