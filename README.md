# Spring Cloud Function example

## Exposed Functions as Endpoints
- *Supplier* - `/supply` - returns an output

```
curl -H 'Content-Type: text/plain' http://localhost:8080/supply
Hello Dhruv⏎                                                                                                      

```

- *Consumer* - `/consume` - expects an input

```
curl -H 'Content-Type: text/plain' http://localhost:8080/consume -d 'Hello Dhruv'
```

- *Function* - `/function` - expects an input and output
```
curl -H 'Content-Type: text/plain' http://localhost:8080/function -d 'Hello Dhruv'
Hello Dhruv⏎    
```

- *Function* - `/hello` - expects an input and output
```                                                                                        
curl -H 'Content-Type: text/plain' http://localhost:8080/hello -d 'Dhruv'
Hello Dhruv⏎  
```
