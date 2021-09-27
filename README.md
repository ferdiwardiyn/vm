# Virtual Machines CI
1. create account and get token ngrok in ngrok.com
2. create account github and login
3. import/fork github repository https://github.com/ferdiwardiyn/vm
4. check your github repository
5. go to Settings->Secrets->new repository secrets
6. enter the name NGROK_AUTH_TOKEN and value <Paste Your token ngrok> and click Add Secret button
7. go to github repository https://github.com/<your username>/vm
8. go to Actions->Select Workflows->Select CI->Run Workflows
9. Waiting 10 minutes and check status in https://dashboard.ngrok.com/endpoints/status
10. copy hostname
  example: 8.tcp.ngrok.io:83009
11. go to apps RDP Client
12. Paste hostname
13. login with user runneradmin and password Techgay11
14. click connect and done.
  
  
 *Note 
  this vm/rdp running 6 jam
