# Management

## Configuration Management 
###  Definition:
**English:**
Configuration Management (CM) is the process of systematically managing and maintaining system settings, software, hardware, and documentation in a consistent state.

**Urdu:**
Configuration Management ka matlab hai system ke software, hardware, settings, aur unki documentation ko control aur track karna, taake koi change confuse na kare aur sab kuch consistent rahe.

#### Main Goals:
Prevent unauthorized or untracked changes

(بغیر اجازت کے تبدیلیوں سے بچاؤ)

Keep systems consistent and predictable

(سسٹمز کو ایک جیسا اور مستحکم رکھنا)

Enable easy rollback of changes

(تبدیلی واپس کرنا آسان ہو)

### Configuration Management Tools:
#### Tool	Use
Ansible	Automates software installation and updates

Puppet	Manages configuration files and servers

Chef	Infrastructure as code (IAC)

SaltStack	Remote system control and automation

**Urdu:**
Yeh tools automatically servers aur applications ko manage karte hain – is se manual errors nahi hotay aur har system same rehta hai.

## Provisioning 
#### Definition:
**English:**
Provisioning is the process of preparing and equipping a system (server, application, user account) so it's ready to use.

**Urdu:**
Provisioning ka matlab hai kisi naye server ya user ke liye necessary settings, access, aur resources ready karna taake wo kaam kar sake.

### Provisioning Process (Provisioning Ka Amal)
Provisioning involves several steps. Here's the complete process:

#### Step-by-Step Provisioning Process:
Step -------------------------------	Description (English + Urdu)

#### 1. Planning ----------------	Decide what system/user needs (hardware, OS, permissions)
Urdu: Pehle se tay karna ke kis cheez ki zaroorat hai

#### 2. Resource Allocation ----------------	Assign CPU, RAM, storage, network
Urdu: Resources assign karna – jaise CPU, memory, IP

#### 3. Configuration -----------------	Install OS, software, settings
Urdu: OS ya application install karna, settings apply karna

#### 4. Access Management ----------------	Create user accounts, set permissions
Urdu: User banake usko permissions dena

#### 5. Testing & Validation ----------------------	Check if system is working properly
Urdu: Sab kuch sahi chal raha hai ya nahi, test karna

#### 6. Handover -------------------------	Deliver to end-user or production
Urdu: Final system user ko de dena ya production mein bhjna

## Automated Provisioning 
###  Definition:
**English:**
Automated provisioning uses scripts or software tools to set up systems and users automatically, without manual steps.

##Urdu:##
Automated provisioning ka matlab hai system ko bina haath lagaye automatically setup karna – jaise server bana, OS install hua, aur user create hua – sab automatically.

## Why Use Automated Provisioning?
Benefit --------------------------------	Urdu Explanation

Faster deployment -----------------	Naye system ya user jaldi ready hota hai

Fewer errors -----------------	Manual mistakes nahi hotay

Consistency -------------------	Har system same configuration par hota hai

Scalability --------------	100s of servers quickly setup ho jate hain

## Tools for Automated Provisioning:
Tool	Use
Terraform	Infrastructure provisioning (cloud servers, networks)

Ansible	Automates both provisioning and configuration

CloudFormation (AWS)	AWS infrastructure provisioning

Azure ARM Templates	Provision Azure resources automatically

## Real-World Example

Imagine your company hires 50 new employees:

Manual provisioning: IT team manually create user accounts, install apps, set permissions (slow, error-prone)

Automated provisioning: A script runs → 50 user accounts created, emails set, apps installed = done in minutes ✅

## Summary Table
Topic --------------------------	Explanation (Eng + Urdu)
Configuration Management ------------------	Systems ko consistent aur managed rakhna

Provisioning ----------------------------	System ya user ko ready karna

Automated Provisioning -----------------	Scripts ya tools se automatic setup

Tools -----------------------------------	Terraform, Ansible, Chef, Puppet, CloudFormation

