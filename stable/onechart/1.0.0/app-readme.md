<br>
# oneChart
 
Similar to "Launch Docker Image", this chart deploys images using repositories, but formatted similar to Kubernetes manifests rather than Docker.
 
OneChart's origin project was to simplify the deployment of applications using Kubernetes (k3s) on TrueNAS SCALE for rapidly deploying mostly stateful applications.  It has morphed into a simplified manifest formatted chart, that can be used to replace docker-compose.
 
oneChart opens up flexibility that isn't currently available in TrueNAS SCALE, which allows users to break many best practices, that are common for learning, development, or Home Lab environments.  As such load balanced, high availability, and clustered applications are not a requirement and IP port management becomes a focus.
 
A basic understanding of Kubernetes will be needed to understand many principles and this project has therefore moved away from a simple flow.  If you're looking for a straightforward simple chart, please take a look at oneApp (not currently released) or the official "Launch Docker Image" from TrueNAS.
 
If you desire a maintained plugin repository for applications, please take a look at TrueCharts.  TrueCharts developers have put a lot of work into making application deployment consistent to resolve upstream inconsistencies and breaking changes.
 
<br>
Please have an understanding of best practices for your requirements, before continuing...
 
<br>
<br>
<br>
