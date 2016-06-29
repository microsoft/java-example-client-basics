DeployR Java Client Library Basics
==================================

The following tutorial demonstrates a wide range of basic functionalities available on the [DeployR Java Client Library](http://deployr.revolutionanalytics.com/docanddown/#clientlib). These examples make concrete the ideas introduced by the [Quick Start Tutorial](http://deployr.revolutionanalytics.com/documents/dev/clientlib) for developers using the client library.


- [About: Client Library](#about-client-library)
- [Tutorial: Get Connected](#tutorial-get-connected)
- [Tutorial: Get Authenticated](#tutorial-get-authenticated)
- [Tutorial: Authenticated Project Services](#tutorial-authenticated-project-services)
- [Tutorial: Authenticated Background Services](#tutorial-authenticated-background-services)
- [Tutorial: Authenticated Repository Services](#tutorial-authenticated-repository-services)
- [Tutorial: Anonymous Project Services](#tutorial-anonymous-project-services)
- [Tutorial: Running The Examples](#tutorial-running-the-examples)
- [License](#license)


### About: Client Library

The [DeployR API](http://deployr.revolutionanalytics.com/documents/dev/api-doc/) exposes a wide range of DeployR-powered R analytics services to client application developers. To simplify the integration of DeployR services within client applications, several client libraries are provided for [Java, JavaScript and .NET](http://deployr.revolutionanalytics.com/docanddown/#clientlib) developers. 

### Tutorial: Get Connected

The first step for any client application developer using the Java client library is to establish a connection with the DeployR server. Further information detailing connections can be found [here](http://deployr.revolutionanalytics.com/documents/dev/clientlib/#connection).

### Tutorial: Get Authenticated

Once a connection to the DeployR server has been established the next step for a client application developer is to decide if end-users or the application itself needs access to authenticated services on the API.

If authenticated project, background job or repository management services are needed by the application then the application must first authenticate. If an application only uses anonymous services then the application can operate anonymously, without ever authenticating. Further information detailing authenticaton can be found [here](http://deployr.revolutionanalytics.com/documents/dev/clientlib/#authentication).

### Tutorial: Authenticated Project Services

An authenticated user or simply an authenticated client application has access to the full range of authenticated services offered on the DeployR API. Further information detailing authenticated project services can be found [here](http://deployr.revolutionanalytics.com/documents/dev/clientlib/#authprojects).

### Tutorial: Authenticated Background Services

An authenticated user or simply an authenticated client application has access to the full range of authenticated services offered on the DeployR API. Further information detailing authenticated background services can be found [here](http://deployr.revolutionanalytics.com/documents/dev/clientlib/#background).

### Tutorial: Authenticated Repository Services

An authenticated user or simply an authenticated client application has access to the full range of authenticated services offered on the DeployR API. Further information detailing authenticated repository services can be found [here](http://deployr.revolutionanalytics.com/documents/dev/clientlib/#repository).


### Tutorial: Anonymous Project Services

An anonymous user, being any user that has not authenticated with the DeployR server, only has access to anonymous services offered on the DeployR API. There is just one single services category for anonymous services, anonymous project services. Further information detailing anonymous project services can be found [here](http://deployr.revolutionanalytics.com/documents/dev/clientlib/#anonservices).

### Tutorial: Running The Examples

Use the [DeployR CLI](https://github.com/microsoft/deployr-cli) to download and run the java-example-client-basics examples.

## License ##

Copyright (C) 2010-2016, Microsoft Corporation

This program is licensed to you under the terms of Version 2.0 of the
Apache License. This program is distributed WITHOUT
ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING THOSE OF NON-INFRINGEMENT,
MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. Please refer to the
Apache License 2.0 (http://www.apache.org/licenses/LICENSE-2.0) for more 
details.
