GCP-workbook

# Categories of GCP Infrastructure and Services:

1. Storage

2. Compute

3. Networking

4. Security

1. Storage

    1. Taxonomy of storage solutions on GCP.

![image alt text](image_0.png)

    2.  Storage solutions use cases.

![image alt text](image_1.png)

![image alt text](image_2.png)

![image alt text](image_3.png)

2. Compute Choices

    3. Taxonomy of compute services/solutions on GCP

![image alt text](image_4.jpg)

    4. Cloud Use Cases:

### Hosting a website - Relatively basic

### Running a Hadoop Cluster - Big Data

### Serving a TensorFlow Model - Machine Learning

1. Hosting a Website

![image alt text](image_5.png)

![image alt text](image_6.png)

![image alt text](image_7.png)

![image alt text](image_8.png)

![image alt text](image_9.png)

![image alt text](image_10.png)

![image alt text](image_11.png)

![image alt text](image_12.png)

![image alt text](image_13.png)

![image alt text](image_14.png)

![image alt text](image_15.png)

![image alt text](image_16.png)

![image alt text](image_17.png)

![image alt text](image_18.png)

![image alt text](image_19.png)

![image alt text](image_20.png)

![image alt text](image_21.png)

![image alt text](image_22.png)

![image alt text](image_23.png)

![image alt text](image_24.png)

![image alt text](image_25.png)

![image alt text](image_26.png)

![image alt text](image_27.png)

2. Containers (GKE Google Kubernetes Engine)

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

Container images become containers at runtime and in the case of Docker containers - images become containers when they run on [Docker Engine](https://www.docker.com/products/container-runtime). Available for both Linux and Windows-based applications, containerized software will always run the same, regardless of the infrastructure. Containers isolate software from its environment and ensure that it works uniformly despite differences for instance between development and staging.

![image alt text](image_28.png)

* Containers v/s VMs

Containers are an abstraction at the app layer that packages code and dependencies together. Multiple containers can run on the same machine and share the OS kernel with other containers, each running as isolated processes in user space. Containers take up less space than VMs (container images are typically tens of MBs in size), can handle more applications and require fewer VMs and Operating systems.

Virtual machines (VMs) are an abstraction of physical hardware turning one server into many servers. The hypervisor allows multiple VMs to run on a single machine. Each VM includes a full copy of an operating system, the application, necessary binaries and libraries - taking up tens of GBs. VMs can also be slow to boot.

### GKE

![image alt text](image_29.png)

![image alt text](image_30.png)

![image alt text](image_31.png)

![image alt text](image_32.png)

![image alt text](image_33.png)

![image alt text](image_34.png)

