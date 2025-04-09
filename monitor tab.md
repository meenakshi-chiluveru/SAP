two applications are connecing through different types of adaptor 
in sap cpi we have many adaptors according to type of application
in the iflow sender and receiver side adaptors functionalities are different behaves different because sender side is not our control receiver we can do any action like get post delete etc..

# system does not know anything we need to tell what to do how to do system will not commit any mistakes we do mistakes we have recify it 
# How to trace errors while developing the iflow

after deploy iflow we have to trigger message before sending message we have refresh token url or generate new token [click on new access token]
for every 30 minutes we have to generate token url in postman and use token token willbe active for one hour and i send message i got an error 500 internal server error because i given host address wrong but that sytem dont know how to handle

if we get error we hve to rectify for that we have a solution trace 

message integration content: 
in this we can go log configration and changed the log level to trace it will be stay for 10 minutes
1. monitor message processing: in that we can see failed messages tile
2. click one failed message we can see one details of failed message we click on trace on logs tab
3. we can see complete picture error 
