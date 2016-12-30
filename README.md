# MuleSoft
Complete SOA Enterprise Architecture now available in an easy to use ESB by MuleSoft

## Salesforce Example

This example application demonstrates how to use MuleSoft Anypoint Studio to build a simple HTTP application to query Salesforce. 
After reading this document, creating and running the example in Mule, you should be able to leverage what you have 
learned to create an HTTP request-response application that is able to retrieve requested data from Salesforce instance 
based on your criteria.

### Assumptions

This document describes the details of the example within the context of Anypoint™ Studio, Mule ESB’s graphical user interface (GUI). 
This document assumes that you are familiar with Mule ESB and the [Anypoint Studio interface](http://www.mulesoft.org/documentation/display/current/Anypoint+Studio+Essentials). 
To increase your familiarity with Mule Studio, consider completing one or more [Anypoint Studio Tutorials](http://www.mulesoft.org/documentation/display/current/Basic+Studio+Tutorial).

### Get the Code
```
git clone https://github.com/markbutton/salesforce.git 
```

### Set Up and Run the Example

Follow the procedure below to create, then run the **Salesforce Example** application.

1. Open the Example project in Anypoint Studio.
2. In your application in Studio, click the **Global Elements** tab. Double-click the HTTP Listener global element to open its **Global Element Properties** panel. Change the contents of the **port** field to required HTTP port e.g. 8081
3. Go to Global Elements and open Salesforce Connector element. Fill in your Salesforce credentials including the [security token](https://help.salesforce.com/apex/HTViewHelpDoc?id=user_security_token.htm).
4. Run the application.
5. Open your browser and hit **http://localhost:8081/salesforce**. 
6. You will see the retrieved data structure.

### Cloudhub deployment

This demo has also been deployed to Cloudhub so it can be used with the salesforce-ui example.  This shows how you can build 
and deploy a full iPaaS solution in a matter of minutes using MuleSolft, Salesforce and Angular 2.


### Go Further

- Learn more about the [HTTP endpoint](http://www.mulesoft.org/documentation/display/current/HTTP+Connector).
- Learn more about the [Mule Expression Language](http://www.mulesoft.org/documentation/display/current/Mule+Expression+Language+MEL) 
- Learn more about the [Expression component](http://www.mulesoft.org/documentation/display/current/Expression+Component+Reference) 
- Learn more about the [Salesforce component](http://www.mulesoft.org/documentation/display/current/Salesforce+Connector)
- Learn more about the [Error Handling](http://www.mulesoft.org/documentation/display/current/Error+Handling)
