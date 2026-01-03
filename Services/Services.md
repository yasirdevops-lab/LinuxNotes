# 1. Cloud Computing Overview
# and AWS-global infrastructure

#### What is cloud computing?

Internet par servers, storage, databases, software wagera ko bina apna physical hardware rakhe use karna or use k mtabiq pay krna ***Cloud Computing*** hai.

- Google
- AWS
- Azure
   - jesi companies Cloud computing k lye servers provide krti hain...

 1. **Infrastructure of a On Primses company..**


  - VMs (Virtual Machines)
  - Load Balancer
  - DNS (Domain Name System)
  - Web Server
  - Database (DB)
  - Storage (SAN)
  - Router
  - Monitoring Tools (zabix , Grafana, Prometus)
  - Switch (SW)
  - RAID
  
  #### Daigram 
  ![alt text](image.png)

  agar is compnay mein koi desaster ho jaye ( Fire , any) to apna data Lose kr deti hain. agar kisi cloud pe in ka Backup ni hai too.

  is ki  lagat bhi zyada hoti hai or Data losing k chances bhi bohat zyada hote hain.



  is trha agar ye company apna sb kuch yani **VMs, Tools,Storage,DBs,etc** kisi or Vendor se le or apna sirf setup us k saath attach kre to bhi is ko infra set krne k lye time+paying darkaar ho gaa.

  Infra of Vedor Diagram:

  ![alt text](image-1.png)

  ### Shared Hosting company 

  ***shared Hosting*** aik aisi web hosting service/ Company Hoti hai jismay aik hi physical server ko kai users mil kar share karte hain.
Har user ko server ke resources (CPU, RAM, Storage, Bandwidth) ka aik chhota hissa diya jata hai.


-  Shared Hosting k issues 
   - ye sirf Choti websites ke liye hoti hai
   - Low traffic mein hi work krti hai
   - Resources ko divide kr dia jata hai
   - Limited control

### Clouds

- **AWS's History**

  - The idea of ​​making AWS clouds came in 2002.


  - in 2004 start Testing on it .

  - Jeff Bezos Launch AWS cloud in 2006 Pulicaly with two services **sqs & ec2**..

  - AWS ne apna sb se pehla Data center ***North Virginia*** mein bnaya tha jis ka region ***South-East USA*** thaa..

ye bs conditions jo AWS apne clients ko provide krta hai is ko *** Cloud Computing*** kehte hain.

- ***Cloud Computing Ki teen conditions***

#### IAAS

***Infrastruture as a Service***

Cloud ne `servers,storage,Load Balancers,Routers,switches,Firewalls,VMs`ko services ki trha provide kia AWS is ko ***IAAS*** ka name diya.

#### PAAS

***Plateform as a service***

Cloud apne clients ko `OS(Opreating Systems),DBs etc` bhi provide krta hai is structure ko AWS ne ***PAAS*** ka name diye hai..

#### SAAS

***Softwares as a service***

is condition mein AWS (Cloud watch,Cloud trial)EBS (Elastic Block Store) applications Provide krta hai or is condition ko AWS ne ***SAAS*** ka name diya hai.

#### ye teeno conditions mil kr Cloud copmuting (C2) bnati hain. in mein se aap koi aik bhi le sktee hain ya 2 ya 3no hi as per you reqiurement.

####  AWS (Amazon web service) Azure ( Microsoft),GCP (Google Cloud platform ) alibaba Cloud Computing ki services provide krte hain..

Agar aap multiple services Multiple Clouds se lee rhee hain to is condition ko ***Hybred Cloud** kehye hain.

ye zrorat is lye peesh ati hai k Mukhlif Clouds ki Mukhtlif Services ka kaam krna aik doosre se behtar hota hai yani kisi cloud k Monitoring Tools behtar kaam krte hai kisi ki security zyada strong ho skti hai.

- Advantage of Cloud Computing..

1. ON Prime ya shared Hosting(co Location) mein aap ko ***setup k lye kaafi waqat darkar hot hai*** yani **servers ko set krna, Data Bases ko Manage krna, Infra set krnaa, Security arrange krna, Storage arrange krna** ye sub kuch kaafi Costly hoat hai or in changings mein aap ko bohat zyada **Down Time** ka smana krna padta hai is K mubable main aap **Cloud Computing** se ye kaam bohat jaldi kr sktee hain or in mein upgarding yani Scalability bohat jaldi or assan hai.

2.  Cloud Computing mein aap ko ye bhi benifit hoota hai k aik hi person jo cloud ki achi Knowledge rakhta hai wo sb kaam manage kr skta hai jo **on Prime** mein 4 ya 5 admins mil kr kr rhe hote hain yani ***Data Bases** ka alag Admin hota hai, **VMs** k lye alag Admin,or **Network** ka alag Admin hot hai Jab k Cloud pe ye kaam acha knowledge rkne wala aik ka zayada se zyada 2 persons easily kr skte hain.
3.  Clouds k through hum apne data ko Mukhltif regions mein store kr skte hain jab k **on Prime** ya **Co Locations** mein aap apna data sirf apne Data center mein rakte hain jo k **desasters** yani aag lag jana, ya any Natural Desaster ki wjha se Lose ho jata hai . **Cloud Computing k through ye Dunyia k do hisson mein store ho jata hai or safe rehta hai


### Global Infrastruture of AWS ..

![alt text](02b790d3d6b773afdea29a2483c46cd0.4c2a53c7c0d445df26718987c0b6a4ff3a05510c.jpeg)

- Region kya hota hai?

***AWS Region aik geographical area hoti hai jahan AWS apne bade bade data centers chalata hai.***


- Availability Zone kya hoti hai?

Is map mein AZs directly show nahin kiye gaye.

***AWS Region ke andar High availability ke liye multiple independent data centers banata hai jin ko AZs kehte hain***


Har AZ ka apna separate Power point ,Cooling system or  Network hota hai

For Example:

- `us-east` 1 region hai us k AZs ye  hain:

  - us-east-1a
  - us-east-1b
  - us-east-1c
  - us-east-1d
  - us-east-1e
  - us-east-1f

AZs sirf region ke andar hoti hain  map me unko point nahi kiya jata.

- Edge Location kya hoti hai?

**Edge locations chhote data centers hote hain jahan AWS apni CDN service CloudFront chalata hai.**

![alt text](image-2.png)

### Basics Of Cloud 

 Taking Technology of Mlutiple services from internet yani servers, storage, database, networking aur software sab kuch internet ke zariye use karna  bina apna hardware rakhe ye technology cloud kehlti hai.

 wolrdwide ye technology ye companies provide krti hain.

 `AWS Azure,GCP,alibab`

 Jis tarha aap electric company se bijli lete ho bina apna power plant banaye. or use k mutabiq Bill pay krte hain isi trhaa ye companies bhi internet k zaryee aap ko services provide krti hain or use k mutabiq bill pay wsool hain.

 #### Cloud ka kaam 

 **IT resources ko internet ke zariye provide karna**

Yani..

 Server dena + Storage dena + Database dena + Networking dena + Security dena  woh bhi internet ke zariye, pay-per-use model par.


 #### Cloud KI zrorat Q parti hai....

 ##### aik choti company ko chlane k lye Infrastructure

 -  ***Servers***

    - 50 servers chahiye

     - Har server ka cost approx 1 lakh – 5 lakh
  
- ***Software License***
 Servers chalane ke liye:

  - OS license

  - Antivirus

  - Database license

ki zorota bhi hoti hai


- ***Networking Equipment***

  - Router
  - Switch
  - Gateway
  - Cabling


- ***Employee Cost***

- Servers chalane ke liye:

  - Admin

  - Network engineer

  - Maintenance staff
  
 is sb ki salaries ki cost bhi hoti hai..

 yani agar hum ***on-premise*** servers khareed kar data center banayen, to bohot zyada paisa lagta hai (Capital Expenditure).

Isi liye companies Cloud use karti hain  kyunki cloud me ye saare kharche nahi hote.

#### Clouds Ka Benifit

Clouds mein Aapko sirf use ke hisaab se pay karna padta hai. Servers, storage, bandwidth, aur services aap subscribe kar lete ho.

Scalability: Zarurat padne par resources instantly increase ya decrease kar sakte ho.

- No Maintenance Cost for Users:

  - Cloud provider hardware maintenance, cooling, power, updates sab handle karta hai.

  - Aapko sirf apni applications aur data ka management karna hota hai.
- Elasticity (Auto Scaling):

  - Agar aapke apps ko traffic spike ho, cloud automatically extra servers allocate kar deta hai.

  - On-premise me aapko har peak ke liye extra servers kharidne padte.

- Global Infrastructure:

  - Cloud ke multiple regions aur edge locations hoti hain.

  - Data users ke nazdik store hota hai, is se latency kam aur efficiency zyada hoti hai.


 ##### Cloud in services ko teen conditions mein provide krta hai..



 #### IAAS

***Infrastruture as a Service***

Cloud provider aapko virtualized computing resources deta hai—jaise servers, storage, network, aur data center infrastructure—jo aap use kar sakte ho without physically owning hardware.

#### PAAS

***Plateform as a service***


#### SAAS

***Softwares as a service***

___

# lec#2  Launching EC2-Instance

### AWS Regions 

Aik independent geographic area jisme multiple Availability Zones hoti hain aur jahan AWS apni services run karta hai.

