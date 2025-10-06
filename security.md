# Cybersecurity Risk Assessment

## Introduction

This section provides a **cybersecurity risk assessment** for **Truelec**'s network infrastructure. The goal is to identify and assess key **security risks**, propose relevant **security controls** to mitigate those risks, and provide recommendations for improving the **overall security posture** of Truelec's network. We will evaluate **8 security threats** from the provided template and select **3 security controls** from the **NIST SP800-53** framework.

## Risk Identification

Below are **8 security threats** identified for Truelec’s network:

1. **Malware**:
   - **Risk Level**: High
   - **Description**: Malware, such as **ransomware** and **viruses**, can infect systems and lead to data loss, system outages, and loss of productivity.

2. **Data Breach**:
   - **Risk Level**: High
   - **Description**: Unauthorized access to sensitive data (e.g., **HR data**, **financial data**) can result in reputational damage, legal action, and regulatory penalties.

3. **Denial of Service (DoS) Attack**:
   - **Risk Level**: Medium
   - **Description**: A DoS attack could overwhelm network resources, causing disruption of services and loss of connectivity.

4. **Unauthorized Access**:
   - **Risk Level**: High
   - **Description**: Users or attackers gaining unauthorized access to internal systems or data could compromise **confidential information** and **network integrity**.

5. **Phishing Attacks**:
   - **Risk Level**: Medium
   - **Description**: **Phishing** attacks could trick employees into revealing sensitive information like **login credentials** or infecting systems with malware.

6. **Insider Threats**:
   - **Risk Level**: Medium
   - **Description**: Employees or contractors with access to critical systems could misuse their privileges, leading to data theft or damage.

7. **Weak Encryption**:
   - **Risk Level**: Low
   - **Description**: Weak encryption or lack of encryption for sensitive data could expose data in transit or at rest to interception and theft.

8. **Physical Security**:
   - **Risk Level**: Medium
   - **Description**: Lack of proper physical security controls could allow unauthorized individuals to access servers or network devices, leading to potential data theft or hardware tampering.

## Data Assets

The following **4 critical data assets** are considered vital to Truelec’s operations:

1. **HR Data**:
   - Includes sensitive employee information (e.g., **personal identification**, **salary data**, **employment history**).
   
2. **Customer Information**:
   - Contains personal data of customers (e.g., **contact details**, **payment information**, **service usage**).
   
3. **Financial Data**:
   - Includes **financial records**, **accounts** data, and **transaction history**.
   
4. **Intellectual Property**:
   - Includes proprietary data, such as **designs**, **business strategies**, and other sensitive corporate knowledge.

## Risk Levels

Each risk has been evaluated for its **potential impact** and **likelihood**. The following **risk levels** have been assigned:
- **High**: These risks have a significant impact on the organization and are likely to occur if not addressed.
- **Medium**: These risks may result in some impact and occur intermittently.
- **Low**: These risks are less likely to occur and may have minimal impact if they do.

## Recommended Security Controls

Based on the identified risks, the following **3 security controls** from **NIST SP800-53** are recommended to mitigate these risks:

### **1. Control: Access Control (AC-1)**
   - **Applicable Risk(s)**: Unauthorized Access, Insider Threats
   - **Control Description**: Implement **access control policies** to restrict system access based on **user roles** and **least privilege**.
     - **Implementation**: 
       - Use **Role-Based Access Control (RBAC)** to define access levels.
       - Require **multi-factor authentication (MFA)** for accessing sensitive systems or data.
     - **Benefit**: Reduces the risk of unauthorized access by ensuring that users only have access to the data and systems necessary for their roles.

### **2. Control: Security Training (AT-1)**
   - **Applicable Risk(s)**: Phishing Attacks, Malware
   - **Control Description**: Conduct **security awareness training** for all employees to recognize phishing attempts and follow proper security practices.
     - **Implementation**: 
       - Train employees on **email phishing**, **password security**, and safe internet browsing habits.
       - Conduct **regular phishing simulations** to ensure employees can identify and avoid suspicious emails.
     - **Benefit**: Reduces the likelihood of employees falling victim to **phishing attacks** and **malware infections**.

### **3. Control: Data Encryption (SC-12)**
   - **Applicable Risk(s)**: Weak Encryption, Data Breach
   - **Control Description**: Encrypt sensitive data both **in transit** and **at rest** to prevent unauthorized access.
     - **Implementation**:
       - Use **TLS/SSL** for encrypting data transmitted over the network.
       - Implement **AES-256 encryption** for storing sensitive data such as **HR** and **customer data**.
     - **Benefit**: Ensures that even if data is intercepted, it cannot be read without the proper decryption key.

---

## Conclusion

In this risk assessment, we identified and evaluated 8 key cybersecurity threats and recommended 3 security controls to mitigate the highest-priority risks. The implementation of these controls will help protect **Truelec’s network** and **critical data assets** from potential cyber threats, ensuring a more secure and resilient network infrastructure. By focusing on **access control**, **security training**, and **data encryption**, we can significantly reduce the likelihood of a successful attack while ensuring compliance with industry best practices.