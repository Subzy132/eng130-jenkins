# Jenkins

### What is CI?

Continuous Integration is the practice of regularly merging their code into a main branch. After it has been tested an ran and ready for final deployment. 

The benefits are that you are able to find and attend to bugs quicker, improve the software quality and reduce the time it takes to validare new software updates. 

### What is CD?

It could mean continuous deployment or continuous delivery. It essentially is a practice that allows the developers to have automatically prepared something for release to production. All the code is sent to a test environement and allows the developers to carry out unit tests on it. 

The benefits are that the developers automate testing beyond just unit tests so they can verify application updates across multiple dimensions before deploying to customers

### What is CDE

Common data environment. 

### What is the difference between C delivery and C deployment?

The main difference between delivery and deployment is that continuous deployment will be automatically deployed without having the need of an approval by the developer whereas continous delivery will automate the entire process up until the end where it then waits for the developer's approval to be deployed to the live production environement.

### What is a webhook? 

It is some sort of web call back. It is a way for an application to provide other applications with real-time information. It provides data as it is happening. This essentially means that you get the data immediately rather having to set up frequent polls to get it in real time. 

---


![Alt text](/images/CICD.png)

---

# Jenkins

### Stages

There are 4 stages to the continuous delivery pipeline in Jenkins. These being the Build Stage, Deploy Stage, Test Stage and Release Stage.

![Alt text](/images/Stages.png)

A piece of code that is ready to be deployed needs to go through each of these stages before it is released to a live production. It is a thorough check at each stage and must pass. 
### How does it work?


Jenkins is a Java-based open-source automation platform with plugins designed for continuous integration. It is used to continually create and test software projects, making it easier for developers and DevOps engineers to integrate changes to the project and for consumers to get a new build

### benefits of using Jenkins?

- It is open source and it is user-friendly, easy to install and does not require additional installations or components.
  
- It is free of cost.

- Easily Configurable. Jenkins can be easily modified and extended. It deploys code instantly, generates test reports. Jenkins can be configured according to the requirements for continuous integrations and continuous delivery.
  
- Platform Independent. Jenkins is available for all platforms and different operating systems, whether OS X, Windows or Linux.

- Rich Plugin ecosystem. The extensive pool of plugins makes Jenkins flexible and allows building, deploying and automating across various platforms.
- Easy support. Because it is open source and widely used, there is no shortage of support from large online communities of agile teams.


### Who is using Jenkins?

Companies like Facebook, Netflix and udemy use the application Jenkins to help with their CI/CD pipelines.

### What other tools are available as automation servers? 

- Circle CI
- TeamCity
- Bamboo
- Gitlab