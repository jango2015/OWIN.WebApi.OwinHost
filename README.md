#OwinHost.exe to host WebApi: 

Install-Package OwinHost
??? Install-Package Microsoft.AspNet.WebApi.Owin

While some will want to write a custom process to run Katana Web applications, many would prefer to simply launch a pre-built executable that can start a server and run their application. For this scenario, the Katana component suite includes OwinHost.exe. When run from within a project’s root directory, this executable will start a server (it uses the HttpListener server by default) and use conventions to find and run the user’s startup class. For more granular control, the executable provides a number of additional command line parameters.
