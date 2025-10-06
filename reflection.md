# Cloud Services Evaluation

## Introduction

In this section, we will evaluate **cloud services** from two major providers—**Amazon Web Services (AWS)** and **Microsoft Azure**. These cloud providers are the top choices for hosting services and provide a range of **virtual machines (VMs)** that can be used to replace on-premises hardware. The purpose of this evaluation is to assess which cloud provider offers the most **cost-effective**, **reliable**, and **scalable** solution for **Truelec**’s network infrastructure.

## Cloud Provider Comparison

### **1. Amazon Web Services (AWS)**

AWS is a leading cloud service provider offering a wide range of services, including **compute**, **storage**, and **networking**. The key component we’ll evaluate for Truelec is **Amazon EC2** (Elastic Compute Cloud), which allows users to run virtual machines on demand.

#### AWS EC2 Pricing:
- **Instance Type**: `t3.medium` (2 vCPUs, 4GB RAM)
- **Pricing**:
  - **On-Demand**: $0.0416 per hour
  - **5-Year Total Cost (without Reserved Instances)**: $1,440.00 (based on continuous 24/7 usage)
  - **Data Transfer**: $0.09 per GB after the first GB per month
  - **Storage** (EBS): $0.10 per GB/month for general-purpose SSD

#### Advantages:
- **Scalability**: AWS provides highly flexible scaling options for compute power and storage, ideal for growing businesses.
- **Global Reach**: AWS operates in multiple geographic regions, ensuring low-latency access.
- **Advanced Security Features**: AWS provides a wide range of security controls, including **VPC** (Virtual Private Cloud) and **IAM** (Identity and Access Management).

#### Disadvantages:
- **Pricing Complexity**: AWS’s pricing model can be difficult to navigate, especially for new users.
- **Cost Fluctuations**: On-demand pricing can become expensive without proper management of instance usage.

---

### **2. Microsoft Azure**

Microsoft Azure is another major cloud service provider, with a strong offering of **virtual machines** through **Azure Virtual Machines (VMs)**. Azure is particularly beneficial for businesses already using **Microsoft products** like **Windows Server** and **SQL Server**.

#### Azure VM Pricing:
- **Instance Type**: `Standard_B2ms` (2 vCPUs, 8GB RAM)
- **Pricing**:
  - **Pay-As-You-Go**: $0.0384 per hour
  - **5-Year Total Cost (without Reserved Instances)**: $1,350.00 (based on continuous 24/7 usage)
  - **Data Transfer**: $0.087 per GB
  - **Storage**: $0.12 per GB/month for standard SSD

#### Advantages:
- **Integration with Microsoft Products**: Azure offers seamless integration with **Windows Server**, **Active Directory**, and **SQL Server**, making it an ideal choice for companies already utilizing Microsoft products.
- **Hybrid Cloud Solutions**: Azure offers great hybrid cloud capabilities, which can allow Truelec to run some services on-premises and others in the cloud.
- **Security**: Azure provides strong **security measures** including **Azure Security Center** and **Compliance offerings** such as **GDPR** and **ISO 27001**.

#### Disadvantages:
- **Complexity in Configuration**: Some users may find Azure's interface and configuration options less intuitive than other cloud providers.
- **Cost**: Similar to AWS, Azure’s **pay-as-you-go model** can become costly without proper planning and management.

---

## Total Cost Analysis

### **Total Cost Over 5 Years (for One Instance)**:
Below is a **cost comparison** for a **single virtual machine instance** running continuously (24/7) for 5 years with **no reserved instances** or discounts.

| **Cloud Provider** | **Instance Type**   | **Hourly Cost** | **Monthly Cost** | **5-Year Total Cost** |
|--------------------|---------------------|-----------------|------------------|-----------------------|
| **AWS EC2**        | t3.medium           | $0.0416         | $30.00           | $1,440.00             |
| **Microsoft Azure**| Standard_B2ms       | $0.0384         | $28.80           | $1,350.00             |

### **Additional Costs**:
- **Data Transfer**:
  - AWS: $0.09 per GB (after the first GB each month)
  - Azure: $0.087 per GB
- **Storage Costs**:
  - AWS: $0.10 per GB/month for SSD
  - Azure: $0.12 per GB/month for SSD

### **Conclusion**:
Based on the cost analysis, **Microsoft Azure** offers the **most cost-effective solution** for running a **virtual machine** continuously over a 5-year period, with a **lower total cost** than AWS. However, if Truelec is already using Microsoft products like **Windows Server** and **SQL Server**, Azure’s seamless integration may be a significant advantage.

---

## Recommendation

After considering the **pricing** and **additional factors**, we recommend **Microsoft Azure** for Truelec's cloud infrastructure needs. Azure's cost-effectiveness, along with its strong integration with Microsoft products and robust **security features**, make it an excellent choice for Truelec’s growing network. 

For future scalability, we suggest utilizing **Azure Reserved Instances** or **Hybrid Cloud Solutions** to further optimize costs while ensuring high performance and availability.

---

This concludes the **Cloud Services Evaluation** for Truelec, providing a detailed comparison and recommendation between **AWS** and **Microsoft Azure** based on pricing, scalability, and suitability for Truelec’s infrastructure.