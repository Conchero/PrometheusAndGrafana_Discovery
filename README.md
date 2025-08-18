### How to 

[From this page](https://prometheus.io/download/#prometheus) :
* Download prometheus and node explorer
* Extract them

### Grafana and prometheus linkage
[Go to Grafana page and create your account](https://grafana.com/auth/sign-up/create-user):
* Create a prometheus dashboard
<img width="1028" height="418" alt="image" src="https://github.com/user-attachments/assets/9d61563f-a259-4914-9491-2f8c2c761349" />
* The yml file is all ready to go ! Just replace the <info> with your credentials given at account
* then execute
  *  ```<prometheus file path (most likely in "prometheus-*-*-*" folder)> --config-file=<path to prometheus yml file>```
 
then you should see Running and traffic info shown !
