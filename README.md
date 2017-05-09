# Deploy a Free Cloudera training environment over Google Cloud Engine
Ideal guide for whom who wants to get familiar with Cloudera Hadoop distribution and would like to setup a cluster from scratch using the Google Cloude free subscription. <br/>
This is a study guide I made for the Cloudera Certified Administrator (CCA) that I am preparing. This is for test exam code CCA-131 (https://www.cloudera.com/more/training/certification/cca-admin.html). <br/>
I took the class offered from Cloudera and I used the O'Reilly book "Hadoop The Definitive Guide (4th edition)" to study. 
I also used the Cloudera support website documentation. The Apache Hadoop website is also a great site for even more documentation.
<br/><br/>

The following are the main steps I went through:
1. Open and configure a proper training VM environment on Google Cloud Engine
2. Install and configure Cloudera Manager and CDH
3. Perform basic and advanced configuration needed to effectively administer a Hadoop cluster
4. Maintain and modify the cluster to support day-to-day operations in the enterprise
5. Enable relevant services and configure the cluster to meet goals defined by security policy; demonstrate knowledge of basic security practices
6. Benchmark the cluster operational metrics, test system configuration for operation and efficiency
7. Demonstrate ability to find the root cause of a problem, optimize inefficient execution, and resolve resource contention scenarios
<br/><br/>

# Setup Google Cloud Engine environment
In this course, I will install Cloudera Manager and CDH (Cloudera Distribution including Apache Hadoop) on five virtual machines (VMs) running in the cloud (Google Cloud Engine), exploiting the free trial period (around 1 month). These are referred to as the “cluster VMs”. <br/>
All the VMs use the Centos 7 distribution and they have the following specifications: <br/>
  * lion: n1-standard-2 (2 vCPU, 7 GB memory)
  * elephant: n1-standard-1 (1 vCPU, 3.75 GB memory)
  * tiger: n1-standard-1 (1 vCPU, 3.75 GB memory)
  * horse: n1-standard-1 (1 vCPU, 3.75 GB memory)
  * monkey: n1-standard-1 (1 vCPU, 3.75 GB memory)
