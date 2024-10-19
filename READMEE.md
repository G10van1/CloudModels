[\[English\]](READMEE.md) [\[Português\]](README.md)

# Cloud Computing Service Models: IaaS, PaaS and SaaS

## 1. IaaS (Infrastructure as a Service)

### Definition
IaaS is a cloud service model that provides on-demand IT infrastructure, such as servers, storage, networks and operating systems, in a virtualized form. Companies use this model to create and manage their own IT environments without the need to acquire or maintain physical hardware.

### Examples
- **AWS EC2**
- **Microsoft Azure Virtual Machines**
- **Google Cloud Compute Engine**

### User Responsibility
The user is responsible for managing the operating system, middleware, applications and data, while the provider takes care of the underlying infrastructure (hardware, networks, storage).

### Case Study
**E-commerce Company using IaaS**
An e-commerce company decides to expand its operations to an international market. To handle the increased traffic, the company chooses AWS EC2 to host its application and database servers. The IT team configures the virtual machines, installs the operating system, and manages the scalability of the application. This model allows the company to quickly scale its computing resources as needed, without the need to invest in new physical servers.

---

## 2. PaaS (Platform as a Service)

### Definition
PaaS provides a ready-made platform for developing, testing, and deploying applications, without the need to manage the underlying infrastructure. The goal is to make development work easier by offering a controlled environment with all the necessary tools.

### Examples
- **Google App Engine**
- **Microsoft Azure App Service**
- **Heroku**

### User Responsibility
The user manages only the applications and data, while the provider takes care of the infrastructure, operating system, and runtime.

### Case Study
**Application Development Startup using PaaS**
A startup that develops a mobile application for personal finance management uses Heroku as a platform to quickly launch its product on the market. Developers create the application, configure the platform and integrate it with database and analytics tools. Heroku takes care of the infrastructure, load balancing and automatic scaling, allowing the development team to focus solely on improving the application without worrying about operational issues.

---
## 3. SaaS (Software as a Service)

### Definition
SaaS offers ready-to-use software directly over the internet, without the need for installation, configuration or management by the user. SaaS solutions are accessible via browser, providing a simple and integrated experience.

### Examples
- **Google Workspace**
- **Microsoft 365**
- **Salesforce**

### User Responsibility
The user simply uses the software, without worrying about maintenance, updates or infrastructure.

### Case Study
**Marketing Company Using SaaS**
A marketing company decides to adopt **Salesforce** to manage its customer relationship management (CRM). With Salesforce, the sales team can track the progress of negotiations, automate tasks and access reports in real time. The company does not need to worry about system configuration or software maintenance, since the provider takes care of everything, from updates to security.

---

## Summary of Responsibilities

| Model | Provider Responsibility | User Responsibility |
|---------|----------------------------------------|-----------------------------------------|
| **IaaS**| Infrastructure (hardware, network, storage) | Operating system, middleware, data and applications |
| **PaaS**| Infrastructure and platform (runtime, OS) | Applications and data |
| **SaaS**| Everything (software, platform, infrastructure) | Software Usage |
