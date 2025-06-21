**AZ-104: Microsoft Azure Administrator** certification. 

## ✅ **AZ-104 Practice Scenario: Azure Infrastructure Deployment for Contoso Ltd.**

### 📘 **Background:**

Contoso Ltd. is a mid-sized company transitioning from on-premises to the Azure cloud. You have been hired as an Azure Administrator to deploy and manage their cloud resources.

---

## 🧩 **Scenario Objectives:**

### 1. **Resource Group and Resource Deployment**

* Create a new **Resource Group** named `ContosoRG-EastUS`.
* Deploy a **Windows Server 2022 VM** in East US with the following specs:

  * Name: `ContosoVM01`
  * Size: `Standard_B2ms`
  * Admin username: `AdminUser`
  * Password: `StrongP@ssword123!`
  * Public IP with a DNS name: `contosovm01-eastus`

### 2. **Storage Management**

* Create a **Storage Account** named `contosostorageprod` (globally unique).
* Enable **soft delete** for blobs.
* Create a **blob container** named `docs`, and upload a sample file (`company-policy.pdf`) with private access.

### 3. **Virtual Network Configuration**

* Create a **VNet** named `ContosoVNet` with address space `10.1.0.0/16`.
* Add a **subnet** named `AppSubnet` with address range `10.1.1.0/24`.
* Associate the VM’s NIC with this subnet.

### 4. **Monitoring and Alerts**

* Enable **Boot diagnostics** for `ContosoVM01` using the Storage Account.
* Create an **alert rule** that sends an email when CPU usage is over 80% for 5 minutes.

### 5. **Role-Based Access Control (RBAC)**

* Create a custom **Azure AD group** named `ContosoVMAdmins`.
* Add a user `jdoe@contoso.com` to this group.
* Assign the group the **Virtual Machine Contributor** role on the VM’s Resource Group.

### 6. **Backup and Recovery**

* Create a **Recovery Services Vault** in the same region.
* Configure a **backup policy** for `ContosoVM01` with:

  * Daily backups at 11:00 PM
  * Retention for 30 days

### 7. **Security and Governance**

* Enable **Azure Defender for Servers**.
* Apply a **resource lock** (Read-only) to `ContosoVM01`.
* Apply a **tag** `Environment=Production` to all resources in `ContosoRG-EastUS`.

---

## 🧪 **Bonus Challenge Tasks**

* Create a **policy** that denies the creation of public IPs.
* Implement a **budget alert** for the Resource Group with a limit of \$100/month.
* Move all resources to a new region (e.g., West US) and evaluate what limitations exist.

---

## 🧠 **Skills Practiced**

* Azure VM deployment
* Storage & Networking configuration
* Monitoring, Backup & Recovery
* Azure AD & RBAC
* Azure Policies & Governance
