# Deploy sample infrastructure

**Let deploy infrastructure using deploy button from github**
1. Login into azure subscription
    ```
    az login
    ```
2. Push button Deploy to Azure

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FLeonidChetverikov%2Fterrafy%2Fmain%2FInfrastructureAzure%2Fvm1.json)

This button will deploy Virtual mashine in ressource group, add nsg exception, and create virtual network.