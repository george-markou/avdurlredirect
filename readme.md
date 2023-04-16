# AVD URL Redirect web app


[Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview) is a service that automatically builds and deploys full stack web apps to Azure from a code repository. Use this repo with the [quickstart](https://github.com/george-markou/avdurlredirect/generate) to build and customize a new static site that will redirect http requests to the AVD service.

Here's how the AVD HTTP redirection works:

* The client queries the custom domain name avd.markou.me.
* The DNS request is resolved and the CNAME record is returned to the client.
* The client connects to the Azure Static Website.
* Azure Static Web App redirects the client to AVD public endpoint address.

![image](https://user-images.githubusercontent.com/82205061/232325641-ae6ae517-0541-4136-b306-93e1804277fc.png)