#### AWS ke total 25 Regions hain jo k countries k name se rakhe daye hain.

Yani india mein AWS ka aik region hai lekin us name Mumbai region rakha gaya hai na k inda Region .

##### Hmare yani Pakistan mein koi Region ni hai or hamre sb se qareeb Region ***Mumbai***  Region hai.

##### total AWS Regions= 38 worldwide 

- ##### Middle East

  - me-south-1 – Middle East ***(Bahrain)***

  - me-central-1 – Middle East ***(UAE)***

- #### Asia Regions 

  - ap-south-1 – Asia Pacific ***(Mumbai)***

  - ap-south-2 – Asia Pacific ***(Hyderabad)***

  - ap-northeast-1 – Asia Pacific ***(Tokyo)***

  - ap-northeast-3 – Asia Pacific ***(Osaka)***

  - ap-southeast-1 – Asia Pacific ***(Singapore)***
### AWS Availabilty Zones (AZ)

Har region mein multiple Availability Zones (AZs) hotay hain.

Any Region Has ***atleast 3 minimam*** Availability Zones .

- For Example 

  - Asia mein  ***(Mumbai)*** Region has 3 AZs

Any Region has ***atleast 6  maximam*** Availability Zones 
- For Example 
  - North. Virginia has highest 6 AZs .

#### Multiple AZs ki Zaroorat Kyu Hoti Hai?

***AWS ne ek Region ke andar multiple independent data centers banaye jise AZs kaha.***

- Multiple AZs se high availability aur fault tolerance possible hoti hai.

- 1. 
Multiple Availability Zones (AZs) is liye istemaal ki jati hain ke agar ek AZ fail ho jaye, to baaki AZs kaam jari rakhti hain, jis ki wajah se aapki application band nahi hoti aur service chalti rehti hai — is ko hi high availability kehte hain.


- 2. 
Is ke alawa, multiple AZs fault tolerance (gahan failover protection) aur disaster recovery (tabahi ki surat mein system dobara chalana) mein bhi madad karti hain.

#### AWS ne AZs (Availability Zones) kyun create kiye?
1) Single data center fail ho jata tha

Pehle companies apna pura system ek hi data center mein chalati thi.
Agar power fail, cooling fail, network cut, fire, ya hardware issue ho jata  poora system down.

***AZs ka solution:***

AWS ne ek Region ke andar multiple independent data centers banaye jin ko  AZs kaha.AWS ka main goal tha k ***Application 24/7 up rahe*** Agar ek building fail ho, doosri AZ se app chalti rahe

AZs ka design aisa bnaya gaya k agar ***ek AZ ki power off ho,ek AZ ki network fiber cut hojye ya ek AZ flood ho jaye***to doosri AZ bilkul safe rehti hai.

Yani ek problem poore region ko impact nahi karti.

#### Final Overview 

##### `AWS ne Availability Zones is liye create kiye taake ek Region ke andar multiple independent data centers ho jahan applications ko high availability, fault tolerance, aur zero downtime ke sath chalaya ja sake — bina expensive hardware banaye.`

- AWS also has 120+ Availability Zones inside all regions

### EC2 Luanching

sb se pehle mein AWS k aik new account Create kia ..

![alt text](image-3.png) 

![alt text](image-4.png)

![alt text](image-5.png)

- Jab aap apni Gmail lagate hain to AWS ki taraf se aik OTP ata hai jo aap ne yhan paste krna hota hai.

![alt text](image-7.png)

- Us k bbad next stpe mein aap apna AWS lk password create krte hain 

![alt text](image-8.png)

- Next wo aap se Billing information Lete hain .
Ye aik formality hoti hai aap k account se Peesy ni cut hote .

![alt text](image-9.png)



![alt text](image-10.png)



Ab aap ka Account create hone par aap ko Gmail bhi Recive ho gi or concole per bhi **Congraulations**
Likha hoa dekhe gaa..

![alt text](image-11.png)

![alt text](image-12.png)


ab aap k smane consloe open ho ga or aap services deekh skte hain or Luanch kr sktee hain

![alt text](image-14.png)


![alt text](image-15.png)

![alt text](image-16.png)

![alt text](image-17.png)

ab aap ko aik public IP mile ga or aap us IP k through ***MObaExtrem*** se session le sktee hain .


![alt text](image-18.png)

![alt text](image-19.png)

![alt text](image-20.png)

___

# Lec#3 Services Overview Billing Support Center- Waiveoff

### some AWS Services and usecase



#### 1. EC2 (Elastic Compute Cloud)
- **Kaam:** ye service cloud se Virtual machine (VM) provide karta hai cloud mein.
- **Use case:** Website host karna, applications run karna, testing environments.

---

#### 2. Auto Scaling

- **Use case:** is ervice ko High traffic handle karna, system crash se bachany k lye use kia jata hai.

---

#
#### 3. ELB (Elastic Load Balancer)
- **Kaam:** Multiple EC2 instances ke beech traffic distribute karta hai.
- **Use case:** ye service Website ka high traffic handle karta hai.

---

#### 4. ECS (Elastic Container Service)
- **Kaam:** ye cloud service Containers (Docker jaise) ko manage karti hai.
- **Use case:** Microservices applications deploy karna aur scale karne mein use hiti hai.

---

#### 5. EMR (Elastic MapReduce)
- **Kaam:**ye service  Big data process karta hai or ye Hadoop/Spark frameworks ko handle krta hai.
- **Use case:** Data analytics, log processing, machine learning on large datasets ko handle krta hai.


---

#### 6. QuickSight
- **Kaam:** ye aik Business intelligence toolnjo Data visualize aur dashboards banate hee.
- **Use case:** Reports aur insights generate karna for decision-making.

---

#### 7. Glue
- **Kaam:** ye data ko one storage to another mein move krta ahi move karta hai 
- **Use case:** Data warehouse setup, data cleaning.

---


***On Primesses Company ka infrastructure***

![alt text](image-21.png)

- Replaces all Services with cloud services  
  
![alt text](image-22.png)

###  On-Premise  AWS Replacement Mapping  
**(Facebook Infra → AWS Infra)**


---

### 1. DNS
**On-Prem:** DNS Server  
**AWS:** Route 53  

---

### 2. Content Delivery / CDN
**On-Prem:** CDN Servers  
**AWS:** CloudFront  

---

### 3. Load Balancer
**On-Prem:** Hardware / Software Load Balancer  
**AWS:** ELB (Elastic Load Balancer)  

---

### 4. Virtual Machines (Web + App Servers)
**On-Prem:** VMs, Hypervisor VMs  
**AWS:** EC2 Instances  

---

###  5. Database Cache
**On-Prem:** Redis / Memcached on servers  
**AWS:** ElastiCache  

---

###  6. Message Queue
**On-Prem:** RabbitMQ / Custom MQ  
**AWS:** SQS (Simple Queue Service)  

---

###  7. Email Sending
**On-Prem:** SMTP Server  
**AWS:** SES (Simple Email Service)  

---

###  8. Mobile / Push Notifications
**On-Prem:** Push Notification Server  
**AWS:** SNS (Simple Notification Service)  

---

###  9. Monitoring & Logs
**On-Prem:** Nagios, Zabbix, Custom Logs  
**AWS:** CloudWatch  

---

###  10. Storage (Media, Images, Videos)
**On-Prem:** NFS / SAN Storage  
**AWS:** S3 Buckets  

---

###  11. Video Processing / Conversion
**On-Prem:** Local Video Processing Servers  
**AWS:** Lambda + MediaConvert  

---

###  12. Image/Video Content Filtering
**On-Prem:** Custom Content Filter  
**AWS:** Rekognition  

---

###  13. User Click Stream Processing
**On-Prem:** Custom Logging + Stream Processor  
**AWS:** Kinesis  

---

###  14. Big Data Processing (Hadoop / Spark)
**On-Prem:** Hadoop Cluster, Spark Cluster  
**AWS:** EMR (Elastic MapReduce)  

---

###  15. Data Warehouse
**On-Prem:** SQL Data Warehouse  
**AWS:** Redshift  

---

###  16. Business Intelligence / Reports
**On-Prem:** Tableau / Local BI Tools  
**AWS:** QuickSight  

---

###  17. Private Network
**On-Prem:** Data Center Private Network  
**AWS:** VPC (Virtual Private Cloud)

---

#### Ye bohat kam hota hai lekin kuch services hoti hain jo all Regions mein available ni hoti...

### AMI Images 

AWS me AMI aik pre-configured image hoti hai jisme OS + Software + Settings pehle se installed hotay hain.
Isko use karke aap new EC2 instance launch kartay ho.

Jis trha ham kisi cheez ka clone (Duplicate) bnaty hain yani aik file k ho ba hoo same file isi trha AWS mein Linux Machine ki images ki clone Images hoti hain..

### Public and Elastice IPs

- ***Public IP***

AWS free Treil ki taraf se jub hum ec2 instance Luanch krte hain to aik public IP milta hai jis k through hum ec2 ka session as vm lete hain or rebbot k baad ye ip chnage hota hai is ko **Public IP** kehte hain.

ye as a prectice or own work k lye Use hoty hain.

 - ***Elastice IPs***

agar aap chahte hain k ec2 k reboot hony par bhi aap ki VM ka ip change na ho or baar baar session lena na pade too AWS aap ko paid IP bhi provide krta hai is ko **Elastice IP** khete hain.



