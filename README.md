# Management

## Configuration Management & change  management

# 1.Configuration Management
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

# 2. change  management

## What is Change Management?
### Definition:
**English:**
Change Management is the structured process of planning, implementing, monitoring, and reviewing changes in IT systems, software, network, or business operations, to minimize disruption and risk.

**Urdu:**
Change Management ka matlab hai kisi bhi system, software, ya business mein tarteeb se aur safely tabdeeli (change) lana — taake kaam disturb na ho aur problems na aayein.

## Change Management Components 

### Component ----------------------------------------------	English + Urdu Explanation

### 1. Change Request (CR) --------------------------------	A formal request to make a change.
Urdu: Change karne ki official request, jisme detail hoti hai kya change chahiye aur kyun.

### 2. Change Advisory Board (CAB) ----------------------------	Group that reviews and approves/rejects changes.
Urdu: Ek team jo change ko review karti hai aur decide karti hai ke change hona chahiye ya nahi.

### 3. Change Evaluation -------------------	Risk and impact analysis.
Urdu: Change se kya effect hoga systems pe – is ka analysis.

### 4. Change Implementation -----------------	Applying the approved change.
Urdu: Jo change approve hua usay apply karna.

### 5. Change Documentation -------------------------	Keeping records of all changes.
Urdu: Har change ka proper record rakhna.

### 6. Change Review (Post-Implementation) -----------------	Checking if change worked well.
Urdu: Change ke baad check karna ke sab kuch sahi chal raha hai ya nahi.

## Types of Change (Change ke Types ya Categories)
### Type --------------------------------	Description (English + Urdu)

### 1. Standard Change ------------------	Low-risk, routine, pre-approved changes.
Urdu: Aise change jo roz ke kaam ka hissa hote hain, jaise software updates.

### 2. Emergency Change --------------	Immediate changes due to incident or critical issue.
Urdu: Jaldi change karna pade kyunki system down hai ya koi attack hua hai.

### 3. Normal Change -------------------	Planned changes that go through approval process.
Urdu: Wo change jo na to urgent hai, na routine – lekin proper process ke through jata hai.

## Change Management KPIs (Key Performance Indicators)
KPIs help track the success, speed, and impact of the change management process.

### KPI  -------------------------------	English + Urdu Description

### 1. Change Success Rate	------------------ % of changes implemented without issues.
Urdu: Kitne changes successfully complete hue bina problems ke.

### 2. Change Failure Rate ----------------------	% of changes that caused issues.
Urdu: Kitne changes fail hue ya issues laaye.

### 3. Emergency Change Count -------------------------	How many urgent changes were made.
Urdu: Kitni emergency changes hui hain.

### 4. Mean Time to Implement (MTTI) -------------------	Average time to implement a change.
Urdu: Ek change ko implement karne ka average time.

### 5. Number of Backouts ---------------------------	Changes that had to be reversed.
Urdu: Kitni baar change wapas lena pada.

### 6. CAB Approval Time -----------------------------	Time taken to approve a change.
Urdu: Change approve hone mein kitna waqt laga.

##  Summary Table (Recap)
### Topic -----------------------------------	Details

Change Management -----------------------------	A process to manage IT/business changes effectively

Components -------------------------------	Request, CAB, Evaluation, Implementation, Review

Types ----------------------------------	Standard, Normal, Emergency

KPIs ---------------------------------	Success rate, Failure rate, Backouts, Approval time, etc.

### Example 
Suppose a company wants to upgrade its email server:

Change Request raised by IT.

CAB checks impact on users and approves it.

Implementation team applies upgrade Saturday night.

Post-review checks if emails are working fine.

If all good → change success. If not, rollback is done.
