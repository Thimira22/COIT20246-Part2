# Cloud Services Evaluation

## Introduction

As part of Truelec's ongoing efforts to modernize and expand its infrastructure, a **cloud migration** strategy has been considered. Cloud computing offers several benefits, including **scalability**, **flexibility**, **reliability**, and the ability to reduce capital expenditure on physical hardware. Truelec is exploring whether migrating its **network infrastructure** and services (e.g., **HR systems**, **CRM servers**, **Booking servers**) to the cloud would offer **cost benefits** and improve overall **network performance**.

This evaluation focuses on two of the most widely used cloud providers: **Amazon Web Services (AWS)** and **Microsoft Azure**. The objective is to compare the **cost-effectiveness**, **scalability**, and **performance** of cloud-based virtual machines (VMs) offered by AWS and Azure and determine which provider is better suited for hosting Truelec’s infrastructure. Additionally, the evaluation considers the **security features**, **integration with existing systems**, and **overall reliability** of each platform.

---

## Cloud Provider Comparison

### **1. Amazon Web Services (AWS)**

**Amazon Web Services (AWS)** is a leading cloud provider that offers a wide range of services including **compute**, **storage**, **database**, and **networking** solutions. AWS is known for its **high scalability**, **flexibility**, and extensive **global reach**, making it an ideal option for businesses that require **on-demand computing power**.

#### **AWS EC2 Pricing**:

**AWS EC2 (Elastic Compute Cloud)** allows users to launch **virtual machines (VMs)** on-demand. These VMs can run applications, store data, and manage network traffic. Below is the pricing for the instance we are considering for Truelec:

- **Instance Type**: `t3.medium`
  - **vCPUs**: 2
  - **RAM**: 4 GB
  - **Storage**: EBS (Elastic Block Store) - General Purpose SSD (gp3)
  - **Hourly Rate**: $0.0416 per hour
  - **Data Transfer**: $0.09 per GB after the first GB each month
  - **Storage**: $0.10 per GB/month for general-purpose SSD

#### **Cost Breakdown** (For One Instance Running 24/7 for 5 Years):
| **Component**         | **Cost**         |
|-----------------------|------------------|
| **Hourly Cost**       | $0.0416          |
| **Monthly Cost**      | $30.00           |
| **5-Year Total Cost** | $1,440.00        |
| **Data Transfer Cost**| $0.09 per GB     |
| **Storage Cost**      | $0.10 per GB     |

#### **Advantages of AWS**:
- **Scalability**: AWS offers **auto-scaling** features that allow businesses to scale computing resources up or down based on usage. This flexibility makes AWS ideal for **dynamic workloads**.
- **Global Reach**: AWS has **data centers** in multiple geographic regions, ensuring low-latency access for global users and enabling disaster recovery solutions.
- **Advanced Security**: AWS provides extensive security features such as **Virtual Private Cloud (VPC)**, **Identity and Access Management (IAM)**, **Security Groups**, and **Key Management Services (KMS)** for encrypting data in transit and at rest.

#### **Disadvantages of AWS**:
- **Pricing Complexity**: AWS’s **pricing structure** is complex, and without careful management, costs can become difficult to predict.
- **Costs** Can Rise Quickly: While AWS offers an **on-demand pricing model**, the cost may increase over time, especially when scaling or using data transfer outside of AWS’s infrastructure.

---

### **2. Microsoft Azure**

**Microsoft Azure** is a **cloud computing service** offered by Microsoft that provides a variety of cloud services, including **virtual machines**, **storage**, **databases**, **analytics**, and **networking**. Azure is particularly beneficial for businesses already using **Microsoft products** such as **Windows Server** and **SQL Server**.

#### **Azure VM Pricing**:

**Azure Virtual Machines (VMs)** provide scalable compute resources in the cloud. Below is the pricing for the VM instance we would recommend for Truelec:

