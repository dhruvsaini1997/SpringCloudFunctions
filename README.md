# SpringCloudFunctions
Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@dhruvsaini1997 
TechPrimers
/
spring-cloud-function-example
1
110
 Code
 Issues 0
 Pull requests 0 Actions
 Projects 0
 Wiki
 Security 0
 Insights
spring-cloud-function-example/README.md
@MovingToWeb MovingToWeb [initial commit] Spring Cloud Example
1db5fa3 on Jul 15, 2019
28 lines (21 sloc)  878 Bytes
  
Spring Cloud Function example
Exposed Functions as Endpoints
Supplier - /supply - returns an output
curl -H 'Content-Type: text/plain' http://localhost:8080/supply
Hello Dhruv                                                                                                      

Consumer - /consume - expects an input
curl -H 'Content-Type: text/plain' http://localhost:8080/consume -d 'Hello Dhruv'
Function - /function - expects an input and output
curl -H 'Content-Type: text/plain' http://localhost:8080/function -d 'Hello Dhruv'
Hello TechPrimer⏎    
Function - /hello - expects an input and output
curl -H 'Content-Type: text/plain' http://localhost:8080/hello -d 'Dhruv'
Hello Dhruv⏎ 
