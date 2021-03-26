Basic Use Cases
=====
This section gives an overview of basic use cases and functionality of the plug-in framework.

> [!NOTE]
> This content may be out-of-date. To check the latest information on this topic, inspect the libraries using the Visual Studio Object Browser.


Basic Use Cases
----
The basic use cases and features will be explained using an example application. The application is a simple console application that allows you to send a message using a message transmitter of your choice. The requirement is that these message transmitters should be pluggable.

The following topics will be covered:

* [Defining an Extension Point](core/defining_an_extension_point.md): Defining an extension point so the host application can receive extensions.
* [Creating Extensions](core/creating_extensions.md): Developing an extension for a specific extension point.
* [Creating the Host Application](core/creating_the_host_application.md): Consuming the available extensions within the host application.