read this guide to be able to generate the structure 

https://learn.microsoft.com/es-mx/azure/logic-apps/create-single-tenant-workflows-visual-studio-code

main function reference 

https://learn.microsoft.com/en-us/cli/azure/logicapp/deployment/source?view=azure-cli-latest#az-logicapp-deployment-source-config-zip

checklist

* does affect existing workflow? no
* does it affect existing webjob? pending
* does it affect exiting workflow if name is the same? yes  and also override any existing flow defined on there
* does it support statefull flow? yes
* does it support stateless flow? yes
* does it support flow with service provider conection? yes
* does it support flow with api conection? yes


produce the following output
![image](https://github.com/paying-services/logicapp-standard-workflow/assets/16611331/f448d534-f668-4fbb-9c74-4bfc5a6da9e0)

important notes

* having multiple workflow in a single logic app with standard plan require to adjust the standard plan resource asignment to be able to have all the workflow working correctly