- **Instance Type**: `Standard_B2ms`
  - **vCPUs**: 2
  - **RAM**: 8 GB
  - **Storage**: Standard SSD
  - **Hourly Rate**: $0.0384 per hour
  - **Data Transfer**: $0.087 per GB
  - **Storage**: $0.12 per GB/month for standard SSD

#### **Cost Breakdown** (For One Instance Running 24/7 for 5 Years):
| **Component**         | **Cost**         |
|-----------------------|------------------|
| **Hourly Cost**       | $0.0384          |
| **Monthly Cost**      | $28.80           |
| **5-Year Total Cost** | $1,350.00        |
| **Data Transfer Cost**| $0.087 per GB    |
| **Storage Cost**      | $0.12 per GB     |

#### **Advantages of Azure**:
- **Integration with Microsoft Products**: Azure offers seamless integration with **Microsoft tools** such as **Windows Server**, **SQL Server**, and **Active Directory**, making it an excellent choice for businesses that already rely on these products.
- **Hybrid Cloud Solutions**: Azure supports **hybrid cloud architectures**, which allow businesses to run some applications on-premises and others in the cloud, providing a **flexible infrastructure**.
- **Security**: Azure includes advanced **security measures** such as **Azure Security Center**, **DDoS Protection**, **Encryption**, and **Compliance** with global standards (GDPR, ISO 27001).

#### **Disadvantages of Azure**:
- **Configuration Complexity**: Some users may find **Azure’s interface** and configuration options more difficult to navigate compared to AWS, especially if they are new to the platform.
- **Cost Variability**: Like AWS, Azure’s **pay-as-you-go model** can result in **cost fluctuations** if not properly managed.

---

## Total Cost Analysis

### **Total Cost Over 5 Years (for One Instance)**:
Here is the **comparison** between AWS and Azure based on a **single instance** running continuously for **5 years** (24/7), without **reserved instances** or **discounts**.

| **Cloud Provider** | **Instance Type**   | **Hourly Cost** | **Monthly Cost** | **5-Year Total Cost** |
|--------------------|---------------------|-----------------|------------------|-----------------------|
| **AWS EC2**        | t3.medium           | $0.0416         | $30.00           | $1,440.00             |
| **Microsoft Azure**| Standard_B2ms       | $0.0384         | $28.80           | $1,350.00             |

### **Additional Costs**:
- **Data Transfer**:
  - AWS: $0.09 per GB (after the first GB each month)
  - Azure: $0.087 per GB
- **Storage**:
  - AWS: $0.10 per GB/month for SSD
  - Azure: $0.12 per GB/month for SSD

---

## Conclusion

Based on the **cost comparison** and additional factors, **Microsoft Azure** is the **more cost-effective option** for running a **virtual machine instance** continuously over a **5-year period**. It offers a **lower total cost** ($1,350) compared to AWS ($1,440) for the same instance type.

While **AWS** provides more flexibility in terms of scaling and global infrastructure, **Azure’s seamless integration with Microsoft products** and slightly **lower cost** make it the best choice for Truelec, especially if the company is already using **Windows Server** and **SQL Server**.

For future **scalability** and **cost optimization**, we recommend exploring **Azure Reserved Instances** or **Hybrid Cloud Solutions** to further optimize costs while maintaining high performance and availability.

---

## Recommendation

After evaluating both **AWS** and **Microsoft Azure**, we recommend **Microsoft Azure** for Truelec’s cloud infrastructure needs. Azure's cost-effectiveness, robust **security features**, and strong integration with **Microsoft products** make it the ideal solution for Truelec’s network infrastructure. Moving forward, **Reserved Instances** or **Hybrid Cloud Solutions** should be considered to maximize **cost efficiency** and ensure future scalability.

---

This concludes the **Cloud Services Evaluation** for Truelec, providing a comprehensive **comparison** and **recommendation** between **AWS** and **Microsoft Azure**, based on pricing, scalability, and overall suitability for Truelec’s network infrastructure.