# BDI Hadoop/Spark – Lab 1

## Setup GCP Hadoop Cluster

### Overview of Big Data Environment

Various vendors offer big data platforms. This document focuses on setting up a big data platform using Google Cloud Platform (GCP), which provides a $300 credit. While there's an option to use a virtual box to install a Hadoop sandbox from Hortonworks, installing Hadoop locally has limitations. For instance, it's not compatible with Macbook M1 chips. For those facing challenges with GCP setup, a backup plan for local Hadoop cluster setup is provided in Appendix B.

> **Note:** Some sections of this manual might be outdated. For instance, GCP now offers a $300 credit for 90 days, not 12 months. While Google frequently updates GCP's interface and policies, most of this guide remains relevant. If updates are needed, please notify others via the Teams channel.

### Hadoop on GCP

Hadoop is an open-source big data processing framework that offers a distributed file system and a framework for processing large data sets across computer clusters. GCP offers several big data services, including those compatible with Hadoop.

Google Cloud Dataproc is a fully-managed service that allows users to run Apache Hadoop and Apache Spark jobs on Google Cloud. It provides a dynamic cluster management system, making it easier to manage and scale big data processing workloads. GCP also offers complementary services like Google BigQuery, a serverless data warehouse, and Google Cloud Storage, a scalable object storage service.

---

### How to Obtain GCP's Free Credit

This section guides you through signing up for a Google account, activating the $300 credit for 90 days, and launching a GCP project.

> **Important:** Do not use the University of Illinois Google Account for GCP as its access has been disabled. Use a personal Gmail account. A credit card is required to activate the free trial, but charges only apply after the trial ends.

Upon activating the free trial, users can opt to upgrade to a paid account, granting full access to all GCP services. However, charges apply once the $300 credit is exhausted or after 90 days. Both free and upgraded accounts serve the course's purposes, so the decision to upgrade is discretionary.

For detailed information on the free trial or billing, refer to [GCP's Free Cloud Features](https://cloud.google.com/free/docs/free-cloud-features).

---

### Creating a Project in GCP

Before launching any GCP service, start by creating a project.

---

### Setting Up a New Storage Bucket (Optional)

Google offers a bucket-based storage system, similar to AWS S3, called Google Cloud Storage. This section demonstrates setting up a storage bucket, which can later be linked to our Hadoop cluster.

---

### Creating a Hadoop and Spark Cluster in GCP

This guide illustrates launching a Hadoop and Spark cluster in GCP. For free-tier users, the total number of CPU computer engines is limited to 8 vCPU. This means you can create a 2v CPU computing engine given the need for one master node and two data nodes.

---

### Exploring the Hadoop Ecosystem with Linux Commands

Learn to navigate the GCP-created cluster using Linux commands.

---

### References

- [Creating a Hadoop Cluster on GCP](https://cloud.google.com/bigtable/docs/creating-hadoop-cluster)

---

### Appendix A – Hadoop and Linux Commands

---

### Appendix B – Setting Up a Local Hadoop Cluster (Optional)

For those who can use GCP without issues, this step is optional. However, setting up a local cluster can be beneficial for exploration after the GCP free trial concludes.

