# PowerShell-Interview
Document Resources, Topics, Questions and Tips for a PowerShell Development Interview

# Questions

### What is PowerShell?
### How does powershell differ from other scripting languages
### PowerShell versions and differences
### Execution Policies
### CIM vs WMI
### Automatic variables
### Parameter binding
    * By Value
    * By PropertyName
### Powershell Pipelines
### Out-Host, Write-Output, Write-Host
### Num. of ways to create an object
### How to rename a variable
### Explain what is the function of $input variable?
### Whats is $_ and $PSItem variable
### What are two ways of extending PowerShell?
    PSSnapins
    Modules

### You have a script which uses Read-Host to prompt the user for an IP address. You need to make sure the user inputs a valid IP address. How would you do that ?

Splitting the address in 4 elements and try to cast them to a [byte]

A regular expression [regex]

Cast the input string to the [System.Net.IPAddress] class

### Advanced Functions
### CredSSP issues in PowerShell and workarounds
### PSRemoting
    * How to enable?
    * What is Implicit remoting
### Try, Catch, Finally
### Errors
    * terminating, non-terminating errors
    * throw
    * Write-error    
    * $ErrorActionVariable, -ErrorAction parameter


# Topics

## SOAP and REST API


|SOAP|REST|
|--|--|
|SOAP stands for **Simple Object Access Protocol**| REST stands for **Representational State Transfer**|
|SOAP has been around a while|REST is a newcomer and fixes few problems with SOAP|
|Relies exclusively on XML|Can also use other smaller message/data formats like JSON, CSV or even RSS|
|Have to use XML for requests by making RPC calls, and response if received in XML as well|REST relies on a simple URL in many cases|
|Slow, requires bandwidth|Fast - lighter weight alternative|
|In-Built error handling| NA |
|SOAP is **a protocol**. SOAP was designed with a specification. It includes a **WSDL (Web Service Definition Language)** file which has the required information on what the web service does in addition to the location of the web service.| REST is an Architectural style in which a web service can only be treated as a RESTful service if it follows the constraints of being Client ,Server, Stateless, Cacheable, Layered System, Uniform Interface|
|SOAP cannot make use of REST since SOAP is a protocol and REST is an architectural pattern.|REST can make use of SOAP as the underlying protocol for web services, because in the end it is just an architectural pattern.|
|SOAP uses service interfaces to expose its functionality to client applications. In SOAP, the WSDL file provides the client with the necessary information which can be used to understand what services the web service can offer.|REST use Uniform Service locators to access to the components on the hardware device.|
|SOAP requires more bandwidth for its usage. Since SOAP Messages contain a lot of information inside of it, the amount of data transfer using SOAP is generally a lot.|REST does not need much bandwidth when requests are sent to the server. REST messages mostly just consist of JSON messages. Below is an example of a JSON message passed to a web server. You can see that the size of the message is comparatively smaller to SOAP. **{"city":"Mumbai","state":"Maharastra"}**|
|Tranfer on HTTP, FTP and SMTP etc| Only HTTP|



