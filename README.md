# Knative-demo
Knative for serverless 

[YouTube Demo](https://youtu.be/p0xx9yTcya8)

**Tools**

 1. The Knative Command Line Interface [https://knative.dev/docs/client/install-kn/#verifying-cli-binaries](https://knative.dev/docs/client/install-kn/#verifying-cli-binaries)

*You'll need a Kubernetes cluster of some kind. In the demo, I use the free OpenShift Developer's Sanbox. You can create a free Red Hat account at [developers.redhat.com](developers.redhat.com). Alternatively, you can also use [OpenShift Local](https://developers.redhat.com/products/openshift-local/overview) is a terrific development environment.

 2. The OpenShift Command Line Interface

You can download these tools together through the OpenShift Developer Sandbox console by clicking on the [Help and clicking Command Line tools.](https://cookbook.openshift.org/accessing-an-openshift-cluster/where-can-i-download-the-openshift-command-line-tool.html)


3. A sample application

You're welcome to use my sample Quarkus app from my Quay repository. Otherwise, please try your own app and experiment with how it responds when deployed with Knative. ***Not all runtimes are appropriate for Serverless***. i.e., long spin up times from zero.

4. Some kind of load testing tool to throw lots of traffic at your serverless app!
In my demo, I use the terrific [fortio](https://github.com/fortio/fortio) tool, which is part of the Isitio project. Howeve,r another great tool to try is [Dddosify](https://ddosify.com/)
