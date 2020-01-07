# ALB-Baseline-Lab
ARM Template Deployment of the on premises domain for the Azure Lab Builders Baseline Lab




<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frandy2ner%2FALB-Baseline-Lab%2Fmaster%2FALBBaselineLab.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>

ARM Deployment will create 4 VMs named based on a Prefix provided:
Domain Controller
Azure AD Connect Server
ADFS Server
WAP Server

These VMs will be configured to Auto Shutdown based on the time supplied.  It also statically assigns IP address 10.9.0.100 to the Domain Controller and configures the virtual network clients to point to this IP for DNS.
