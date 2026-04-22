# Azure Onboarding Summary Report

## 1. Selected Region

I selected **West Europe (Netherlands)** as my primary Azure region.

### Reason:
- It is geographically closest to my location (Nigeria)
- Provides lower latency compared to other regions
- Offers high availability and broad service support

---

## 2. Availability Zones

Availability Zones are physically separate datacenters within a region.

### Importance:
- Improve fault tolerance
- Ensure high availability
- Protect against datacenter-level failures

---

## 3. Deployed Resource

I deployed a **Storage Account** as my test resource.

### Configuration:
- Resource Group: rg-learning-azure
- Region: West Europe
- Performance Tier: Standard

---

## 4. Shared Responsibility Model

The Shared Responsibility Model defines how security responsibilities are divided between Microsoft Azure and the customer.

### Microsoft (Cloud Provider) Responsibilities:
- Physical datacenter security
- Hardware maintenance
- Networking infrastructure
- Host OS and virtualization layer

### My Responsibilities (Customer):
- Data security and encryption
- Access control (RBAC)
- Resource configuration
- Monitoring and usage

### Application to My Resource:
For the Storage Account:
- Azure secures the infrastructure and storage hardware
- I am responsible for:
  - Managing access permissions
  - Securing stored data
  - Monitoring usage and costs

---

## 5. Cost Management

I accessed the Cost Management + Billing section and reviewed:
- Cost Analysis dashboard
- Budget configuration tools

### Importance:
- Prevent overspending
- Monitor free-tier usage
- Set alerts for spending thresholds

---

## Conclusion

This exercise helped me understand:
- Azure portal navigation
- Resource organization using Resource Groups
- Importance of region selection
- Security responsibilities in cloud computing
- Cost monitoring and budgeting
