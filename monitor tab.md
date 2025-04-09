two applications are connecing through different types of adaptor 
in sap cpi we have many adaptors according to type of application
in the iflow sender and receiver side adaptors functionalities are different behaves different because sender side is not our control receiver we can do any action like get post delete etc..

# system does not know anything we need to tell what to do how to do system will not commit any mistakes we do mistakes we have recify it 
# How to trace errors while developing the iflow

after deploy iflow we have to trigger message before sending message we have refresh token url or generate new token [click on new access token]
for every 30 minutes we have to generate token url in postman and use token token willbe active for one hour and i send message i got an error 500 internal server error because i given host address wrong but that sytem dont know how to handle

if we get error we hve to rectify for that we have a solution trace 
monitor: to rectify error of message we use monitor tab
monitor - integrations and APIs -  -message status overview - we have many status types like failed,retry,completed,processing,escalated

monitor message processing: we can check error message details

how to find error: 
1. go to manage integration conetent we have the status of the iflow
2. after the clicking artifact go to log configuration and change the log level to trace and resend message once trace will be active for 10 minutes
3. trace data will be active for one hour

monitor message processing: we have failed messages and we logs in that we have trace option click that we can see message processing run 
we can mess flow 
