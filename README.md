# Cloud Computing – Recommendation Report (Max Horn | 10621467) 

## Table of Contents

1. [INTRODUCTION-OF-“TRUE FRUITS”](#Introduction of “true fruits”)
2. [IT-INFRASTRUCTURE](#IT-Infrastructure)
3. [EVALUATION-OF A-CLOUD-SOLUTION](#Evaluation of a Cloud solution)
4. [RECOMMENDATION-OF-DEPLOYMENT](#Recommendation of Deployment)
5. [SOURCES](#Sources)	


## Introduction of “true fruits”

The medium-sized company “True Fruits GmbH” was founded in 2006 in Bonn, Germany. It has 31 workers and a revenue of 43 million Euros per year. Their production is focused on fresh-made smoothies. 

## IT-Infrastructure

The IT infrastructure is kept very simple since they only have one location where they are working. The production is set up at other production plants. Since freelancing jobs and home office opportunities were denied, it indicates hardware, non – cloud or traditional IT infrastructure. 
“A traditional infrastructure consists of the usual hardware and software components like Facilities, data centers, servers, network hardware, desktop computers, and enterprise application software solutions”. (IBM, 2022)
Generally, this type of infrastructure setup requires lots of power, physical storage, and the most money. Therefore, traditional infrastructure is installed on-site and used in the enterprise. 
Compared to a cloud–based infrastructure it is similar. However, users are able to get access to the infrastructure over the internet. That means that IT resources must not be downloaded physically on a server and can be used virtually. “Virtualization connects physical servers, which are separated worldwide from a service provider. Resources are partitioned and abstracted to make them accessible to users anywhere there is an internet connection.”. 
(IBM, 2022)
Therefore, a cloud is creating possibilities to outsource data centers, servers, and network hardware. This brings the fortune, that the company is saving money since a third-party supplier is taking care of IT problems and installation. In addition, workers are not bounded anymore on a fixed working place, like on on-site desktops and the company have not to spend a lot of money on its own software licenses (e.g. using SaaS and PaaS).




## Evaluation of a Cloud solution

For the company a cloud solution is recommended, since they have a small size of workers and it makes it easier for sharing important data and to react fast to impedances on the market. Furthermore, they have a big online shop. When there are high volumes of orders or even clicks, you can react to them faster and increase capacity. Workers can work in remote, anywhere where is an internet connection. Therefore, applications can be used over the cloud, which makes it more flexible and cheaper e.g. “Microsoft 365”. Parallel to the flexibility aspect, there is also the advantage of scalability. “The provider has far greater resources than the customer company and can therefore adapt the capacities for computing power, storage and network throughput to demand at any time. “ (ahd, 2021)


## Recommendation of Deployment

Out of the four deployment models of a cloud (private, public, community and hybrid cloud) “(the Hybrid Cloud) encompasses the best features of the abovementioned types.”  
(Yuliya, 2021)

 
![Cloud Deployment](https://www.sam-solutions.com/blog/wp-content/uploads/2021/06/hybrid-cloud@2x-min.png "Cloud Deployment Overview")

The hybrid solution is not cheapest one. However, a company should suggest about risk. If it comes to a data breach the costs can be very high. Thus, “the cost of lost assets must be balanced against the cost of securing the network; your company must decide how much risk it is willing to take.”
 (Laird, 2022) 

Summarized, the deployment of a Hybrid Cloud is the best solution, since IT service is laid on third-party companies and the own company is flexible and agile in reacting on different cases on the market. It will also increase your options like rapid scalability on demand (e.g. IaaS) and business beyond building, which means you can work from anywhere. It is friendlier for the environment and your bank account, since you reduce travel to work and you share your resources in a cloud. 



## Sources

ahd, 2021. ahd a proact company. [Online] 
Available at: https://www.ahd.de/welche-cloud-loesungen-fuer-unternehmen-gibt-es/
[Accessed 13 November 2022].

IBM, 2022. IBM. [Online] 
Available at: https://www.ibm.com/de-de/topics/infrastructure
[Accessed 9 November 2022].

Laird, P., 2022. Cloud Security and Risk management, moodle: s.n.

Yuliya, S., 2021. sam-solutions. [Online] 

Available at: https://www.sam-solutions.com/blog/four-best-cloud-deployment-models-you-need-to-know/
[Accessed 10 November 2022].

















# Docker Getting Started Tutorial

This tutorial has been written with the intent of helping folks get up and running
with containers and is designed to work with Docker Desktop. While not going too much 
into depth, it covers the following topics:

- Running your first container
- Building containers
- Learning what containers are running and removing them
- Using volumes to persist data
- Using bind mounts to support development
- Using container networking to support multi-container applications
- Using Docker Compose to simplify the definition and sharing of applications
- Using image layer caching to speed up builds and reduce push/pull size
- Using multi-stage builds to separate build-time and runtime dependencies

## Getting Started

If you wish to run the tutorial, you can use the following command after installing Docker Desktop:

```bash
docker run -d -p 80:80 docker/getting-started
```

Once it has started, you can open your browser to [http://localhost](http://localhost).

## Development

This project has a `docker-compose.yml` file, which will start the mkdocs application on your
local machine and help you see changes instantly.

```bash
docker-compose up
```

## Contributing

If you find typos or other issues with the tutorial, feel free to create a PR and suggest fixes!

If you have ideas on how to make the tutorial better or new content, please open an issue first before working on your idea. While we love input, we want to keep the tutorial  scoped to newcomers.
As such, we may reject ideas for more advanced requests and don't want you to lose any work you might
have done. So, ask first and we'll gladly hear your thoughts!
