# AppInsights-Spring-Boot-Demo

# Introduction 

This sample is based upon the documentation at https://docs.microsoft.com/en-us/java/azure/spring-framework/configure-spring-boot-java-applicationinsights

The sample is an empty Spring Boot Web application with a test controller, and pre-wired Application Insights.

# Getting Started

1.	This sample requires JDK 1.8 or greater.
2.  This sample requires Maven 3.0 or greater.
2.	This sample was built and tested with VS Code on Windows 10

# Testing

1.  Create an instance of Application Insights in your Azure subscription.
2.  Configure your system with the prerequisites.
3.  Edit the application.properties and replace <your key here> with the Instrumentation Key of your Application Insights instance. This key is available on the Overview information in the Azure Portal.
4.  Build the app: mvn clean package
5.  Run the app: mvn spring-boot:run
6.  Go to the test contoller using either a local browser or curl: http://localhost:8080/sample/hello 
7.  In Application Insights, you should see telemetry in a few minutes. You can verify that the console output debug and trace messages are published to Application Insights by running a query on the Traces object.

# License

**MIT License**

*Copyright (c) 2018 Jim Priestley*

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