is ki Zrorrat  Production level pe hoti hai ta k baar baar IP ki changings se Application ki srunning mein koi Khalal na aye.


___

# lec#4 AWS  Cloud-Watch 


### AWS mein Monitoring Methods


![alt text](image-23.png)
___
-  Cloud Watch's Monitornig 

![alt text](image-24.png)
___
***Day by Day Monntoring Method***

![alt text](image-25.png)
___

***Agar hum chahte hein K Cloud Watch ki service DashBoard par dekhai de to hum selected server ki Monitoring ko Dashboard per Move bhi kr skte hain ..***

![alt text](image-26.png)

![alt text](image-28.png)


![alt text](image-29.png)
### AWS Free instances Limit

-  Free Tier = 750 hours 
  
  ***Yani AWS 31 Days and 6 Hours k lye aap ko free services (Limited) provide krta hai***

  ***Limited se murad hai k kuch (Non-micro services ) jo free  available nhi hoti ***

***t2.micro / t3.micro (Linux/Windows) ke liye.***


- Important Points

  - Free Tier **sirf t2.micro ya t3.micro** per apply hota hai.

  -  AWS GPU, large sizes services , ya kisi bhi non-micro instance per free tier nahi deta .

  - Windows + Linux hours separate nahi balke combined count hota hai.
___

### Importance of Key

![alt text](image-31.png)

___


![alt text](image-32.png)

***AWS  services mein ja kr apmi VM ka key name find kran..***

___

![alt text](image-30.png)

**yani meri pehli VM ka key name ***yasir.pem*** hai to mein ye hi select kron gaa.**
___
**corrcet eay ko Select krnein  or ***open*** pe click krein.**

![alt text](image-33.png)

___

#### Session created 

![alt text](image-34.png)

___
# Lec#5 AWS - Types Families and  EBS Volumes

### Types of ec2

AWS cloud mein Instance ki **410 types** available hai.

Kisi type ki stotage zyada hoti hai or kisi type mein RAM zyada hoti hai.

sometime Ye types mukhtlif Regions mein differenr properties rakhti  hein yani agar **Mumbai Region** mein **c1.medium** ec2 ki properties CPU 2 hain ,RAM 1.7GB  hai. or stoarge  15 GBs hai to ye sometimes **OSAKA**Region mein different ho skti hai.

___

- ### AWS EC2 Instance Families

#### 1. General Purpose Instances
**(A1, T2, T3, T3a, T4g, M4, M5, M5a, M5n, M6g)**

AWS ne ye family *** small Websites, Small/medium applications, Development and testing servers*** k lye design kia jin k lye balance average CPU,Memory or storage required hoti hain..

---

#### 2. Compute Optimized Instances
**(C4, C5, C5a, C5n, C6g)**

IS Family ko  ***High-performance computing,Batch processing,Gaming servers*** k lye design kia hai jin k high CPU,Memory or storage required hoti hain..

---

#### 3. Memory Optimized Instances
**(R4, R5, R5a, R5n, R6g, X1, X1e, Z1d)**

Designed for workloads requiring large amounts of RAM.

Yani 
- Large databases k lye 
- Big data workloads
- Real-time analytics

---

#### 4. Accelerated Computing Instances
**(P2, P3, F1, G3, G4)**

ye Instances  GPU hardware k lye design ki gai hai.

Use cases:
- Machine learning training
- High Results Video ko dekhen k lye
- High-graphics applications running k lye 

---

#### 5. Storage Optimized Instances
**(D2, H1, I3, I3en)**

YE instances fast local storage and high IOPS k lye  Designed hain.

ye Use hoti hain
- Big  databases k lye 
- Data warehousing k lye 
- High IOPS workloads

### EBS volume 

***EBS Volume = AWS ki virtual hard disk***

Jise tum EC2 machine k sath use karte ho data store karne ke liye.

EBS Volume (Elastic Block Store) AWS ka block-level storage hota hai jo EC2 instances ke sath attach hota hai, bilkul waise hi jaise computer me hard disk (HDD/SSD) lagti hai.

jub hum t2 ya t3 ec2 instance Launch krte hain to by -default 8 GBs storage provide krta hai.Hum is volume ka size badha sakte hen, type change kar sakte hen (gp2 → gp3 → io1 etc.

![alt text](image-36.png)


![alt text](image-37.png)


### 1. Block Storage hota hai
Data ko blocks ki form me store karta hai (jaise SSD/HDD).
___

### 2. EC2 instance ke sath attach hota hai
Jaise physical server me disk hoti hai, waise EC2 me EBS hota hai.
___
### 3. Persistent storage hai
Instance stop/terminate bhi ho jaye, data safe rehta hai  
(agar delete-on-termination off ho).
___
### 4. Network-based storage
Ye AWS network ke through attach hota hai (local disk nahi hota).
___
### 5. Resize & type change possible
Tum volume size badha sakte ho, type change kar sakte ho  
(gp2 → gp3 → io1 etc.).
___
### 6. Snapshots bana sakte ho
Backup lene ke liye EBS snapshots use hote hain  
(jo S3 me store hotay hain).
___


### Types of EBS Volumes

1. **gp2 / gp3**  
   - Type: General Purpose SSD  
   - Use Case: Web servers, applications  
___
2. **io1 / io2**  
   - Type: High Performance SSD  
   - Use Case: Databases, high IOPS workloads  
___
3. **st1**  
   - Type: HDD – Throughput Optimized  
   - Use Case: Big data, streaming workloads  
___

### Interview Based Quetions

1. AWS instance families – EC2 instances ke different categories kya hain?
2. AZ – Availability Zone kya hota hai?
3. AWS Regions ka concept kya hai?
4. EC2 instance choose karne ka criteria kya hai? (CPU, RAM, storage, network)
5. EC2 instance ka creation process kya hai?
6. EC2 ke storage options kya hain? (Type aur size)
7. EC2 data persistence ya storage level ke options kya hain?
8. Agar SSH key bhool gaye to kya karna chahiye?
9. Ek saath maximum kitne instances launch kar sakte hain?
10. AWS me monitoring kya hoti hai? (CloudWatch, instance monitoring)
11. EC2 instance purchasing options ka difference kya hai? (Spot, On-demand, Dedicated Instance, Dedicated Host)
___

![alt text](image-38.png)



### : AWS Console se Volume Add Karna

#### 1. EC2 Dashboard
- AWS Console pe  **EC2** instance mein jain
- Left side menu  **Volumes** 
- **Create volume** par click karein

![alt text](image-39.png)

---

### 2. Volume Details Fill Karein


- **Volume type**: gp3 (recommended)

![alt text](image-40.png)


- **Size**: 10 GiB (ya apni requirement ke mutabiq)

![alt text](image-41.png)



 #### Same AZ select karein jahan EC2 instance run kar raha ho  
  Example:  
  - Instance AZ: `ap-south-1a`  
  - Volume AZ: `ap-south-1a`

![alt text](image-42.png)
- **Create volume** par click karein
___
### 3. Volume ko EC2 Instance ke Sath Attach Karein
- Volumes list se apna volume select karein
- **Actions → Attach volume**
- EC2 instance select karein
- **Device name** default rehne dein (example: `/dev/sdf`)
- **Attach** par click karein

![alt text](image-43.png)


![alt text](image-44.png)

___
#### Comman line se add volume check krnaa...


![alt text](image-45.png)

### Volume ko delete krne ka method.

![alt text](image-46.png)

___
# Lec#6 AWS Elastic IP S3

#### Hum AWS instance machines ko ko ***yum*** se update kr sktee hain..

### AWS EC2 Internet Connectivity Architecture

![alt text](image-49.png)
![alt text](image-47.png)

Jo IP router par hota hai or hmari requets ko AWS servers tak le kr jata hai us ko **Live IP** bhi kehte hain..

Publice IP se machine k off hone k baad aap ko har bar New Session lena parta hai Q k har baar aap ko **new  Publice IP** milta hai ..
___
### Elastic IP.

Companies ke andar aksar **Elastic IP** use ki jati hai taake machine (EC2 instance) **reboot, stop/start** ya replace hone ke baad bhi uska Public IP change na ho.

- ***One-Line Interview Answer***

***Elastic IP is used to provide a static public IP so that services remain accessible even after EC2 restart, stop/start, or failure.***

***Important Note:***


Elastic IP reboot ke liye nahi balkay stop/start aur instance replace ke liye critical hota hai

**AWS charge leta hai agar..**

***EIP use mein na bhi ho Ya instance se attached bhi na ho***
___
#### EIP allocating Method.

![alt text](image-50.png)
___
![alt text](image-52.png)
___
![alt text](image-51.png)

___
## S3 (Simple Storage Service)

- S3 ek cloud hard disk hai, jahan hum files / data rakhte hain — jaise:

  - images

  - videos

  - backups

  - logs

  - software files

is ki example esy jesy Google Drive pe hum 15 GBs tak Data store kr sktee hain is trha AWS bhi hame 5 GBs tak spce provide krt hai jis mein any tpe of Data store kr sktee hain.

### Differnce between EBS and S3.

| Point   | S3                         | EBS                              |
|--------|-----------------------------|----------------------------------|
| Type   | Object Storage              | Block Storage                    |
| Attach | Kisi server se attach nahi  | EC2 ke sath attach hoti          |
| OS     | OS ka hissa nahi banti      | OS ke andar mount hoti           |
| Access | Internet / API / URL        | OS ke through (file system)      |

#### EBS AZ-specific hoti hai,is AZ mein EC2 instance hoga, EBS bhi usi AZ ki honi chahiye

#### jab ke S3 region-level service hai jo multiple AZs mein data replicate karti hai, is liye globally accessible hoti hai.

![alt text](image-53.png)

***Object = Data + Metadata + ID***

Har file ko ek object bola jata hai.

1️⃣ Data → actual file (image, video, zip)

2️⃣ Metadata → file ki information (size, type, owner, date)

3️⃣ Object ID / Key → unique naam / address

Examples..

***Google Drive / Dropbox***


#### s3 Bucket.

S3 mein agar data store krna ho to sb se phele aik **Bucket** bnana padta hai. Jis ka name **Globely Unique** hota hai yano is jesa AWS mein kisi Bucket k name ni hona chaye..

Hum S3 mein **Multiple** buckets bna skte hain..

#### Method of Creating Bucket

![alt text](image-54.png)


![alt text](image-55.png)


![alt text](image-56.png)


![alt text](image-57.png)

![alt text](image-58.png)

![alt text](image-59.png)

![alt text](image-60.png)

![alt text](image-61.png)

___

# Lec#7 S3-Calculator-NFS


### S3 Bucket ko Public krne ka mehtod.

***Step 1:***

- AWS Console login karo
- S3 service open karo
- Apna required bucket select karo
- Permissions tab par jao

![alt text](image-62.png)
___

***Step 2:***

- Permissions tab par jao
- Block public access (bucket settings) open karo
- Edit par click karo
- Block all public access ko UNCHECK karo
- Save changes

![alt text](image-63.png)

![alt text](image-64.png)

![alt text](image-65.png)

![alt text](image-66.png)

![alt text](image-67.png)

![alt text](image-68.png)

#### AWS S3 Free Tier Request Limits (per month)

1. 20,000 GET Requests (file download / read requests) free
   
2.  2,000 PUT, POST, COPY, or LIST Requests (file upload/modify/list operations) free
   
3. Free Storage: 5 GB S3 Standard storage per month free
---

#### High Availability (HA) / Clustering ka Concept..

Agar hum **multiple services** (jaise **web server, database, applications**)  
**sirf aik hi server** par chala rahe hon, to:

- Server par **load zyada ho jata hai**
- **Hardware failure**, **OS crash**, ya **application crash** ka risk hota hai
- Agar server **down** ho jaye to **saari services band** ho jati hain

Isi problem ko solve karne ke liye companies  
**High Availability (HA)** aur **Clustering** ka use karti hain.
___
#### Clustering kya hota hai?


 Multiple servers ka mil kar aik hi service provide karna clustering hai.

jo server milte  Ye servers **cluster nodes** kehlate hain

- Load aur traffic multiple servers mein distribute hota hai
___
![alt text](image-69.png)
___

### NFS (Network File System)

Definition:

NFS ek **network protocol** hai jo allow karta hai ek computer ko apni files aur directories ko network ke doosre computers ke saath share karni hain

- Kaam:

  - Ek server apni file system ki kuch directories ko export karta hai.

  - Clients in directories ko mount karke apne local system ki tarah access karte hain.

  - Is tarah multiple machines same data ko read/write kar sakti hain.
___
# Lec#8 Server Client Model NFS-Server


Client server Model bany k wajah:..

Hmare pass kuch files hoti hain jin ka Client ko acces dena hota hai. is Lye hum ye NFS create krte hain.

Is k lye pehel mein ne 2 CentOS machines bnai..
aik Machine ko **as a server rakha** or dosri machine ko **as a Client** rakha..

![alt text](image-70.png)

![alt text](image-71.png)

![alt text](image-72.png)

![alt text](image-73.png)

![alt text](image-74.png)

#### ab ye krna hai jis trha same machines mein IP ping ho rhee hain isi  trhaa server Ka IP Client k Ping kr skee or Client ka IP server bhi Ping skee is k lye bhi in k IPs ki entries `/etc/hosts` file mein krni hoon gi..


#### Client  Srever IP ping 

![alt text](image-75.png)

![alt text](image-76.png)

### Server  Client IP ping
![alt text](image-77.png)

![alt text](image-78.png)

#### Now Connection Build between Client and server.

#### Jab Client se Server ping hota hai, iska matlab Client se Server ka network path open hai.
___
### NFS Server Setup on CentOS 7

is command se check kia k mere pass nfs ka pacjage hai ya ni ...

      rpm -qa | grep -i nfs
in  Commands se mein **nfs** or **rpcbind**ki service start ki or us ko enable/persist kia .
 


      systemctl start nfs-server

      systemctl enable  nfs-server

      systemctl status nfs-server

      2.rpsbind

      systemctl start rpcbind


      systemctl enable rpcbind
Phir is directory mein us file ka path add kai jis ko client k lye accessable bnan tha ..

      vi /etc/exports

 ye path us file mein add kia .

    /opt/fileserver *(sync)
***Shares /opt/fileserver with all clients (*) with synchronous writes***

 NFS ke liye ports open nahi honge agar firewall chal rahi ho, isliye testing ya initial setup ke liye firewall ko temporarily stop kiya jata hai.

      systemctl stop firewalld.service

### Client side 

![alt text](image-79.png)

yeh command NFS server (yasir) par available shared directories (exports) ko dekhta hai.

- ***showmount -e yasir***

Output mein dikh raha hai ke NFS server yasir ne sirf ek directory share ki hai:

      /opt/fileserver *

shared directory ka path
- ***/opt/fileserver***

(* )ka matlab yeh shared file  sabhi hosts/network ke liye accessible hai.
___

shared folder ko mount krne ka method :


- is command se shared folder ko mount kia hai .


  -       mount yasir:/opt/fileserver myshare
  - **yasir** NFS server ka naam

  - **/opt/fileserver** NFS server par shared folder

  - **myshare**  client machine par mount point 
___
# Lec#9 NFS Server2 and FTP

### NFS Rule

Server aur client dono ek hi data ko dekhte hain.  

- Agar aap **SERVER** par file banate hain:  
  - Server directory: `/fileserver/abc.txt`  
  - Client par woh file yahan nazar aayegi: `/myshare/abc.txt`

- Agar aap **CLIENT** par file banate hain:  
  - Client mount point: `/myshare/xyz.txt`  
  - Server par woh file yahan banegi: `/fileserver/xyz.txt`

### Important Conditions (warna error aata hai)

1. Server export `rw` hona chahiye.  
2. Client mount `rw` hona chahiye.  
3. Permissions correct honi chahiye.

![alt text](image-80.png)

![alt text](image-81.png)

#### How to change NFS filesyatem permissons? 

![alt text](image-82.png)

![alt text](image-83.png)

 ![alt text](image-84.png)

 ### ab hum server k shared folder(/opt/fileserver) ko all permission de dein gee.

![alt text](image-87.png)

ab client  side pe mein shared folder mein Files create kr skta hoon

![alt text](image-86.png)

***Server:*** Wo device Jahan files store hoti hain aur FTP service chal rahi hoti hai.

***Client:*** wo Device Jo files ko server se download ya server par upload karti hai.

- ***FTP*** Application Layer protocol haijo ***TCP*** ke upar kaam karta hai.

***Difference between NFS and FTP***

***NFS***

Ye file sharing protocol hai.is k through servers se files ko client k saath share kia jata hai.

Jab server down ho jaye to filess ki access bhi khatam ho jati hai 

Client files ko download nhi kr skta.

***FTP***



ye aik  Protocol hai jo  Server aur client ke beech files transfer karne kam krta hai (upload/download)

 Application layer (OSI Layer 7)


Client server se files download kar sakta hai

Client server par files upload bhi kar sakta hai.

#### FTP 2 Ports par kaam krt hai.

1. Port: 21 connection k lye.

 Client aur server ke beech connection k lye or commands exchange krne use hot hai.

Connection type: TCP

 

2. Port: 20 data transefer k lyee

Actual file transfer ke liye use hota hai

Connection type: TCP

TCP (Transmission Control Protocol) ek protocol hai jo network par data ko reliably aur sahi sequence mein pohanchata hai.

### Method of FTP

sb se pehle check kr lo k aap k pass **FTP Package** available hai k ni.

      rpm -qa | grep -i vsftpd

![alt text](image-88.png)
___
#### Now Services start kr lein...

##### Start FTP service
      systemctl start vsftpd

##### Enable on boot
    systemctl enable vsftpd

##### Status check
      systemctl status vsftpd


___
#### Ports check krne ki commands

      ss -tuln | grep ':22'
      ss -tuln | grep ':21'
___
### FTP mein files share karne ka DEFAULT path
 vsftpd ka default directory:

    /var/ftp/


Is folder ke andar jo bhi file hogi, FTP client ko wahi nazar aayegi.

![alt text](image-89.png)
____

### Client side k browser pe aap ab ye files dekh skte hain 

![alt text](image-90.png)

Client browser pe jab **ftp://yasir** search kr ga to ye files use dekhe gi or wo files ko download bhi kr skta hai..
___
# Lec#10 .Service Concepts Securing vSFTP

### services k basic Concepts

#### Koi bhi package install kr ne se phele check kia jata hai k package already available hai k nhi.

- Command:-

  -       rpm -qa | grep -i package_name
![alt text](image-92.png)

![alt text](image-91.png)

- ***rpm -qc <package>***

Purpose:ye command Package ke configuration files list karne ke liye hai.

-q = Query package

-c = Show configuration files

Example:

      rpm -qc httpd

Ye httpd package ke saare configuration files (jaise /etc/httpd/conf/httpd.conf) dikhayega.

___

#### 2. `rpm -ql <package>`

Purpose: Package ke saare installed files list karne ke liye.

-q → Query package

-l → List all files installed by package

Example:

      rpm -ql httpd


Ye dikhaega ki httpd package ne kaun kaun se files system me install kiye hain (binaries, docs, configs, etc).
___
### 3 `rpm -qd <package>`

Purpose: Package ke documentation files list karne ke liye.

-q → Query package

-d → Show documentation files

Example:

    rpm -qd http


Ye dikhaega ki http package ke docs (jaise README, LICENSE, COPYRIGHT) kahan store hue hain.

#### Package ki sb se important file **binary files**hoti hain .
![alt text](image-93.png)

Better way command k through service ko start krna hi hai.

- systemctl start httpd (REHL centOS 7)
- service httpd start (REHL 6 centOS)



___ 
#### Package  available na ho to package Yum se install ke lein.

  - Command
   
     -        yum install docker -y


Phir is package ki services ka status check krein agar start hai to **active/running** aye ga or agar stop hai ti **inactive/dead** aye ga

![alt text](image-94.png)
![alt text](image-95.png)

      systemctl status >service name>
      systemctl restart >service name>
      systemctl stop >service name>
      systemctl enable >service name>

___

### 3 type of FTP users

1. Anonymous User
2. local system users
3. Virtual Users


#### 1. Anonymous User

 Anonymous user woh hota hai jo bina username/password ke sirf public data access karta hai or download kr skta hai.

 - **For Example**

 Jis tarha hum **youtube** ya **Vidmate** se songs,clips Download kr lete hain lekin koi bhi password nhi dete hain.

#### 2. local system users

OS ka real user jo FTP server me apne credentials se login karke full access le sakta hai.

OS ka real user jo apne username/password se FTP server me login karke apne assigned folder me read/write/delete kar sakta hai.


#### 3. Virtual Users
FTP-only user jo OS account ke bina sirf FTP server me login karke access le sakta hai.

jesa k Clients jo OS users ka hissa nhi hote lekin FTP k through un files ko access kr skte hain jo **/var/ftp** mein rakhi gai hon or un ka IP as client /etc/hosts mein mention ho too.

Client jo OS user nahi hota lekin FTP server ke through specified directory me files ko read/write kar sakta hai.

![alt text](image-96.png)

### Important

Every service have a **config file**. jis ka purpose permeters ko change krna hota hai jo k hum **Binary files** mein nhi kr skte. Ye real time mein perameters ko change krta hai. Na k source code mein.

FTP server par Anonymous login tabhi possible hota hai jab server config me **anonymous_enable=YES** ho.

FTP service ki Config file ka path.

    /etc/vsftpd/vsftpd.conf

![alt text](image-97.png)
is file mein hum changing krte hain to ye isi trhaa hi jese k fbinary file mein changing ki hoti hai

      vi /etc/vsftpd/vsftpd.conf


![alt text](image-98.png)

![alt text](image-99.png)

#### jab hum koi bhi config file mein changing krte hain to ye lazmi hai k hum us file ko dobara RAM main load krein ta k RAM jb config file ko read kre to changing k according load kree.

- ***command :-***

      systemctl restart vsftpd

![alt text](image-100.png)
___

#   Lec# 11.Setting Up FTPs in Enterprise

***configuration file:***

Config (configuration) file wo file hoti hai jisme service / program ke rules (parameters) likhe hote hain.

 (vsftpd)
Config file location:

        /etc/vsftpd/vsftpd.conf

***parameters***

kisi program,serviceya command k kaam krne k rules+settings ko perameters kehte hain..
___

![alt text](image-101.png)


### chroot kya hota hai?

chroot ka matlab hota hai user ko ek specific directory ke andar ***jail*** kar dena
taake wo system ke baqi files / folders ko dekh hi na sake.

chroot = user ko uski directory ke bahar jaane se rok dena (directory jail).

### Hotel room example

Tum guest ho

Tum sirf apna room use kar sakte ho

yani ap k pass Kitchen, store room, staff area ki access nahi hsi

- Room = chroot directory
-  Guest = FTP user

  is k lye bhi hame **vsftpd** ki config file main **chroot** ko enable/yes krna ho ga.

        vi /etc/vsftpd/vsftpd.conf


  ![alt text](image-102.png) 

ab hame jese hum ne phel bho padha hai config files mein changes k baad file ko dobara RAM mein LOad krna hota hai taa k system un files k perametes ko dobara read kre or us hissab se kam kre.

Lekin ***production level*** pe jahan kam ho rha hota hai services ko baar baar **restart** krne se **connections** break ho jate hain or kam stop ho jate hain.

yani agar koi **FTP USER** files ko download kar rha ho to service ko restart krne se connection broke ho jata hai or downloading cancle ho jati hai.

is lye again & again  **systemct restart vsftpd**  command run nhi krni chahye.

is lye Behtar option ye hai k aap service ko **restart** ki bjaye **reload** kr lein

      systemctl reload vsftpd

is command se aap ne jo changes ki hoon gi wo RAM mein Load ho jayen gi or aap ka process bhi kill nhi ho ga.

![alt text](image-103.png)

### Active and Passive FTPs

![alt text](image-104.png)

## Passive FTP 

Client server k pass khud jata hai or Port 21 se connection bnata hai or Server  ki 1024(random) ya koi bhi Higher port k through data collect krta hai.

yani

Client server ke paas jaata hai aur dono connections khud banata hai.

___

# Lec# 12.Apache Server

### Webserver 

Web Server aik software hai jo website ka content (HTML, images, waghera) internet ke zariye deliver karta hai, aur ye aik digital storefront ki tarah kaam karta hai.

  jaise

 ***Apache, NGINX,***
___
 ### Website 

 Website web pages, documents, images, aur media ka  majmua hai, jo online ek hi domain name (jaise example.com) ke under accessible hota hai aur web server par store hota hai, jo aik digital space ki tarah kaam karta hai jahan maloomat available hoti hai.



 **Domain Name:** Aap ka unique web address (jaise yourcompany.com).

**Web Pages**: Documents (HTML, CSS, JavaScript) jisme text, images, videos, waghera hotay hain.

**Web Server:** Wo jagah jahan website ki tamam files store hoti hain, taake ye online available hon.

**Web Browser:** Software (jaise Chrome, Firefox) jo websites dekhne ke liye istemal hota hai aur ye files request aur display karta hai.

___
### WebHosting


**Web Hosting** aik **service** hai jo aap ki website ki files (text, images, code) ko **servers** par store karti hai, taake aap ki website online accessible ho jaye. Jab koi user aap ka domain name browser mein type karta hai, to ye files un tak pohanchti hain.
___

### Apache server 

![alt text](image-105.png)

Hum ne pehle bhi parha hoa hai k koi bhi service run krte time us ka package check krna hai k install hai ya nhi 

Jessy hum ab **apache** service ko use krene waly hain to is ka package bhi chahye ho ga.

![alt text](image-106.png)

Yhan mere pass apacjage available hai.


![alt text](image-107.png)

![alt text](image-108.png)


 Phele system boot k duran Parent config file **httpd.conf** ko read krta hai or usi file k content **include child files** ki entry hoti hai or phir system un files ko bhi read krta hai. 

 ___

 ### Sample Files 

 **/usr/share/doc**
 
yhan packages ke sample files hoti hain, jo user ko package ka istimal aur details samajhne mein help karti hain.

![alt text](image-109.png)

yani agar hame **httpd** ko virtual host kran hai to is k realted bhi file mojud hai aap ne firf us file ko copy kr k httpd ki bydefault path **/var/www/httpd** pe la k ana hai.

or file mein aap ko changes krni hai jo sb se zayada secure or easy way kisi config file mein chandes krne ka.
___
### Apache config file k sections 

1.  Global section
2.   Main section 
3.   Virtual Host section 
  
  Hame 3rd section mein changes krni hoti hain is k lye hame dangerless way ko choose krte hoye **Sample File httpd-vhosts.conf** file copy kr **conf.d** mein le kr ana ho ga jis mein **child conf** files hoti hain.

  ![alt text](image-110.png)

        vi httpd-vhosts.conf

        file content k Last mein  hame ye meile gaa.

        see  below screenshot....
#### sample config file bfore changes.
 
  ![alt text](image-111.png)

  #### sample config file mein changes

  VH config file mein hum ne 3 changes kye.

  - port ka name change kia **80**
  - Server ka name define kia jo hum browser per search krein ge.
  - httpd server ka file path define kia jo kr browser k through access ho gaa.




![alt text](image-112.png)

File mein changes ko test krne k lye **httpd -t** command run kr k aap changes ko test kr kte hain k ye **suitable** hain yani kaam krein gi.

![alt text](image-113.png)

___
Now we do reload or restart the service so that files reload in RAM and system execute file with new perameters.

    systemctl reload httpd

          or

    systemct restart httpd


    systemctl enable httpd (optional)

![alt text](image-115.png)


### Mapping with name 

**/etc/hosts** file mein IP K saath name bhi likh deya..


![alt text](image-116.png)


![alt text](image-117.png)
___
# Lec# 13.Apache Server with 2 Containers


### Real Scenario: 

jab Chrome/Firefox mein likhte hain:

    http://yasir1.zone


Too browser ko keh rahe hote hain k 

**Mujhe yasir1.zone ka page dekhao**

___
### Name to IP Resolving

Browser ye order follow karta hai q ka browser sirf IP address hi ko samajh skta hai or yhan hum name likh rhe hain .

#### ***Browser cache***

Browser se pehle apni chache check krta hai k aya k pehle kabhi is name se serach to nhi kia or wahan se hi IP find ho jaye gaa.

2.  ***OS cache***

 Phir Browser OS ka cache check krta hai k aya k is OS mein kisi or jagha is name ko resolve to nhi kia gaya Q k browser ko jaldi IP chahye hota hai.

 OS RAM check krta hai k pehle kisi or Browser mein ya name to nhi use hoa or resolve hoa ho to foran mein IP browser ko de dooon.



3.  ***/etc/hosts***
   
OS se IP resolve na hone par browser **/etc/hosts** file ko check krta hai k is file mein IP ki entry to nhi hai .

Yahan hum already entry krte hain. Q k hum anhi DNS ko use nhi kr rhe agar DNS use na krna ho or LocalNetwotk pe server chlaane k lye **/etc/hosts** file mein entry Lazmi hai.


4.  ***DNS (internet)***
  
agar file mein bhi entry na ho requset internet par jati hai or internet k through IP find hota hai .

sb se pehle system apne configured DNS se poohta hai k is name/Domain ka IP kia hai jese k **8.8.8.8 / Goggle** is **ko Recursive DNS** kehte hai.

Recursive DNS ko bhi agar DNS na mile to to wo Mian Domain house ko request forward krta hai k tum se te Domain li gai hai is ka IP btao. .com/.online etc

Phir yahan 100% IP mil jata hai.


### Lekin hame /et/hosts file se hi IP milta hai Q k hum ne loacal Network per hi server bnaya hai or /etc/hosts mein etries bhi ki hoi hai.

![alt text](image-118.png)

___


### TCP Port connection 

- TCP Pot 80

IP browser ko milta hai to browser TCP k through port 80 se connection build krta hai.

- Config file Reading

Port 80 se request apache server ko gothrough krti hai k wo apni config file read kre or server Name ko match krte hoye ** webserver file ka path find kre.

Config file mein container mein likhi gai configrations ko read and match kr  k apache web server file ka content browser mein load kr deta hai .

Last mein file permissions ko check hoti hain oe browser pe file content show ho jta hai.
___

### Apache Server with 2 Containers


![alt text](image-119.png)

![alt text](image-121.png)

![alt text](image-120.png)

___
### Two types of Apache Hosting

***1. Name Based***


Ek hi IP address pe multiple websites host ki ja sakti hain.

Browser HTTP request me Host header (yasir.zone) bhejta hai, server is header ko dekh ke decide karta hai kaunsa site serve karna hai.


    <VirtualHost *:80>
    ServerName site1.com
    DocumentRoot /var/www/site1
</VirtualHost>

    <VirtualHost *:80>
    ServerName site2.com
    DocumentRoot /var/www/site2
</VirtualHost>



***2. IP Based***

Har website ke liye server ke paas alag IP address hota hai.

 Jab client request bhejta hai, server IP address dekh kar decide karta hai kaunsa site serve karna hai.

 Example 

    <VirtualHost 192.168.1.10:80>
    ServerName site1.com
    DocumentRoot /var/www/site1
</VirtualHost>

    <VirtualHost 192.168.1.11:80>
    ServerName site2.com
    DocumentRoot /var/www/site2
</VirtualHost>


# 14.Tcp Wrappers-IP Tables


### TCP Wrappers

TCP Wrappers ek **host-based access control** mechanism hai jo Linux/Unix systems mein network services ko control karta hai.

Isko **Applictaion levle** ka **Firewall** bhi kehte hain.

___


### Kaam kya karta hai

- TCP Wrappers incoming network connections ko monitor karta hai.

- Ye decide karta hai ki connection allow hoga ya deny hoga based on IP address ya hostname.

- Ye log bhi maintain karta hai ki kis IP ne connection attempt kiya.

---

### File Structure

TCP Wrappers ke do main configuration files hain:

### 1. `/etc/hosts.allow`

### 2. `/etc/hosts.deny`
___
### `/etc/hosts.allow`

- Yahan specify hota hai **kaun allow hai**.  
- **Example:**
  ```bash
  sshd: 192.168.1.10

iska matlab hai k sirf **192.168.1.10** yani mentioned IP wali machine hi remote session le skti hai.


### `etc/hosts.deny`

Yahan specify hota hai kaun deny hai.

Example:

    ALL: ALL


Baaki sab deny ho jayenge, sirf hosts.allow mein defined IP allow hoga.
___
### Rule Flow

TCP Wrappers ka rule ye hai: **hosts.allow*** pehle check hota hai or jo IPs ya hostname service k saath  mention hoon ge un ko allaow ho ga.


Phir  **hosts.deny** check hota hai or jin IPs ka hostname jis service k saath entry ho gi wo IPs /Hostsnames un service ko nhi chla skte .
___

### Firewall


Firewall ek **network security system** hai jo **incoming** aur **outgoing network traffic** ko monitor aur control karta hai, aur ye decide karta hai ke kon sa traffic allow hoga aur kaun sa block hoga.
___
### Types of Firewalls

- ***Hardware Firewalls***


Hardware Firewalls ek dedicated physical device hote hain jo network ke beech lagaye jaate hain aur incoming aur outgoing network traffic ko filter karte hain. Ye high-speed aur reliable protection provide karte hain, specially enterprise environments ke liye.

in Firewalls mein Network rules cngig krt deta hai k kis type ka data ana chahye or konsa Network allow hai communication k lye.

Doosra ye k outgiong Methods k lye bhi rules define kye jate hain k company ka konsa user bahit k network se connect kr kta hai or data share kr skte hai.
![alt text](image-122.png)
___
- ***Software/Applictaions Firewalls***

Software/Application Firewalls ek program-based security system hai jo directly computer ya server pe install hota hai aur system-level ya application-level network traffic ko monitor aur control karta hai.

___

- ***Cloud Firewalls***

Cloud Firewall internet aur cloud resources ke beech ek protective layer provide karta hai.

jaise AWS, Azure, Google Cloud, ya koi private cloud. Ye traditional hardware/software firewall ki tarah kaam karta hai, lekin cloud infrastructure ke liye optimized hota hai.


Cloud k network infrastructure pe Incoming aur outgoing traffic ko IP, port, protocol ke basis pe filter karta hai.

- Scalability

Automatically scale hota hai yani jab network traffic increase ho to firewall recources bhi increase ho jate hain or zyada traffic ko control krne mein lag jate hain.
___

**DMZ (Demilitarized Zone)**

ye ek subnetwork hai jo company ke internal, trusted network (LAN) aur untrusted external network (Internet) ke beech ek buffer ka kaam karta hai. Ye public-facing services jaise web, email, DNS, aur FTP servers host karta hai, jisse external users in services ko access kar saken, lekin internal network ko direct exposure se protect karta hai.

- #### Real-Life Exmaple 

  DMZ = **“Reception & lobby area”** jahan visitors limited access le sakte hain, lekin office ke andar (LAN) jaane se rok diya jata hai.

![alt text](image-125.png)

  ### IPTables

  iptables Linux kernel ka **firewall tool** hai jo IP packets ko rules ki madad se filter karta hai aur decide karta hai ke packet accept, drop, ya reject ho.

  #### Real-Life Example (Company Gate)

Socho ek company building hai:

- Employees = trusted traffic

- Visitors = untrusted traffic

- Security guard/Enrollment Scanner = iptables

- Rules list = Employe ka finger prints DataBase mein store hote hain.

Jab employee finger scan krta hai to DataBase mein mjood Finger templetes se matching hoti hai or agar match kr jaye to **Access Granted** or agar mismatch ho to **Access Denied** yani gate open nhi hota or Untrusted .

Employee → allow

Unknown visitor → deny

Bilkul isi tarah iptables har network packet ko rules ke through check karta hai.

--

#### Netfilter

Netfilter Linux kernel ka ek firewall hai jo incoming, outgoing, aur forwarding network packets ko rules ke zariye process karta hai, jaise allow, block, ya modify karna.

Netfilter asli engine hai, aur iptables / nftables us engine ko control karne ke tools hain.

Yani ***IPTables*** mein hum rules likte hain k kis IP k input,output,fowarding block krna hai.  

___

# Lec # 15. IP Tables Firewall lD SE Linux

Types of IPTable :


***1. filter***

***2. nat***

***3. mangle***

***4. raw***
___

***1. filter***

ye layer **Traffic allow / block karne,Firewall rules banana or Security control krne** k lye use hoti hai.

***Ye bydefault table hoti hai***

***2. nat***

  **Network address Translation**

ye layer private IP ko Public IP se change krne k lye,internet sharing ,ports forwarding k lye istemal hoti hai.

![alt text](image-126.png)

***3. mangle***

ye layer IP Packates k **headers**ko modify krne or packets ko mark krne yani packets ki **priority** set krne ka kaam krti hai.


***4. raw***

Packet ko connection tracking se bahar nikal deta hai taa k Performance improve rhee.

**VIP lane jahan checking skip hoti hai.**

___ 
### Firewalld 

REHL 7,8 Mein **IPtables** ko **Firewalld** ka name diya gaya hai.

Jis tarha REHL 6 mein Tablelayers(filters,nat,RAW) hoti hain usi trha REHL 7,8 mein **Zones** hoti hain.

REHL 7,8 mein bydefault layer **Public** hoti hai.

Commands

      service ka status check krne ki command 
                  |
      `systemctl status firewalld`
      ______________________________
    for cheching currently active firewall zone
                 |
      `firewall-cmd --get-active-zones`

      __________________________________
      Active zone ki complete details check krne k lye
                  |
      `firewall-cmd --list-all`
____

#### Firewalld mein service ko add krne ki command:
      firewall-cmd --permanent --add-service=samba
       output = success

![alt text](image-127.png)

#### Important!

Kisi bi service ko a**llow/add** krne ya **deny/remove** krne ya firewalld mein kisi type k changes krne k baad lazmi hai k firewall service ko **reload ye restart** kiya jaye ta k service ki **configration files** RAM mein changes k saath load ho jaaiyen.

-     firewall-cmd --reload

___

#### Firewalld zones

Firewalld k zones check krne ki coommand:


-     firewall-cmd --list-all-zones
 
 #### Firewalld ki bydefault Zones k 9 Zones hote hain.

or jis zone k name k saath **(active)** is k matlab hai k wo zone active yani running halat main hai.


1.  drop
2.  block
3.  public(active)
4.  external
5.  dmz
6.  work
7.  home
8.  internal
9.  trusted

#### Active zones ko check krne ki command 

-     firewall-cmd --get-active-zones
      
![alt text](image-128.png)

___

### SELinux

***Defination:-***

SELinux **(Security-Enhanced Linux)** ek **Mandatory Access Control** (MAC) security system hai jo Linux kernel mein built-in hota hai۔
Ye **extra security policies** enforce karta hai aur **extra security layers** provide karta hai taa k processes aur users ka system resources(jaise files, network aur ports)ki access ko ***traditional rwx permissions*** se pehle  control kiya jaye.

              SELinux ki 3 Conditions 

                   SELinux
                  /   |   \
                 /    |    \
                /     |     \
               /      |      \
              /       |       \
       Disabled    Permissive  Enforcing
        |               |           |
    bilkul band     allow+logs   block + log
    everyone allow    Warning 
 

### ! Important Flow of SELinux



**Enforcing** se **Permissive** ya **Permissive** se **Enforcing** ki janab switch krne k lye machine ko **reboot** krna zroori ni hai q k ye temporary changes hain or **reboot** ke baad **bydefault mode** fir se **SELinux configuration** file ke mutabiq ho jata hai **(/etc/selinux/config).**

- id numbers

  - Enforcing = 1

  - Permissive = 0 
  
 - Command for switching  

    - `setenforce 0`  = Enforcing to Permissive
    - `setenforce 1`   = Permissive to Enforcing


agar in dono conditions main se Disable ki taraf switch krne k lye lazmi hai k machine **reboot** hoo.kyun ke **kernel** SELinux ko load karne se pehle decide karta hai ki **enable ya disable** ho.

- Temporary command (setenforce) se disable nahi kiya ja sakta.

SELinux ko **disable** krne k lye **/etc/selinux/config** me line change karni hoti hai:

- **/etc/selinux/config**

  - ***SELINUX=disabled***


![alt text](image-129.png)
___

### SELinux working:

- SElinux working k 2 components hain.

  - Aik component services per kaam krte hai.

  - doosra component Directories and Files par kam krta hai.

Components.

1. Boolean Value 
2. Context Value 

- Boolean Value 

  - 1=on,
  - 0=off

Apply on services  jeese (ftp,samba,nfs)

- context value 

applyed on Directories and files.

yani agar aap ne services k lye selinux ko **block/allow** krna hai to **Boolean value** use ho gi.

or agar aap ne **Files&Directories** per selinux apply krna hai to aap Context value use krein gee.


### Scenario:

agar ftp k lye boolean value 0 hai jab k ftp k lye port 21 bhi open hai to kia connection bany paye gaa?

**Connection establish nahi hoga**

Firewall sirf yeh dekhta haik Port open hai ya nahi?”

SELinux yeh dekhta hai k
Process ko kaam karne ki ijazat hai ya nahi?

Firewall ne service k lye koi resistance create nhi ki lekin SElinux request ko block kr de ga Q k rules mein **ftp** ki **boolean value = 0**.

**SElinux is OS level security for services .**

yani agar kisi service ko aap ne allow nhi bhi kia hoa to us ka page hack hone par us ko allow kr k bhi ap ki service ko use na kia ja skee.

___

# Lec # 16. DNS Caching Server land DNS Server

DNS :-

DNS **Domain name service/system** name to IP system hai jo Domain names ko IP number mein convert krta hai.

WHy? DNS kyun zaroori hai?:

1. Because computer,servers can not understand domain names only can understand IP numbers and than communicate with one and others.

in this case DNS resolve this issue and convert domain names into IPs.

For Example:

Jab hum `www.youtube.com` likhte hain to computer understand nhi kr pata kia open krna hai is ilye DNS is `www.youtube.com` ko is k public IP mein convert krta hai jo Domain mein configure kia gaya hota hai.


2. Har website ka IP yaad rakhna padta q k digits ko yad rakhna mushkil hota hai Names k muqaable mein.

3. Digits yaad krne hote to Internet use karna bohat mushkil ho jata.
___
### Caching Server

CentOS 7 machine per **Caching server** create krne ka method.

 ### 1.  Package
 sb se pehle aap DNS software choose karo .

mein ne ye software use kia .

- **BIND-* (named)**

Package install kr lein...


  -        yum install bind-*
___

### 2. Config File 

Package isnstallation k baad service ki config file find ki.

bind-* (named) by default config file yahan se read karta hai:

      /etc/named.conf
Mein is config file ko move kr diya taa k ye file RAM mein load na ho paye 

Balkee is ki jagah mein **`/var/named/chroot/etc/`** mein **`named.conf`** file bnai .

    pwd:
          /var/named/chroot/etc/

        touch named.conf

### ! chroot mein config file bnane ka maqsad .

DNS (BIND) ko system se isolate karna taa ke agar DNS hack ho bhi jaye to poora OS disturb na ho.

yani.

- Attacker sirf chroot jail ke andar rahe ga

- Real OS safe rehta hai

- Damage limited hota hai
___

### 3. service start krna, ports, Firewall allow krna ,

Package installation or Config file isolate krne k baad .
        
1. Service ko start kiya 

        systemctl start named-chroot
        systemctl status named-chroot

        Active ( Running)

--

 2. Ports 

Service ko start krne ksaat Port bhi open ho jati hai.

- DNS port 53 use karta hai.



      ss -tulnp | grep :53

![alt text](image-132.png)
--

  1. Firewall mein service ko allow kiya.

         firewall-cmd --permanent --add-service=dns
      
         Pehle bhi likha hai k Firewall mein changes 
          ko RAM mein load krne k lye 
          servce ki reload krna lazmi hai.


          firewall-cmd --reload

Service ko check kr lein k firewall mein active  ho gai hai.


    firewall-cmd --list-service

![alt text](image-131.png)

___

Domain Fields.

`google.com.` aik mukamal  domain hai.

usually domain 3 levels se banti hai. 

- ***Root level(.)***
  - sb se last pe aik dot hota hai jo usually likh nhi jata lekin ye (.) DNS ka Root he.
  
- ***Top level(com)***
  
  - TLD wo last part hota hai jo domain name ke end mein hota hai, jaise .com, .org, .net.
  - Domain category batana (type / use),Domains ko unique rakhna.

        .com – Commercial

        .org – Organization

        .net – Network

        .info – Information
- ***Second level domain(name jese k `google`)***
  
- Website ki identity batata hai yani Brand / company ka naam represent karta hai.

- DNS hierarchy maintain karta hai

### ! Q:

 `Google aur com ke beech jo . hai wo kya hai?`

Short answer:

Dot (.) DNS ka separator hai jo domain levels ko alag karta hai.

Dot **(.)** ka maqsad (purpose) levels ko separate  karna 

yani

kaunsa part TLD hai

kaunsa SLD hai

___
### Land DNS server

Server bnaane k method :

### 1. config file mein Doamin ki entry


      vi named.conf

File pehel empty thi jab hum ne **Caching  serve** bvnaya tha ab file mein aap **doamin** or Zone file ka **path** likh dein taa k system jab ye file read kre to Domain k accprding file mil jaye.

    sysops.local" {
    type master;
    file "var/named/sysops.db";
    };


#### 2.  Directory Setup

BIND ka bydefault location hai /var/named/ ya chrooted environment mein /var/named/chroot/var/named/.
Yahan zone files create ki jati hain.

    cd /var/named/chroot/var/named
    ls

Output example:

`chroot,  chroot_sdb,  data,  dynamic,  dyndb-ldap, named.ca,  named.empty,  named.localhost,  named.loopback,  slaves`



####  3. Zone File Create Karna

Apni domain ke liye zone file create karo. Yahan humne sysops.db create kiya.

ye file us path pe ctreate ki jo mein ne **named.conf** file mein **domain** k saath **mention** kia tha.

 Create new zone file:

 - `/var/named/chroot/var/named`

       touch sysops.db
        ls


        Output:

        `chroot,  chroot_sdb,  data,  dynamic,  dyndb-ldap,  named.ca,  named.empty,  named.localhost,  named.loopback  slaves  ***sysops.db***`



#### 4. BIND Restart 

- Restart BIND service

   -     systemctl restart chroot-named             


#### 5. DNS Queries Test Karna (Local DNS Server)

ab apne domain k  IP ko localy **dig** kr ke check kr lein k server kaam kr rha hai ka nhi.

jeese k 

    dig @192.168.18.121 facebook.com
ye pehli dafa kuch toda time lee ga

    ;; Query time: 712 msec

yani ye 712 msec mein request complete kr rha hai 

agar aap ye dobara krein gee to `;; Query time: 0 msec` mein kaam krta hai yeni **caching server** kaam kr rha hota hai.

___

# Lec # 17 Domain Registration LIVE Web Hosting

#### Web Hosting :

Web Hosting aik service hoti hai jisme aap apni website ki files (HTML, CSS, images, videos, code, database) ko internet par hamesha online chalne wale server par rakhte ho, taake duniya ka koi bhi banda browser (Chrome, Firefox) se aapki website dekh sake.

#### Web Hosting mein kya cheezen hoti hain?

-  Public IP address
-  Storage (Disk space)
-  Bandwidth
-  Web server (Apache / Nginx)
- Securit (Firewall, SSL)

___
### Method OF Web Hosting Server

AWS EC2 + Public IP + Apache use kar ke **Web Hosting Server*** banane ki step-by-step checklist.

#### 1. SSH of machine 

phel maachine ka session le lain or session mein aap machine ka **Public IP** use krein.


 #### 2.  Apache Installation & Service

agar aap k pass Amazon Linux / RHEL machine hai to.

Firstly aap check kr loo k aap k pass apache/httpd package install hai .

          command

    rpm -qa | grpe httpd

agar nhi to install kr loo mein ne bhi kia .

            commands

    yum install httpd -y
    systemctl start httpd
    systemctl enable httpd

#### 3. Document Root (Index.HTML)
    bydefault Path

                  /var/www/html/index.html


**index.html** file mein aap koi content write krdain jo aap web Page pe Publicaly share krna  chahte hain.

      cd /var/www/html
      vi index.html

     Content:
      My name is Ghulam Yasir.
      etc....

#### 4. Apache Virtual Hosting 

Hosting config k bydefault path jo apache use krta hai .
 
 yahn hum major config file k bjaye child config file **conf.d** mein **vhosts.conf** file  bnaye ge or us file mein hum virtual Hosting conatiner bnaye gee.


    cd /etc/httpd/conf.d/

    vi  vhosts.conf
           \
    Content:\
             \
    <VirtualHost *:80>
    ServerName ghulamyasirdevops.com
    ServerAlias www.ghulamyasirdevops.com

    DocumentRoot /var/www/html
    ErrorLog logs/yasir_error.log
    CustomLog logs/yasir_access.log combined
    </VirtualHost>

ab apache ko reload kr lein. ta k chnages RAM mein load ho jayen.

    systemctl reload httpd


  
#### Security Groups checking 

![alt text](image-133.png)

![alt text](image-134.png)

![alt text](image-135.png)

![alt text](image-136.png)

___

# Lec # 18 Xinetd SSH

### xinetd

xinetd (Extended Internet Services Daemon) Linux ka aik super-server hai.

Is ka kaam ye hota hai ke network services ko on-demand start kare yani service tab hi chale jab koi client connect kare.

ye multiple child services ko efficiently work krne ,security ko yaqeni bnata hai or memory utilizaing ko control krta hai.

![alt text](image-137.png)

![alt text](image-138.png)


### SSH

Definition:

SSH aik cryptographic protocol hai jo remotely system management k liye  aur encryption, authentication k through data transfer ko secure banata hai.

#### 1. SSH service management (CentOS 7)

Check status:

      systemctl status sshd


Start service:

      systemctl start sshd


Enable at boot:

      systemctl enable sshd


Restart after config change:

      systemctl restart sshd
___
#### 2. SSH security & config

SSH ki Main config file:

      path


     /etc/ssh/sshd_config

Config file ki Important options:

    Port 22

  SSH server kis port par listen kare — ye define karta hai.

      PermitRootLogin no
Root user ko direct SSH login se block karta hai.

 Kyun zaroori?

Root = full control

Yani 

Pehle normal user se login kro 

Phir root bano password k through .


      PasswordAuthentication no

ye agar **yes** kr dein to aap password s **Remote access** le skta hain or **NO** rhe ga to **SSH KEY** k through hai access le skte hain.


changes k baad file ka syntax Check :

      sshd -t
---
#### 2. Port checking commands

Check listening port:

    ss -tulnp | grep ssh

SSH TCP port 22 use karta hai, jab tak admin usay manually change na kare.

___
# Lec# 19.SAMBA

Samba aik open-source network service hai jo SMB/CIFS file-sharing protocol use karti hai, jis ke zariye hum Linux to Linux aur Linux to Windows systems ke darmiyan files aur printers share kar sakte hain, aur is mein users ko username aur password ke zariye authenticate kiya jata hai.

#### SAMBA SERVER–CLIENT PRACTICE.

1) Pehle check kia
  
        rpm -qa | grep samba


-  Sirf samba-common aur libs installed the
-  samba.service exist nahi karti thi
Iska matlab actual server package install nahi tha


2) Full samba install kia

        yum install samba-* -y


 Is se:

smbd

nmbd

samba tools
sab install ho gaye

___
3) Services start aur enable ki
  
                systemctl start smb
                systemctl start nmb

        systemctl enable smb
        systemctl enable nmb


Check:

    systemctl status smb
    systemctl status nmb


**Dono active (running)**

___

4) Samba config location
  
        cd /etc/samba/
ls


Main file:

        smb.conf
___

5) Samba rule yaad rakho

smb.conf ke 2 parts hotay hain

1. [global]

2. [share]
___
6) Custom share banaya

Directory:

      mkdir /opt/fileserver


Config file mein section bnao :

      [section]
      path = /opt/fileserver
      hosts allow = 192.168.1.0/24

___

7) Samba mein config apply ka tareeqa

 NFS jaisa  nahi hota

         exportfs -rv 
 Samba mein:

      testparm


 agar error na aaye = config OK

 ___

 8) Important SAMBA rule (EXAM + PRACTICAL)

!  **Har Samba user ka Linux user hona zaroori hai.**

 Direct samba user add:

      smbpasswd -a thejin


**Error aya**

- Sahi tareeqa:

      useradd thelion
      smbpasswd -a thelion

___

9) Ports yaad rakhne wali baat

Samba ports:

- 137 → NetBIOS (nmbd)

- 139 → SMB

- 445 → File sharing

Check:

    ss -tulnp | grep 137
    ss -tulnp | grep 139
    ss -tulnp | grep 445
___

**important Tips.**

- Har Linux user → FTP/mail ho sakta hai

- Har Linux user → Samba user nahi hota

- Samba apni separate password DB use karta hai

- testparm must after config change
 ___

 ### SAMBA config file mein shared Tags .

 ![alt text](image-139.png)

1. ***create mask = 0644***

 shared Path **/opt/server** mein New files ki permission

Matlab:

Owner ki lye **read + write** ki permission ho gi

Group k liye → **rea**d ki permission ho gi

Others k liye bhi **read** ki permission ho gi

 - full File permissions= -rw-r--r--
directory mask = 0770


---

2. shared Path **/opt/server** mein New directory ki permissions.

Matlab:

Owner k liye full access ho gi .

Group k liye  full access ho gi.

Others k liye  no access ho gi.

 jab Folder banay ga to ye permissions set ho gi: `**drwxrwx---**`

___
 3. **hosts allow = 192.168.1.0/24**

 Sirf is network ke clients access kar sakte hain
Baaki sab deny ho jayein ge

___
4. **path = /opt/fileserver**

 Actual Linux directory jis folder ka data share ho raha hai.
___

5. **read list = thejinn thepen**

Yani Ye users thejin,thelion:

- sirf read kar sakte hain

- write nahi kar sakte

___
### Active Directory (AD) kya hai?

Active Directory Microsoft ki ek technology hai jo networks mein users, computers, aur resources ko manage karne ke liye centralized system provide karti hai. Basically ye ek digital address book hai jahan se aap network ke sabhi users aur devices ka access aur permissions control kar sakte ho.

Linux mein AD k concept nhi hai lekin SAMBA k through windows se connection kr k hum Widows ki AD ko acces kr skte hain is k lye Linux mein **windbad** package hoa lazmi hai.


Winbind – Samba ka ek component jo Linux ko Windows AD ke users aur groups recognize karne deta hai.


**LDAP Integration** 

 AD ka data LDAP (Lightweight Directory Access Protocol) ke zariye Linux ke systems pe available hota hai.

- LDAP Ports:

1. Plain LDAP:

**Port 389 TCP/UDP**

Ye encryption ke bina normal LDAP communication ke liye use hota hai.

2. Secure LDAP (LDAPS):

**Port 636 TCP**

Ye SSL/TLS encryption ke saath secure communication ke liye use hota hai.