# Linux Fundamentals
##  1.Introducing

### What is Linux ?

 ```Linux is a family of open-source, Unix-like operating systems based on the Linux kernel.```

 Linux itself is just the kernel.

### How It Became Open Source?

The origin of Linux as an open-source project is directly tied to the decision of its creator (Linus Torvalds) to adopt a specific software license.

Linus Torvalds, a Finnish computer science student, began developing the Linux kernel in 1991 as a personal hobby project. He aimed to create a free operating system kernel for his personal computer.

### What we read in intensive and intensive++?

see sceen shot.....

![alt text](image.png)

### Basic Commands 

```df```

ye command OS ki partations deekhny k use hoti hee 

```df -h``` sy hum partation ki deatils readable form me deekh skte hee
see screen shoot....
![alt text](image-1.png)

```date ``` command see hum copmuter ki date settings beekh skte hee or change bhi k,r skte hee.

```pwd``` "print working directory" 

is command see hum maloom kr sktee hee k hum kis file/directory mee heen.

### What are commands/Flags?

![alt text](image-2.png)

- 1.Commands

Commands and Flags basic concept hain jb aap linux me command line interface k saath kam kr rhe hote hain.

 command ek hukum hoti hai, jo computer ko kisi khaas kaam ko anjam dene ke liye di jati hai.
- 2.Flags

 Flags (also called options) jo kisi command k behavior ko change krny k lye use hoty hain.
 
 - Flags usually start with hyphen -  .
 
   - hyphen - (short form) 
   - double hyphen -- (long form).

 - Examples

   - -l: long listing format

    - -a: show all files (including hidden ones)
### Paths

Har OS mee 2 types k paths hooty hain

1. Absoloute Ptah
2. Relative path

#### What is absoloute Ptah?

Yeh aisa address hai jo hamesha computer ki jadd (root) yaani \ se shuru hota hai.

Jaise kisi shehar ka pooray ka pooray address mein house number, street, colony, sab kuch likhna.

  

  - Hamesha / (forward slash) se shuru hota hai.

- Examples

  - /home/ahmad/Documents/meri_file.txt

  - /usr/bin/ls
#### What is relative path?

Yeh aisa address hai jo aap ki haal ki jagah (Current Directory) se shuru hota hai.

Jaise aap kisi ko kehna "Yahan se seedha chalo, phir left mur jana."


 Kabhi bhi / se nahi shuru hota.

 . (Dot) = Abhi jahan khade hain (Current Directory)

.. (Double Dot) = Upar wala folder (Parent Directory)

---

- For Example  aap /home/ahmad mein hain):

  - ./Desktop = Yahan se Desktop folder mein jao
  - ../zeeshan = Upar jakar zeeshan folder mein jao
  - ----

## 2.File System Hierarchy Overview

**Files aur folders ko ek tarteeb (structure) ke sath arrange karna jese ek tree ke branches hoti hain File System Hierarchy hai.**

Har cheez ki bunyaad ```/ ``` directory sy hoti he  jis trha tree ki bnyaad root he isy trha linux main bhi```root / ``` directory sb files/directories ki bnyaad he .

_**Is ko ```Father off al files ``` bhi ke sktee hain.**_

![alt text](image-3.png)

### Hierarchy Kyu Zaroori Hai ?


#####  Asani se Access
Har file ka pata hota hai kahan hai, is wajah se access lena asaan ho jata hai.

##### System Management Easy
Admins ko system samajhne mein asani hoti hai, kyunke file system munazzam hota hai.

#### Security & Permissions
Har folder ka apna role aur access level hota hai, jo security ko behtar banata hai.

#####  Maintenance Easy
Files ko manage, update, ya delete karna asan hota hai, kyunke sab kuch apni jagah par hota hai.

  ***Inshort*** File System Hierarchy aik computer ki tarteeb hai jo files aur folders ko aik mustaqil  tareeqay se arrange karti hai, jis se system chalana, maintain karna, aur secure rakhna aasan ho jata hai.

###  FHS main absolute path or relative path ko use krte hoye files/directories mee jana

```See Screenshoot```

![alt text](image-4.png)


### If Linux not installed how to use linux.

Agar ap ne apne computer par Linux install nahi kiya, to ap yeh alternative istemal kar sakte hain.

 - Online Linux Terminals
-  AWS Free Tier
- Mobile Phone Terminals

Ap Linux ke commands baghair koi machine install kiye online terminals ke zariye practice kar sakte hain. Google par "Linux online terminals" search karen.



![alt text](image-5.png)


google par wbsite mojood hain jin see hum directly Linux ka terminal use kr skte hain.

![alt text](image-6.png)

### Commands/Flags

- Commands
Commands atlast a programs
Linux mein lagbhag sab commands C language mein develop kiye jate hain aur phir binary mein convert kiye jate hain.
- Flags

  Flags (options ) commands ke sath use kiye jate hain unke behavior  ko change krty hain. Ye hyphen (-) ya double hyphen (--) se shuru hote hain.

agar kisy commands k flags maloom krny hoon to ```--help``` command use hoti hai.

See Screenshot

![alt text](image-7.png)

### Flags ka use case ...

agar command k saath flags lagay jaen to commands ki power yani kaam krny ki taqat or treeqa kar change karty hain .

 Screenshots sy wazaht ..

 Is SS. main simple command k saath 1 directory k andar 1 or dircetory bnan rha hai lakin output main keh rha hai directory ni bn skti.

 ![alt text](image-9.png)
 
 is SS. main command k saath ```-p``` flag use krty haoy same command run krta hain directoey bn jaaty is maloom hota hai k flags k role Linux main bohat eham or strong hai.
 ![alt text](image-10.png)

 ```-p``` ka matalb hai k jis directory main directory create kr rhee hain us ko parent maan kr directory bnao . is koi error eist ni ho gaa.

## User Switch krna ..

### Linux Multiuser Multitasks hai dekhain.

hum neechy dye gae screenshot me mojjod commands ko follow kr k user switch kr skty hain .

![alt text](image-8.png)

_is sy maloom hoa k Linux multiuser mutitasks hai._
____
##  3.About some Directories....

Linux main veesy to beshumar directories hoti hain jin main  har makhsso kaam ko krny k lye commands hoti hai lakin yhan kuch directoreis ka overview jany gy jo basic hain .

![alt text](image-11.png)
|   directories | opreations                                                                  |
|-------------|----------------------------------------------------------------------------------------|
| /dev        | Hardware ke parts (jaise printer, hard disk) ko chalane wali special files yahan hoti hain. |
| /etc        | Computer ke system ki settings aur programmes ki configuration files yahan hoti hain.  |
| /lost+found | System kharab hone par bach gayi files is jagah milti hain.                            |
| /lib        | Programmes ko chalane ke liye zaroori basic files yahan hoti hain.                     |
| /var        | Woh files jo waqt ke saath badalti rehti hain, jaise logs, emails, ya database.        |
| /opt        | Zyada connections waly software (jaise games) yahan install hotey hain.                    |
| /mnt        | CD, USB, ya koi doosri drive computer mein lagane ki temporary jagah.                  |
| /bin        | Saada (basic) commands jo har user istemal kar sakta hai, unke programmes yahan hain.  |
| /sbin       | Superuser (Admin) ke khaas system commands aur unke programmes yahan hain.             |
| /boot       | Computer ko ON karte waqt chalne wali sab se ahem startup files yahan hoti hain.    

yhan par lib main ```.SO``` files ka zikar hoa jo k bilkul nai hain maery lye is ki kuch wazaht ...

Ye aik compiled binary file hoti hai jo multiple programs ke liye shared code provide karti hai.

### File editors

Linux files ko edit krny k kaafi editors available hain jo different treeqa sy work krty hain hum kch aditors k baary main padheen gy..
 1. vi 
 2. vim
3. nano

-  vi editor
File  main mojood content ko remove krny,add krny or save krny k lye use hota hai.
     - file main changing kry k lye ya add krny k lye ```vi  filename``` ki command run krain . jis file main kaam krna us file ka name dena hoo ga.
     - ab aap file k andar hain file main kisi line delete krn ho to line ko select kr ``dd`` press kain line delete ho jaye gi.
     - agar content ki kisi line ko copy krna hoo to line ko select kr k ```yy``` type krain file copy ho jaye gi.
   - ab agar copy content ko paste krna ho jhaa paste krna ur row ko selct kr k ```p``` type kree content save ho jaye gaa.
    - kaam krny ka baaad aap ne jo changing ki hain us save krny k lye pehle aap insert mode ko khatam krain ```Esc key``` press kr k or phi aap ```:wq``` write kr k enter kr dain aap file save kr k baahir aa jayee gee.
     - agar bahir nai ana to ```:w``` wirte kr k enter kr dain file save ho jaye gi lekin aap file k anar hi hain.
     - agar aap ko forcely koi content save krna ho to ```:eq!``` write kr k enter krain.

  ![alt text](image-12.png)
____
## 4. Softlink and Hardlinks
softlink kisi file ka shortcut hota hai.isy _**symbolic**_ link bhi kehty hain.
- **Softlink Create krny ka treeqa**..
  - agar mey pass 1 file hai jis name ``` myfile``` hai is ka Softlink bnany k lye command ```ln -s myfile yasir```
ko run kro ga ab mery pass ```yasir ``` as a softlink ho ga.
![alt text](image-13.png)
  - jb hum file main koi content likheen gee to wo soft link main bhi show kry ga as same agar hum softlink main vi editor sy kuch write kreen gy to woh parent file main bhi show ho ga. in short both are working same. **see screenshot...**
  
  ![alt text](image-14.png)
  
   - agar parentfile (yani jis file ka softlink create kia hai)us ko delet kr dain to softlink drop ha jaye ga yani work ni kre ga . Lakin agar same name sy dobara file bna di jaye to softlink kam kre ga as per same .
![alt text](image-15.png)

### Directories and partitions..

- Directories
  - ye daigram directories ko zahir krti hai. 


![alt text](image-17.png)


- partitions
  
 ye daigram partitions ko zahir krti hai. 


![alt text](image-16.png)

  - Iska main maksad yeh hai k Linux system main stability aur security k liye directories ko alag partitions main divide karte hain, taake ek issue doosre ko affect na kare.
  - Yahan pe directories jaise /usr, /home, /var, /boot ko alag-alag partitions banaya gaya hai.
  - Partitions ka maksad hota hai data ko alag rakhna (isolation). Agar ek partition corrupt ho jaye to baaki safe rehte hain.
  - Partations ko view krny k lye ```df -f``` command use hotia hai.
  ![alt text](image-18.png)

  - Agar directory df -h main show ho rahi hai → wo partition + directory hai.
  
  ![alt text](image-19.png)

- Agar directory sirf ls / main show hoti hai aur df -h main nahi → wo sirf directory hai, partition nahi.

![alt text](image-20.png)

### Screenshoot k mutabiq..

- #### Real Partitions
  - /, /home, /boot

 - #### Virtual/Temporary Mounts (RAM or kernel provided):
    - /dev, /run, /sys, /dev/shm, /sys/fs/cgroup, /run/user/1000
- Kernel yeh sab virtual filesystems banata hai because:

  - Hardware ko files ki tarah represent karna (/dev).

  - Runtime system info aur process info dena (/proc, /sys).

  - Fast, temporary storage provide karna (/run, tmpfs).

  - User-space aur kernel-space ke beech ek bridge create karny k lye. ta k OS kaam kr skeen.

- #### Only Directories (ls / main hain but df -h main nahi):

    - bin, etc, lib, media, mnt, opt, proc, root, sbin, srv, tmp, usr, var
  
###  Advantage and disadvanatge of softlink and hardlink
🔹 Soft Links (Symbolic Links)

Yeh Windows ke shortcuts ki tarah hotay hain.

| **Advantages**                                                                                  | **Disadvantages**                                                                 |
|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| Easy to access- Tum kisi file/folder ka shortcut bana sakte ho aur use easily access kar sakte ho. | If parent is deleted-child (link) becomes useless (broken link). |
| Can cross partitions- Soft link ek partition se doosre partition main bhi point kar sakta hai.   |                                                                                   |
| Can be created on directories-Tum directory ke liye bhi soft link bana sakte ho. Example: `ln -s /var/log logs_link` |                                                                                   

🔹 Hard Links

Yeh ek tarah ka duplicate reference hota hai original file ka. Matlab dono ek hi inode (file system entry) ko point karte hain.

| **Advantages**                                                                                                                         | **Disadvantages**                                                                                          |
|-----------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| Type of backup- Agar ek link delete ho jaye, file ka data doosre hard link ke zariye still accessible hota hai.                        | Cannot cross partitions Hard link ek partition ke andar hi ban sakta hai. Agar file `/home` main hai to uska hard link `/usr` main nahi ban sakta. |
| If parent is deleted, no impact on child - Matlab agar original naam wali file delete kar di, tab bhi data hard link se access ho sakta hai .|  Directories ke liye hard link banane ki ijazat nahi (to avoid loops aur complexity). |

 🔹Simple

**Soft link:** shortcut ( original file pe depand krta hai)

_**Hard link:**_ copy reference (agar original file delet ho bhi jaye to link kan krt hai)

 #### inode number

 Har file ka ek unique inode number hota hai.

Inode ek file ke attributes/properties ko store karta hai.

Inode dekhne ka command hai:``` ls -i filename```

```ls -il ```command ka use kar ke tum file ka long list aur inode details dekh sakte ho.

Inode number pehle se nahi hota, bilkul class roll number ki tarah. Jab file create hoti hai tab usay inode number assign hota hai.

Hardlink files ka inode number same hota hai.

Softlink files ka inode number alag hota hai.

![alt text](image-21.png)

Hum indoe number sy ```-inum``` command ko use krty hoaye maloom kr skte hain hain k konsi file apas main linked hain

![alt text](image-22.png)
----
## 5. Ownership permissions overview

### 🔹 Linux Version, Kernel aur Architecture check karne ke commands

1. ```cat /etc/redhat-release```Linux distribution aur uska version check karta hai.

2. ``` uname -r ``` Kernel ka version dikhata hai.

3. arch``` Machine ki architecture (32-bit / 64-bit) show karta hai.

![alt text](image-23.png)


Linux main jab hum ls -l command chalatay hain, to file/folder ke details aati hain jo 9 alag-alag fields hoti hain. Yeh slide unhi ko explain kar rahi hai.



```-rw-r--r--  1  root  root  0  May 10 08:03  myfile.txt```
### Fields ka breakdown (1 se 9):

1. Type of file.

- Pehla character batata hai ke yeh file hai, directory hai ya link.

  - (-)normal file

  - (d) directory

  - (l) link

2. Permissions

**_Next 9 characters: rw-r--r--_**

Ye batate hain ke owner, group, others ke paas read (r), write (w), execute (x) permissions hain ya nahi.

3. SELinux

- Security context (kabhi show hota hai, kabhi nahi) magar normal ls -l main hamesha visible nahi hota.

4. Link count

- Yeh batata hai ke file ke kitne hard links hain.

   - 1 sirf ek naam se refer ho rahi hai.

5. Owner (User)

- Yeh batata hai file ka owner kaun hai.

  - root

6. Group name

- File ka group jo access control ke liye use hota hai.

  - root

7. Size in bytes

- File ka size (bytes main).

  -  0 matlab empty file hai.

8. Access / Modification time

   - Last modification ka time show karta hai.

-  May 10 08:03

9. Filename

- Actual file/folder ka naam.

  -  myfile-txt

#### Permission Explanation:

r = read (padh sakta hai)

w = write (edit/delete kar sakta hai)

x = execute (run kar sakta hai, agar script/program ho)

-= no permission


rw-  Owner ke paas read + write permission hai

r--  Group ke paas sirf read permission hai

r--  Others ke paas bhi sirf read permission hai

 - 9 characters: rw-r--r--

   - pehly 3 owner k lyee hoty hain.

    - 2nd 3 gruop klye hooty hain.

    - last 3 other k lye hoty hain.

- Owner file ko read + write kar sakta hai

- Group aur Others file ko sirf read kar sakte hain, edit ya delete nahi kar sakte

#### changing permissions.

- gar kisi file ki permission ```rw-r--r--```

-  ```rw-```his ka matlab hai k is file k owner(user) ko read&wirte ki permission hai (yani user is file ko pad skta hai or file main likh bhi skta hai).

 - ```r--```agy is file ka group yani(ye file jin users k group ko avail hai)wo bs file ko pad skty hain.

 - ```r--```last main file user or is k group k ilawa jin ko avaiable hai yano others wo bhi sirf read kr skty hain.

### How can change permissions?

Hum as a root user kisis file ki permissions ko change kr sktee hain is k lye ```chmod``` command use hoti .

Yhan screenshots main kuch wzahat deekhen...

agar kisi ko permission deni hai to + use ho ga .

![alt text](image-25.png)

 yhan par hum permissions off krein gy ..

agar kisi k lye permissin off krni hoo tu - use ho ga .
Screenshot dekhain..

![alt text](2025-09-30_23-23.png)

hum 1 saath sb ki permission bhi off kr skty hain jis ka prectical neechy screenshot main hai.

![alt text](image-26.png)

____

## 6. Editors Ownership Permission

vim editors main 

### Vim Cheat Sheet (Basic)

| Kaam | Command |
|------|----------|
| **Modes** | `Esc`  Normal mode, `i`  Insert, `v` →Visual, `:`  Command-line |
| **Save** | `:w` |
| **Quit** | `:q` |
| **Save & Quit** | `:wq` ya `ZZ` |
| **Quit without saving** | `:q!` |
| **Undo** | `u` |
| **Redo** | `Ctrl+r` |
| **Copy  line** | `yy` |
| **Copy  word** | `yw` |
| **Cut (delete) line** | `dd` |
| **Cut (delete) word** | `dw` |
| **Paste** | `p` (baad me), `P` (pehle) |
| **Select (character)** | `v` |
| **Select (line)** | `V` |
| **Search text** | `/word` |
| **Next match** | `n` |
| **Previous match** | `N` |
| **Show line numbers** | `:set number` |
| **Hide line numbers** | `:set nonumber` |

#### file ki ```rwx``` pemissions kia hain?

- agar aap k pass ```r``` yani read ki permission hai too aap file ko read kr sktee ho , file ko copy bhi kr sktee hoo,
- if you have ```rw``` permissions o aap file ko modify yani file main likh bhi skty hain, file ko delete bhi kr sktee hain.
- if you have ```x``` execute permission so aap us file ko run bhi kr sktee hoo. ye permission scripted file k lye hoti .![alt text](image-27.png)


yhan phir permission ki baat krian gy..

1 normal user kisi ko permissions ni de skta jesa k is screen shot main dehay gay hai 1 user kisi or ko execute ki pemission dee rha hai lekin permission denaied ka error a rha hai. is ka matlsb hai k aap as a normal user ksis ko koi permission ni skty ka wo file ko read wrote ya execute kr skee. 
![alt text](image-28.png)

### chattr command
(change attribute) Linux command hai jo file ya directory ke special attributes set/change karne ke liye use hoti hai.

jb ye kisi file ko chattr kr dya jata hai to file na to modify ho skti hai or na hi delete . is file root user bhi delete ni kr sktaa.

file cahttr k lye command:```cahttr +i myfile```

![alt text](image-29.png)

file cahttr khatam krny k lye command:```cahttr -i myfile```

### octalway  for permissions

ye digit k saath permission grant krny ka method hai.

![alt text](image-30.png)

screenshoot k mutabiq data file ki pemissions ```rw-r--r--`` hai to ab is file ki permission octalway sy change krni hain .

- r=4
- w=2
- x=1
  
ab sb k lye `rwx` ki permission on krni hain.

`chmod 777 myfile`

![alt text](image-31.png)

#### agar 1 command hai or us main 10 ya 20 users hain jo us file ko use krty hain to un ko permission deny k lye 1 alag command use hoti hai.
command:`setfacl u:username:rwx filename`

agar check krna ho k kis user ko access control list sy permission di gai he

command:`getfacl file name`

![alt text](image-34.png)

agar kis user ko `acl` access control list sy nikalna ho to ye coomand use hoti hai.

command:`setfacl -x u:username:rwx filename`

___
## 7. permissions and run level

- agar ksis file ki sari mermissions odd hain to phir bhi file ka owner or root user file ko overwrite or delete kr ksty hain.

- agar kisi file ki averall permission off kr dain or us ki parent directory ki jo permissions on hoo gi wo users or group isteaml kr k wo kam kr skty hain jin kk lye directory ki permission on hoo gi is ko Inharit Permission kehty hain

![alt text](image-32.png)

- inherit permission 

  - inherit permission ka matlab hai ke ek file ya folder apne parent folder ki permissions ko automatically le leta hai.
  - Inheritance se permission management easy hoti hai, kyunki har new file/folder ke liye manually permission set nahi karni padti.
- **chattr _command_**

  - ye command kisi inportant file ko secure krny k lye use hoti hain taa k koi bhi yani root user, owner user ya other user is file ko overwrite ya delet na kr skee.

  - ya command sirf important file (confidantial data) k lye use ki jaati hai . 

  - system files ko chattr ni krna Q k logs update hona bhi off ho jaye gee agar system file ko bhi chattr kr dain too
- see screeshot
![alt text](image-33.png)

 chattr command ko htany k baad root user us file delet kr skta hai .

 - chattr command htany k lye ` chattr -i myfile ` likh kr run kr dain aap ki file sy chattr hat jaye gi.

### Runlevels

linux main 7 runlevels hoty hain jo 0,1,2,3,4,5,6 hoty haun.

agar check krna ho k mjoda runlevel kia he to
`runlevel` command use hoti hai.

jb hum runlevel check krty hai to is trha show hota jo screenshoot main dekhya gya hai.

![alt text](image-35.png)

`init` command sy hum runlevel change krty hain.

- about runlevels

  - runlevel 0=HALT
  - runlevel 6=reboot
  - runlevel 1= single user mode

- if your passwor forget how you can go for 1 runlevel?

runlevel 1 main jaany k lye password ki zroorat ni hoti or agar aap password bool gaye hain to aap 1 runlevel main password change kr skty hain.

## 8. Partations

Harddisk ki daigram...

- ![alt text](image-36.png)

  - Is image mein hard disk ke andar ke logical structure ko dikhaya gaya hai — jisme data tracks aur sectors mein organize hota hai, aur ek read/write head unhe access karta hai.


Hardwear ko os k anadr chlany k lye device dirvers use hooty hain.

Device drivers low level programs hoty hain jo haedwear or respective softwera k darmyaan intract krty hain.


####  Partition ka matlab hai hard disk ko alag-alag logical hisson mein divide karna.

- Partition = Hard disk ke logical hisson mein taqseem.

- Linux mein sab kuch / (root) ke neeche mount hota hai.

- Partitions help karte hain system ko manage, secure aur efficient banane mein.

***Command Line Tools***:

- fdisk, parted, lsblk, mkfs
sb sy common tool `fdisk` hai.

 Linux Partition ka Structure 


| Partition Name | Mount Point | Size Example | Explanation            |
|----------------|-------------|---------------|------------------------|
| /dev/sda1      | /boot       | 512 MB        | Boot files ke liye     |
| /dev/sda2      | /           | 20–30 GB      | Main system (Linux OS) |
| /dev/sda3      | /home       | 100 GB        | Users ka data          |
| /dev/sda4      | swap        | 4 GB          | Extra memory           |

Windows main or linux main partaions alag alag tarz ki hoti hain.

| Windows                | Linux                                |
|------------------------|---------------------------------------|
| C:, D:, E: drives      | Everything under `/`                 |
| Each drive is separate | All folders are mounted under `/`    |
| Can't mount folders as drives | Can mount partitions anywhere in tree |

Mount karna ka matlab hai —

kisi storage device (USB, hard disk, partition) ko system ke file system se attach karna taa ke uska data use kiya ja sake.


## 9. runlevels

#### runlevel 3

- Multi-user mode with networking, but without GUI (Graphical Interface).

  - Sirf command line hoti hai.

  - Network kaam karta hai.

  - GUI (graphics / desktop) band hota hai.

  - Server ya repair mode ke liye use hota hai.
  
- Runlevel 3 mein GUI nahi hota,
lekin tum 6 alag login screens (terminals) use kar sakte ho —
har ek apna console session hota hai.

ALT + F1 sy aap pehla console use kr skty hain.
ALT+F2 sy doosry consool main move ho jaaty hain.
 isy trha F6 tk aap 6 consloes main move kr skty haib jis console main jana hon `ALT+F` k saath us ka number likh dain yani   5 main jana hai ton`F5` .

 level3 main TTYs  (teletype terminal) interface chal rha hota hai. yani har chez type krni hogi.

 TTY ek`text scree` hoti hai jahan tum commands likh kar system control karte ho.
Ye driver nahi, balki interface (terminal) hoti hai jo console driver ke upar chalta hai.

![alt text](image-39.png)

Runlevels sirf services aur interface change karte hain.
storage ya file system par koi asar nahi padta.
Matlab agau runLevel3 par kam krty hoaye main runlevel5 py switch kr doo to files remove nhi hoon gi. bs services change ho jati hain storage remove nhi hota.

**Important concept**

Runlevel3 main hoty hoye hum GUI use kr skty hain.

is k lye command `startx` use hoti hai.

agar GUI sy wapis niklna hai too is k lye `pkillx` command use hoti hi.

_**incase..**_

agar desktop py GUI server install ho ga to ye commands chalee gi agar `minimla istall ` ho ga to ye kam ni kry gi q k us GUI pacakge install nhi.

![alt text](image-40.png)

Hum nee pehly deekha or prha hai k:

jb hun singleuser mode (runlevel1) main jaaty hain to bydefault hum login id k begair or password k bagir login kr skty hain.

ab yha hum password set krain gee .

`/etc/sysconfig/init` 

runlevel 1 main rehty hoaye aap `/etc/sysconfig/init` ye run krain too aap k pass 1 file open ho gi `shift g ` dbaa k last py check karin agay `|SINGLE=/sbin/sush|` ayee ga yaha aap is line ko copy kr k neechy paste kr dain or `sush` ki jgha `sulogin` edit kr dain or jo line copy kia hai us k start py # lga k comment out kr dain ab aap k last line hi system read kry ga or is k mutabiq aap ny ab single user modd py bhi login page set kr dya hai .

**_ruslte_**

`:wq likh kr save kr dain or doobar runlevel5 sy runlevel1 (single user mode)main jayee to ab yha login page show ho ga r password maangy ga.
___
## 10.Targets Partitions Logic Concept

REHL 6 main runlevels hooty hain.

Jb k REHL 7&8 mian main targets hooty hain.

- yhaan par hum 2 targets k mutalaq padheen gy 

  - Multiuser Tragets
  - Graphical targets
Current target deekhny ki command..
  
  ` systemctl get-default`

REHL 7&8 main target hooty hain us ka matlab ye nhi hee kn yhan runlevel show nhi hooty agay REHL 7&8 mian bhi `runlevel` ki command run krty hai too aap ko runelevel show hoo gy.as user friendly.

![alt text](image-42.png)
jeesy hun REHL6 main runelevl sitch krny k lye `init` lift use krt hain Same ust trha REHL 7 ya 8 main hum targts switch krny k lye `systemctl isolate multiuser` too app multi user target main switch kr jayeen gy
or agar`systemctl isolate graphical`  to aap grphical target main switch kr jayeen gy. See screenshot..

- important 

-  `systemctl isolate multiuser` is similar to `runlevel3`

   - Yaani ye black terminal hai only

 - `systemctl isolate graphica` is similar to `runlevel 5`

   - yaani ye Grphical userbinterface hai.

REHL7and8 main single user mode(yaani runlevel 1)ka concept alag hai.

REHL7and8 main single user mode(yaani runlevel 1) main jaany k lye hmy `initramfs `file break krni pdti hai. phir 1 shell milta hai. is k baary main hum aagy padheen gy ki is command kia hai `initramfs` kia hai.
 - Break ki command
 `BREAK initramfs` hai.

   - iska proper concept hum aagy deekhen gai 

#### Abhi hum sirf ye deekhen gy k 7&8 main singleuser mode k passwor kesy change kr skty hain...


### `fdisk`

OS main harddisk ki storage kam q show hoti hsi?

`Ans:`

Hard disk kam is liye show hoti hai
kyunki company aur OS dono storage ko alag tarah se ginte hain.

Company kehta hai: 1 GB = 1000 MB

Lekin OS kehta hai: 1 GB = 1024 MB

Is liye jab OS ginta hai to size thoda kam nikalta hai.


![alt text](image-43.png)

cylinder ki koi permanet value ni hooti. disk ke physical design par depend karta hai.

amooman GBs Harddisk main 1 cylinder `8mb` ka hoota hai.

 or agar 500 MBs ki hardisk hai too cylinder ki value 1 Mb hoo gi.

**Screenshoot k mutabiq..**

`16GB` harddisk main `1958` cylinders hooty hain agar 1 cylinder `8Mb` k hoo too.

`1958*8=1566MB` Cylinders ko Mb main

1566/1024=16 or 15 Gbs approxly

agar 16Gb ki harddisk hai or main nee 24MB ki 1 partation bnani hai too 8Mbs k hisaab sy 3 cylinders user hoon gee.

Harddisk and partaion create krna.

- `Harddisk create krna`

  - machine ko sutdown`shutdown -f now` krain.

  - Settings main storage open kr k `SATA` par add ko click kr k create krain.

  - storage select krain k kitni chaye or choose kr lain.

  - ab maechine start karin aap ki new harddisk create ho gai hai .

  - check krny k lyee `ls -l /dev/sd*` command run krain. latest name sy aap ki new harddisk show ho gi.

- ` Harddisk main partaion create krna`
  - partation create krny k lye `fdisk /dev/HDD ka name` likh kr command run krain.
  - file main app ko deatils dikheen gi `m for help`sy.
  - `n` sy mew partation 
  - `p` sy partation ki deatils print krain etc.
  - `n` likh kr run karin or aagy required details dain jitni storage ki aap ny paration bnanai hai, name number kia rkhna hai,kis cylinder sy start krna hai etc.
  -  method complete kr k`p` sy aap partation ki detials check kr skty hain.
   -  `q` quit kr k aap file sy bahir aa skty hain.
  ##### `fdisk sy sirf partation create kr skty hain or delete kr skty hain.`
  #### ` 1 hardisk main sirf 4 partation bna skty hain`

  #### `agar 4 sy zayad bnana hai too aap 4th aprtation extended bnaye is sy error nhi aye gaa agar already 4 primary partation hain to phir extended bhi bnaye ga aap ko 4th paration extended bnana ho ga. `
  #### ` extended partation k andar bhi aap partation bhi bna skty hain or cylinders hold bhi kr skty hain or baad main us cylinders par bhi  aprtaion bna skty hain.`![alt text](image-44.png)
___
  ## 11.Partitions Logic Concept-FSTab

#### `jb hum partations bnaaty hain too fdisk un ki entry or deatils partation table main main likh deta  hai k paration kitna storage rkhti hai,kitny cilynders par mustmil hai, kis cylinder sy start ho rhi hai or kis cylinder pee end ho rhi hai etc.`

- `Partation Table`
  
  `Partition Table ek aisa structure hai jo hard disk  ke start mein hota hai. Yeh table operating system ko batata hai ke aap ki disk par partitions kaise arrange hain.`

**Yeh basically ek "map" ya "index" ki tarah hai.**
- Yeh Kyon Zaroori Hai?

  - Disk par har partition ki jagah (location) track karne ke liye.

  - Yeh define karne ke liye ke konsa partition "bootable" hai.

  - Operating system ko yeh batane ke liye ke usay data kahan read/write karna hai.
  
  Jb hum partation create kr k `w` save kr qiut `q` krt hain to partation table main save ho jT hai k partation create ho gai hai.

  Isy trha ye process Krenal table pai bhi chalta hai k Harddisk main 1 or partation create ki gai jis sy OS partation access krny ki info hasil krta hai.

- Is k lye command hai `partx -a` 
- `REHL 6 main partx -a`
  - Yeh kisi specific disk ke sare new partitions ko kernel ke knowledge mein add kar deti hai.
  - ye sirf new partations ki detials update krti ahi.
- `REHL 7 main partprobe`
  
  - partprobe ek aisi command hai jo kernel ko forcefully batati hai ke disk ke partitions table mein change hua hai.
  - Ye naya or puana sari deatails update krtihai.
  
  
- ye command partation table sy deatils lee kr kernal table ko update krti hai or RAM main save ho jata hai .
- System ko reboot kye bgair kernal table ko update krny k lye use hoti hai
- agar OS ko reboot kr dya jaye to kernal table khud hi update hoo k partations ki detail load kr leta hai.

![alt text](image-45.png)
- ` agar partation table main details update hoo gi to kernal table main update hoo`
- Make sure k partatiom table main `w` likh kr partation ki deatls update kr dain.

- `Formating`
  
- `Formatting ek aisa process hai jis mein aap kisi partition ya drive ko prepare karte hain data store karne ke liye.`

- `For example:` Aap ek nayi khali copy lete hain. Uss copy par lines (guides) khenchte hain taake aap baad mein acchi tarah likh saken.

File System  create krna bhi formating hai.

Command:` mkfs.ext4 /dev/sdb1`



  - `Partitioning drive ko hisson mein taqseem karta hai` jaise ghar ke kamre banana.

  - `Formatting har hissey ko usable banata hai `jaise har kamrey mein almariyan aur table lagna.
  
 
  `FileSystems`
  
Linux version k issab sy filesystem bnaye gyee hain.

- REHL v4 k lye `ext2`
- REHL v5 k lye `ext3`

jeesa k neechy pic main hai.
 
![alt text](image-46.png)

Par ye baat zroori nhi k jis REHL Version k lye file system ka version bnaya gya hai wo sirf wo hi use kr sktaa hai. har version har filesystem ka version use kr skta hai . Bs us k packages install krny hoo gy.

- ` Mounting`

Defination

`Kisi bhi storage device ke partition ko system ki directory tree ke kisi khaas folder k saath attach krna, taa k partition ki files aur folders tak user ki rsaai ho sake.`
Mounting make sure krti he ke kis physical device ka data kis folder ke andar dikhna chahiye.

Formatting` Drive ko use karne ke qaabil banana (isme file system banta hai).`

Mounting `Us tayyar drive ko system se jorna, taake aap usme files daal aur nikal saken.`

- Maping vs Mounting:

| Point               | Mounting                                      | Mapping                                      |
| ------------------- | --------------------------------------------- | -------------------------------------------- |
| **Kya Jodte Hain?**   | Physical Device (HDD, USB)                    | Virtual/Network Resource                     |
| **Kahan Jodte Hain?** | Directory/Folder (e.g., `/mnt/`)              | Drive Letter (e.g., `Z:`) ya Virtual Path    |
| **Platform**        | Linux/UNIX mein zyada common                  | Windows mein zyada common                    |


agar hum nee kisi directory ko partation k saath mount kia hai too data partation main save hoota hai isy wjha sy directory ko unmount kr dain too data lose ni hoota.

agar doobara mount krain gee too data doobara directory main show hoony lgy ga.

agar pehli directory koo `unmount` kr dain or kisi or directory ko `mount` kr dain too same data nai directory main show hoony lgy ga.

- `fstab`

ye mount ki gai directory system k reboot hony tk hi mount rhy gi. yaani yee temporary process hai. isko permanent krny k lyee `fstab` ka concept use hota hai.

`fstab (file system table) ik boot process file hai yaani jb system boot hota hai to ye file refer hota hai.`

 is ki 6 fields hoti hain.

 ![alt text](image-47.png)

___
### 12.Partitions Task Solving-Compression Tools Redirect Topic

-  Compression Tools
  
compression Kisi cheez ko shrink krna, deflate krna,us main sy azafi hava nikaal deena hai.



Linux main ompression ek aisa process hai jisme files ya folders ko chota size mein convert kiya jata hai taki
Kam storage use ho,
Transfer fast ho,
Bandwidth bache.
### *
  *saary characters ko bulany k lye.yani `rm*.jpg` see sari photos delete ho jaye gi.

? kisi 1 character ko mukhatib kry ga .

file1.txt =` file?.txt`

#### ?

 ik character wali sab files dikhao..

`ls file?.txt`

 ` file1.txt, fileA.txt, fileX.txt`

 Do character wali files is trha deekh skty hain.
`ls pic??.jpg`

 `pic01.jpg, picAB.jpg, pic12.jpg`

![alt text](image-48.png)

#### -`File ko zip krny k lye command`

`gzip filename`
`bzip filenme`

jab hum ksis file ko zip krty hain to file ki extantion khud ba khud change hoo k `.gz ya .bz` hoo jata hai.
![alt text](image-50.png)

#### - `file ko unzip krny k lye command`

`gunzip filename`
`bunzip filename`

- zip kia hai?
  
  ye command multiple files ko compress krta hai or sb files ko 1 file main archive krta hai.


![alt text](image-51.png)

![alt text](image-52.png)
___
## 13.Archive Compression Tools
File ko compress krny ki suitability file ki halat par depend krti hai k file kis noyat ki hai. .txt hai,.png hai ya .dochai.

Isy hiassab sy file compress hoti hai simple file yani .txt .doc file see zyada compress hoti hai or .doc file .png file se zyada compress hoti hai.

`zip` ka maqsad files ko archive krna yaani multiple files ko gether krna akhatta krna or 1 single file bna dena hai.

agar compressive file ko hum `cat` sy read krain gee to file data croptted show hoo ga yaani unreadabel.
![alt text](image-53.png)

Hum is file k data koo `zcat filename` command run readable form main hasil kr skty hain agar file ko uncompress kiye bgair read krna hai.![alt text](image-54.png)

agar file `bzip` sy compress kia hai wo file `bzcat file name` sy read hoo gi. 

see   SS. 
![alt text](image-56.png)

![alt text](image-55.png)

- `*` ka usecase

agar hum `*` ko usde krain to is ka matlab hai all select yaani jis directoy main hain us main mjood saari file ko select kroo.

agar same diretory mai hain too simple `* ` use hoo ga agar kisi file main rehty hoye kisi or file k data ko select krna hee to file ka proper path de kr last py`*` use krai keesy k .. ` etc/mint/*`

jb hum file ko zip krty hain too jis file main hum sb file ko archive krty hain us file ki extamation koi bhi likh dain to file to bhi koi masla ni hoo ga of files archive hoo jaye gi.

lekin `ls -l `sy file ki list niakleen gy to file red highlighted ni hii go .

![alt text](image-57.png)

- ### TAR

Yeh aisi file hai jis mein bohat si files jamaa kar ke band kar di gayi jaati, jaise aap saamaan ek box mein pack karte hain.

- .tar.gz

- .tgz


![alt text](image-58.png)

tar sirf files ko akhata krta hai compress ni krta compress krny k lye tar k saath compressive tools `gzip` ya `bzip` use krny hooty hain.

![alt text](image-59.png)

agar in files ko axtarct krna hai to ya command use hoon gi agar `tar` k saath `.gzip` use hoi hai to is file ko `tar -zxvf filname` use hoo ga.

agar file `tar` `bzip` k saath compress or archive hoi hai too `tar -jxvf filename` extract hoo gi.

agar file ki halat maloom krni hai k compress hai ya archive+compress hai to is k lye `file filename` command use hoti hai.

### linux k backup tools.
cp  ,  rsync, cpio linux k backup tools hain 

yaani in tools sy hum data ka backup lee skty hain.

cp sy kisi file ka backup leena hoo ye commnd hai.

`cp /data/* /yasir`

yaani `data `dir k andar jo bhi files ya data hai usy `yasir`main bhi copy krdo.

`cp`tool main directory k andar agar directory hoo too ya error deta hai yaani data copy ni krta.

- `rsync` ik powerful backup tool hai .agar koi puchy k bakup k lye konsa tools use hota hai to sb pehly `rsync`.

  - ye remote sync bhi kr sktaa hai yaani other machine par bhi backup ly skta hai.
  
  - ye 1 encreamentall tool hai.
  - `command`
  ![alt text](image-60.png)
___
## 14.RSync

`rsync` is lyee powerful tools hai q k is sy 1 machine sy doosri machine main data k  backup ly skty hain.
agar same machine main backup lain to machine crash hoony ki sorat main bacup bhi katam hoo skta hai is lye is tool ka usecase bohat powerful hai.

rsync k saath compression tools 9.bzip and .gzip0  ko bhi use kia jaa skta hai.

#### Tacking Backup.

agar machine to machine backup lena hai too aap lee skty hain or agar compant aap SAN.NAS ya tape drive provide kr rhi hai to aap us main backup lt skty ahin.

![alt text](image-61.png)

- Remote copy (SSH ke zariye):

`rsync -avz /home/yasir/docs username/backup/`

  ### -a (Archive Mode)

  `Ye ek combination flag ha ye bohat si options ko enable krt hai.jaise ek folder ka excat clone bnana hoo-a wahi karta hai.`
  
  - Iska kaam hai file ka pura structure aur properties preserve karna.

    - r recursively copy karna (subfolders ke sath)

    - l  symbolic links preserve karna

    - p  permissions preserve karna

    - t  timestamps preserve karna

    - g group info preserve karna

    - o  owner preserve karna

  ### -v (Verbose)

 ` ye sirf output dekhata hai k jo file copy ki hai ya jis ka backup liya hai us ka size kitna tha,data kitna transfere hoa hai.etc`

-  -v use kiye bgair  rsync  silently kaam karta hai.
- -v, k saath aap real-time feedback hasil kr skty hain.

 ### -z Compress Data During Transfer.

 Agar aap network par file bhej rahe ho (remote system) k zryee data transfere krny sy pehle ye data ko compress kr deta hai or Destination par jaake woh data decompress hota hai taaa k bandwidth bachy aur transfer fast hoo khaas tor par slow networks par.

 `- SSH transfer ke dauran ye automatic hota hai.`

 ### --delete.
 `Ye ensure karta hai ke destination directory bilkul source ke barabar ho.yaani joo file source dir main mjood nhi hee wo destination see delte ho jaye gi. 

 `mirror image` banana yaani source se extra cheezein destination se hata di jayen.

 ### -P  Progress + Partial Transfer Resume

 - progress har file ka progress is sy daiks skty hain.

-  transfer beech main ruk jaaye (network down, etc.), to hun is process ko resume kr skty hain.

### `SSH`

`SSH (Secure Shell) ek network protocol hai jo aapko remote computer ya server se secure connection ke zariye connect hone ki ijazat deta hai.`

SSH ka kaam.

1. Remote system se securely login karna

2. REmote server par command run krna.

3. Files transfer karna (yani rsync)

4. securely Port forwarding / tunneling karna 

- `SSH`Working

  - jb kisi remote system sy connect hoty hain`ssh username ya ip` to apka system aur remote system ek encrypted connection establish karte hain.

  - password Ya SSH key pair (public/private keys)  se Authentication hoti hai.

  - agar connect ho jaye too aap remote terminal par directly commands run kar sakte ho jaise aap local system par karte ho.

  - SSH data ko encrypt karta hai taakePasswords aur commands safe rahen Koi bhi s attacker data ko read na kar sake.
  - SSH port 22 par run hota hai.

Port ek numarical gate hota hai jisse computer ke andar koi network service communicate karti hai.

Har computer ya server ke paas ek IP address hota haijaise ghar ka address.
Lekin us ghar ke andar bohot saare kamray yaani services hoti  hain jeesy web server, SSH, email server, etc.
Ye kamray alag ports ke zariye identify hote hain.



 #### `SSH or har network service ka port number change kiya ja sakta hai`

#### `Q.kia hum ports ko change kr skty hain?`

#### Ans:- `g han hum ports ko change kr skty hain.`

 | Service                          | byDefault Port | Example of Custom Port |
| :------------------------------- | :----------- | :--------------------- |
| **SSH**                          | 22           | 44, 2222               |
| **HTTP (Web)**                   | 80           | 8080                   |
| **HTTPS (Secure Web)**           | 443          | 8443                   |

#### what is`stat` commmand:-

`stat command ka kaam hota hai file ya directory ke detailed information dikhanajaise size, permissions, owner, timestamps, inode number, or links vgera.`

- `stat filename`

rsync source k modify time or destination k modify time ko compare rkhta hai yaani same rkhta hai. agar source k modify time change ho ga to destination ka m-time bhi change ho jaye ga.bashart k aap rsync kr k doobara update krain too.
___

### 15.Lun Scanning Disk Scanning Logical-Extended Partition_1

What is LUN?

`LUN ka matlab hota hai Logical Unit Number.
Yeh storage system jaise SAN (Storage Area Network) ka logical partition hota hai.`

What is LUN scanning?

`LUN Scanning ka maqsad hai k server apne storage system (SAN/NAS) se updated LUN ko detect kare.`

**Jab storage admin kisi server ke liye naya LUN assign karta hai,to server ko wo LUN automatically nahi dikhta.
Server ko scan karna padta hai taake wo naya LUN detect aur use kar sake.**

jb hum LUN scanning k lye commandecho ` "- - -" > /sys/class/scsi_host/host0/scan` run krty hain too system main mjood HBA card SAN main mjodd HBA card sy wired connection bnata hai or OS ko inform krt hai k naya LUN assign ho gaya hai to tumhe `lsblk`ya `fdisk -l` me nayi disk dikhti hai.

What is HBA card?

- HBA ka matlab hota hai Host Bus Adapter.
  
  Yeh ek hardware card hota hai jo server ko SAN storage se connect karta hai.Jab hum LUN Scanning naye LUN detect karty hain to wo scan HBA card ke through hota hai.
  ![alt text](image-63.png)

  linux server mian jo LUN ko control krta hai usy `initiator` kehty hain. ye HBA card k through ficer conection sy SAN ko command krta hai .

  SAN ko hum `target` kehty hain . or SAN k anadar jo dsiks ko control krta hai us ko `SCSI controller` kehty hain. ye disks ko control or manage krt hai.

  SAN ki disks sy jo LUNs bnaye jaaty hain un ko `LUN id` sy represent kia jata hai.

- initiator k fiber connection k zryee target ko command dena, or SCSI controller ka disks ko manage kr k LUNs banana or LUNs id zryee serevr ko LUNs detect krny ka process hi LUN Scanning hai.

#### `imoprtant Point`

![alt text](image-64.png)
___
## 16.Fdisk Partitioning Cases Standards and Mounting


`extended partation koi storage ni rkhta magar is main hum jo logical partations create krty hain wo sotrage own krty hain.`

yaani hum pehly 3 primary partations create krty hain `sda ,sda1 ,sda2,` or 4rh extended partation hoyi hai` sda5`or us main lodical partations create krain `sda6,sda7 sda8` ab yhaan par 9 partation create hochuki hain lakin sirf 8 partations storage own krti hain .`sda5` yaani extend partation koi storage ni gheerti ye sirf area provide krti hai.

`Q:-agar hum first partation primary bnaye to second wali extend bna skty hai?`

**g han bna skty hain .**

`Q:- kia extend partation k baad primary paration bna skty hain?`

**g hum extend partation k baad 2 oor primary partations bna skty hain.**

`Q:_ kia extend partation ka driver hota hai? ` 

**Nahi, extended partition ka koi driver nahi hota.**

`Q:_ extend partation kia hai?`

**Ek hard disk sirf 4 primary partitions bana sakti hai.Lekin agar hume 4 se zyada chahiyein, to hum ek extended partition banate hain yeh khud data store nahi karti, bas container hoti hai.Uske andar hum logical partitions banate hain jahan actual data hota hai.**

`Q:_Primary partation kai hai?`

**Pimary partation Real usable partition hoti hai jo data store rk skti hai or bootable bhi bnai ja skti hai.**

***Zyada se zyada 4 primary partitions ek disk par ho sakti hain.***

`Q:_ logical partation kia hoti hai?`

***Veesy to sb partation logical hi hoti hai lakin yhan logical partation sy muraaad wo partation hai jo extended partation k andar create hoti hai or data srore kr skti hai.***

`Hum 1 extended partation main 63 logical partation create kr skty hain.`

![alt text](image-64.png)

`Q:- Kia har logical partation ka apna driver hota hai?`

**Har logical partition ka apna driver nahi hota.Sab logical partitions ek hi disk driver share karte hain.**

`Q:_Kia har primary partation ka pna driver hota hai?`

***har OS ek hard disk k lye single driver assign krt hai . yaani `/dev/sda`Us disk ke andar jitni bhi primary partitions hain (/dev/sda1, /dev/sda2, /dev/sda3,),sab usi driver ke zariye access hoti hain.***

`Q:_partations ko (/dev/sda1, /dev/sda2, /dev/sda3,) ye is trha name q dye jaaty hain jb k dirver to same hi use krty hain?`

**driver same hota hai, Lekin OS ko har partition tak access karne ke liye alag path chahiye hota hai.Is liye Linux har partition ko unique name deta hai — /dev/sda1, /dev/sda2, etc.**

#### `Ye mounting process k lye bhi zroori hoa hai.`

`Q:_What is Partation Tbale?`

***Partition Table ek map  hai jo disk ke andar har partition ka location aur size batata hai.**

##### `Partation Table k kaam..`

1. Ye harddisk main partations ki iformation store krt hai.

2. Ye jb system boot hota to Operating System ko Guide Karta hai k harddisk main kitni partation hain or khan hain taa k OS in ko access kr skee.

3. ye New Partitions Create/Delete Karne Mein Madad krta hai

#### `.Types `

Partatoin table ki 2 types hoti hain:

1. msdos/MBR (Master Boot Record)

2. GPT (GUID partaion table )
  
  - MBR purany OS main hota hai jis k zryee 1 hard disk main sirf 4 primary partation bna skta hai.
- `GPT ` Ye table type new OS main aati hai . or is k zryee hum 1 Hardisk main 128 primary partaion bna skty hain lakin harddisk ki storage 2TB se zyada hoo.

jb partations create ho jaye `w` run kr k partation table ko update kr dya jata hai.

is k baad  hum `partx `command run kr k partation ko kernal k knowledge main laaty hai taa k system boot hony par OS partaion ko access kr skee.

kernal k saath attach krny k baad partations main `mkfs` command k zryee filesystem bnaya jata hai.is amal ko formatig kehty hain.

filesystem jb ban jata hai to file ko kisi directory k saath attach kr dya jata hai taa k partation main mjood data read,write hoo skee is amal ko mounting kehty hain.
___
## 17.FSCK-Repairing the HD

Jab hum system start krty hain to OS storage yani harddisk sy RAM main load hoo jata hai.

`Q:_`kia reason hau OS k data RAM main load ho jata hai? 

OS ka data RAM main is liye load hota hai taake system fast chale

`DetailS`

Speed:

Hard disk slow storage hoti hai.or RAM  bahut fast hoti hai.Is liye OS apna important data (jaise kernel, drivers, aur frequently used files) RAM main load karta hai taake CPU unhe jaldi access kar sake.

Execution ke liye zaroori hota Jab koi program ya OS function run hota hai, CPU sirf RAM se data read kar sakta hai — direct HDD se nahi.
Is liye OS apna data pehle RAM main load karta hai, phir CPU usay execute karta hai.

RAM main data hone se OS ek saath multiple tasks handle kar sakta hai.

Harddisk aik mechanical device hai jb k RAM electronic chip hoti hai.

CPU sirf RAM se direct data read/write kar sakta hai.

##### `RAM kia hia?`

`RAM (Random Access Memory) ek temporary memory hoti hai jo computer ke running data aur programs ko fast access ke liye store karti hai.`

Lekin kuch tasks or commands esi bhi hoti hain jin ko sirf RAM execute ni kr skti un k lye HDD kaam krti hai.

`rm -rf /*` command ko HDD hi execute krti hain q k ye pura OS delete krny ki command hai or is main HDD hi amal pera hoti hai q k overall data ro HDD main hi hota hai or aap us ko delet krny ja rhee hain.isy trha koi file or directory bnana bhi is case ko follow kry ga.

##### Q:- `.ext2,.ext3.ext4,.xfs in sb main kia diference hai?`

| Feature | EXT2 | EXT3 | EXT4 | XFS |
|----------|-------|-------|-------|------|
| **Journaling** | non | hota hai| hota hai |  Advanced |
| **Max File Size** | 2 TB | 2 TB | Up to 16 TB | Up to 8 Exabytes |
| **Max Partition Size** | 32 TB | 32 TB | 1 Exabyte | 8 EB |
| **Performance** | Slow (no journaling) | Medium | Fast average | Very Fast |
| **Snapshot** | no |No|can not take snapshot |  Can take snapshots |

EXT3 ek directory ke andar maximum 32,000 subdirectories (folders) tak handle kar sakta hai.

EXT4 ek directory ke andar 64,000 subdirectories tak support karta hai — yani double capacity.

#### Q:-`Journaling kia hota hai?`

Journaling  file system me esa feature haijo system crash ya power failure ke baad data loss se bachati hai.

` jb hum partation ko kisi directory sy mount krty hain to actually us partation ka file system RAM main load ho jata hai or jb df -f command run krty hain too hum ko output RAM sy hi ata hai or dikh rha hota hai ki partatiom ksi directory k saath mount hoi hai.
![alt text](image-66.png)

ye process temporary hai agar is ko persist/permanent krna hai to is ki entry `/cte/fstab` k andar krni hoo gi.

`vi /etc/fstab`

jb hum partation ki entry /etc/fatab main kr dety hain to `mount -a` ki madad sy hum ummount partation ko mount bhi kr skty hain jin ki enrty fstab main hoi hoo.

ye process lazim hai agar aap ne ko bhi enrty galat ki to machine crash hoo skti hai or reboot ni ho gai is lye har bar `mount -a ` command run krain jb bhi kisi partation ki entry `/etc/fstab` min krain.

### `FSCK`

`fsck ek Linux tool hai jo file system errors detect aur repair karta hai,taake data corruption na ho aur system stable rahe.`

gar check krna ho k hmari partation main koi badblocks hain yaani (errors, missing inodes, broken links,) hain to `badblocks -v /dev/sdd1` run krian gee.

Data main kbhi kisi qisam ka corruption ni hota balky filesystem main errors, missing inodes, aaty hain jis ki wjha sy data access no hoo pata.

![alt text](image-67.png)

Pehly badblocks check kiyee jaaty hain. Pic main 0 badblocks dikhaa rhaa hai.

Neechy filesystem repair krny ki command run ki gai hai. ye command `fsck` ya `e2fsck` hoti hai. `e2fsck `updated tool hai.

`error` a rha hai k partation mounted hai yaani agar mounted partation ko repair kia jaaye to ye error deta hai or precess ni hota.

![alt text](image-68.png)

pehly partation ko unmount kia jata hai.

phir `fsck ` tool ko istemal krty hoyee partation ko clean kia jata hai.
 
 Now pic main deekha ja skta hai k file clean ho gai hai.

 aik or command use hoti hai ji filesystem main mjood errors ko detect krti hai or k ensure karta hai ke har detected problem bina rukhe repair ho jaye.

 #### Command `e2fsck -yc /dev/sdb1`

is command do flags use hoty hain.
`-y,-c`

`-c` ke through bad sectors detect karta hai.

`-y` ensure karta hai ke har detected problem bina rukhe repair ho jaye.
![alt text](image-69.png)

___

## 18.File system Check Repair

Filesystem check and repair krny k lye k lye zrooroi hai k aap ki partation kisi directory sy mount na ho.

agar mount hai to sb sy pehly unmount krian or phir `fsck` ya `e2fsck` sy filesystem repair krain.

agar yhan par hum ko `/` ka filesystem repair krna hoo to `/ root` ko directly unmount nhi krin gy Q k all process running in `/root`.

`/root` ko hum rescue mode main jaa kr unmount kr skty hain taa k process na rukny payen.

`fsck` ya `e2fsck` k zryee filesystem repair krny k dooran data lose n hota jb k filesystem ki indexing change hoo jaati hai.

**Manual**

`e2fsck & fsck` manual reapiring tools hian. is process k duraan aap ko bohat jagha par confirmation deni hoti jo k `yes` `no` ki sorat main aap sy puchta hai.

**Auto Repairing**

`e2fsck -y & fsck -y`

agar dono commands main hum `-y` ka use krain to aap ki required confirmations auto yaani khud ba khud hi dee ga . aap ko baar baar `yes` or `no` krny ki zrorat ni peesh aye gi.

**Auto reparing with report**

`e2fsck -yc`

agar aap `-yc` dono flags ka use krty hain to ye aap ko filesystem ki saari report bhi fraham krta hai.k kia kia cheez urepair ho chuki hai.

#### `Hum FSCK Q krty hain?`

Harddisk ki partation main errors,badblocks aany par harddisk proper work ni kti jis wajah sy hum `fsck` y `e2fsck` k zryee is ko clean krty hain.

#### `ye badblocks kis wajah sy aty hain?`

System ko unclean shutdown krny ki wajha sy yaani machine py kam kry proper band kye bgair systemko shutdown kr dene .

agar aap chahty hain k system boot hony k duran hi aap ki partation ko check kia jaye k clean hai nhi or agar koi error ya badblocks hain un ko remove kr k filesystem repair kr dy too is k aap ko `/etc/fstab` main entry krni hoti hai.

ye enrty fstab ki 6th filed py hoti hai agar whan app `0` likh doo is ka matlab hai k aap nhi chahty k booting k duraan aap ki harddisk ko check and repair kia jaye .

agar waha aap `1` likh dain aap ijazat de rhy hain k sirf `/ root`  partation ka booting k duran filesystems check and repair kye jaye.

agar waha aap `2` likh dain aap ijazat de rhy hain  k booting k duran all aprtations ka filesystems check and repair kye jaye.

### ye entries fstab ki last wali yani 6th field main hoti hain.


### `fstab ki fields .`

![alt text](image-70.png)

#### 1 command ka output doosri command main dena.

yaani hun `/etc` directory main hai or `ls` command sy hum ye check krty hain k is mai ktny files & folders hain.

to agar hmy count krna ho k kitny files and folders hain to ye command use hoti hai.
`wc -l`

agar hum is command ko simply run kry gy to koi output ni de gi .

agar hum `ls | wc -l ` command run krain ge to ye `ls ` k output `|` k zryee `wc -l` main bheej dee ga or `wc -l` is ka out put numbers main de gi k kitny files and folders hain`/etc` directory main.


#### less command 

agar hum `ls /etc/*` run krain gy to is ka ouput kafi long term ho ga agar is ko hum sigle line scroling main hasil krna hai to `\` k saath `less` command use kr k single line scroling shape main hasil kr skty hain.

`ls /etc/* | less`

#### more command 

gar hum `ls /home/*` run krain gy to is ka ouput kafi long term ho ga agar is ko hum page wise hasil krna hai to `\` k saath `more` command use kr k page wise hasil kr skty hain.

`ls /home/* | more`
___

## 19.Grep find locate fstab process daemons

Filesystem ki 4th filed mian 7 kisam sy option hi hain

`auto, rw, dev, async, suid, exec, nouser`


| **Option** | **Description** |
|-------------|-----------------|
| **auto** | Partition automatically boot time par mount hoti hai. |
| **rw** | Read aur Write dono permission deta hai. |
| **dev** | Device files ko use karne ki permission rkhta  hai. |
| **async** | Data asynchronously likha jata hai jis sy performance better hoti hai. |
| **suid** | SUID/SGID bits enable rehti hain. |
| **exec** | Executable files run karne ki permission deta hai. |
| **nouser** | Sirf root user mount/unmount kar sakta hai. |


![alt text](image-71.png)

Agar 4th filed main nouser ki permission likh di jate to koi bhi user partation mount ni kr skta siway root user k.

Agar 4th filed main default ilkha rhee to aap us k aagy jo bhi permission add krain gy system default option ko skip kr k ap ki ad ki gai permission ko priority dee ga or use kry ga.

#### `Process & Deamons`

jab koi program ya command execute .ho rahi hoti hai to wo process ban jaati hai

Process hamesha RAM  mein run hota hai.

##### `open file`

Jab koi program ya process kisi file ko use kar raha hota hai or file RAM mian load hoti hai to wo file `open file` kehlati hai.


check krna ho k hmaari konsi file open file hai 
`lsof` command use hoti ai.

agar in ko count krna ho to hum ne phli bhi 1 comman ka ouput count kia hai . yaani `wc -l` command use krain lekin `|pipe` k zryee if command `lsof` ka output `wc -l `main lee gy.

- `lsof | wc -l`


### `grep ` command

`Full form.`

`grep = Global Regular Expression Print`

  `Defination`

  grep is a Linux command-line tool jo text ya files me search karne ke liye use hoti hai.

- example

`grep root /etc/passwd`

Ye command `/etc/passwd file` ke andar `root` word search karegiaur wo lines show karegi jahan ye word milta hai.

#### is command main flags ka bohat eham kirdar hota hai.

`-i`agar command k saath ye `-i` use krain to command ki case senisitivity khatam ho jaye gi yani jo word search kia ho ga wo big or small lettes dono main hi mil jaye ga.

`grep -i "host" /etc/passwd`


| Option | Explanation | Example |
|:-------|:-------------|:--------|
| `-i` | Case-insensitive search | `grep -i "root" /etc/passwd` |
| `-n` | Line number show kare | `grep -n "bash" /etc/passwd` |



`ls /etc/* | grep -i host | wc -l`


Ye command /etc folder ke andar un sab files/folders ko count karegi
jinke naam me “host” word aata hai (case-insensitive).


#### `find` command

find ek powerful searching command hai jo files aur directories ko specific conditions ke basis par search karta hai (jaise name, size, date, permission, owner, etc).

is command sy search ki gai files and folders ko delete bhi kr skty hain ,permission bhi change ke skty hainetc.

- `find /home/ -iname yasir.txt`

Ye command /home directory ke andaraisi file ko search karegi jiska naam yasir.txt ho chahe wo uppercase ya lowercase letters me likhi hoi.

## 20.Process-daemons-PerformaceMonitoring-P1

pehchy hum ne prha hai `losf   command kia krti hai.

proces kia hota hai.

open file kia hai .

ab hum process and daemons k baary main more prhen gy...

- Each process have own `pid` yaani har har process anpi aik `pid (Process id) rkhta hai jis k zryee system process ko pehchcnta hai.
- `erendom`assin and manage `pids` or 80% process
  `pids` change hoty rhty hain agar service ki restar krain ya machine ko restart krain to `pid` change ho jata hai.
  
  agar dwkhna ho k kitne process hmari machine pe chal rhe hain to command hai.

- `ps -el`

agar pages ki trha output chahye to.

- `ps -el |less`
- `ps -el  |more`

agar count krna ho k kitne proceess chal rhe hain to.

- `ps -l | wc -l`
  
  mari machine py os time 207 process chal rhee hthee.

  ![alt text](image-72.png)

Process ko kill krny yaani stop krny k lye command `kill pid`

agar pid maloom nhi hai to `grep command ` or process k name sy aap pid maloom kr skyty hain jeesy k neech pic main dekhaya gya hai.

![alt text](image-73.png)

direct name k saath process kill krny ki command

`pkill process name`

`cpu` k details check krny ki command

- `lscpu`

`usb` ki details check krny ki command 

- `lsusb`
#### `init REHL6 tk is a father of all processes or is ki `pid` kbhi change ni hoti hai.REHL 7 main system d hota hai`

- `pstree ` process ka hirarchey hota hai.
___

## 21.Process daemons PerformaceMonitoring-P2

How to check load in system?

Linux Performance Monitoring Commands

| Command | Description |
|----------|--------------|
| `top` | System processes aur CPU usage live show karta hai. |
| `htop` | `top` ka advanced version, colorful aur interactive. |
| `sar` | System activity report deta hai.|
| `iostat` | HDD load aur I/O performance check karta hai. |
| `vmstat` | Memory, swap, process aur CPU statistics deta hai. 
| `iperf` | Network bandwidth aur speed test karta hai. |
| `tcpdump` | Network packets capture aur analyze karne ke liye. |

lakin yhan hum `top` k baary main hi parheen gy.ye tmaam process jo RAM main load hoty hain un ko dikhata hai with used parts and programes ki performance k.

**![alt text](image-74.png)**

- what is load?

  - processes ka row yani queue main wait krna load kehlata hai.
![alt text](image-75.png)

agar RAM k process deekhny hon `/proc` directory main ja k deekh skty hain.it conatains navigated files that contain from RAM.

agar `top` command k alwa kisi or command sy storage yani memory check krni ho to ya command bhi use kr skty hain,

`free -m`

![alt text](image-76.png)
___
## 22.Process daemons Performance Monitoring-P3 NW Start

Hum ne pely bhi prhaa ha k kisi process ko kesy stop krna hai or khatam krna hai.

ab yhan pr hum `pkill` and `kill` k darmyaan faraq krain gy.

- `pkill command` 

agar is command sy kisi process ko khatam krna hai to hmy `pkill` k saath precess ka name likhna hoa ga .

  command :`pkill chrome`


- `kill`
kill command main hum process k name ki bjaye us process ki id yani `pid` deety hain.

command: `kill 224`

kill command agar kam ni rkti to hum is ko firce fully kill krty hai yani flags use krty hain.

`kill -9 224`


- forcefully kill krny k lye hum `kill` k saath `-9` use kry hain.

- by default kill `-15` ko use krta hai lekin `-9` focefully kill krt hai.

![alt text](image-78.png)

- `Kill -l` sy hum kill command k signal maloom kr skty hain.

![alt text](image-79.png)

highlighted 3 signal hum aam taor par use krty hain.
#### what is `Ampersand (&)` ?

Ye kisi Command ko background mein run karne ke liye istemal hota hai.

Jab aap kisi command ke end mein `&` lagate ho, to wo process background job ban jata hai.

System usko ek job ID aur process ID (PID) deta hai.

- `  lekin system band hony kis surat main process bhi band ho jaye ga`


![alt text](image-77.png)
  - gnome terminal ny process ko bsah shell main load kia

- shell yani bash ny process ko chlaya.
 
  - agar gnome terminal ko band kr dain gy to process band ho jaye ga.

`jobs` and `fg` ye commands background process ko dekhny k lye hoti hai.

Aur agar chaho to is command k zryee usko foreground mein wapas la skty hain .

`fg %1`yahan %1 job number hai


#### what is `nohup` command?

Full form `No Hang Up`

ye command process ko out of shell chlany k lye use hoti hai.

yani agar aap terminal band kar do
ya logout bhi kar do to bhi wo command ya process band ni hota or background mein chltaa rehta hai.

`nohup "command" &`

#### Kia `nohup` k saath `&` lgana zaroori hota hai?

| Case | Command | Kya Hota Hai |
|------|----------|--------------|
|  **With `&`** | `nohup command &` | Command **background** mein chali jaati hai aur **logout ke baad bhi** chalti rehti hai.  |
|  **Without `&`** | `nohup command` | Command **foreground** mein chalegi (terminal busy rahega), lekin **logout ya terminal close hone ke baad bhi** band nahi hogi. |

#### What is fork bombing?

Is main 1 program  apne aap ko baar-baar copy krta hai isliye bahut jaldi bahut saare processes ban jaate hain or System ki memory khatam ho jaati hai aur computer hang ho jaata hai.

Command

`:(){ :|:& };:`

Ye command ek fork bomb banata hai matlab ye system main infinite processes bana deta hai CPU aur memory dono full ho jate hain system hang / crash ho jata hai. 

### what is daemon?

`Daemon ek aisa background process hota hai jo system boot hone ke baad automatically start hota hai aur continuously specific task perform karta rehta hai.`

#### Differnce Between Process an Daemons

| Feature | Process | Daemon |
|----------|----------|---------|
| **Definition** | Program jo run ho raha hai (foreground ya background dono ho sakta hai) | Special process jo background mein continuously chal kar service provide karta hai |
| **Start Hone ka Time** | User ke command dene par (manual) | System boot hone par (automatically) |
| **User Interaction** | User directly control karta hai | User se directly interact nahi karta |
| **Terminal Control** | Usually terminal se linked hota hai | Terminal se unlink hota hai (no controlling terminal) |
| **Lifetime** | Jab tak user program run kare | System shutdown tak active rehta hai |
| **Purpose** | Temporary kaam karna (e.g. file edit, copy) | Continuous service dena (e.g. SSH, web, logs) |



![alt text](image-80.png)


![alt text](image-81.png)


1: System ko static IP address do.
Ya phir
2: System ko DHCP ke zariye automatic IP lainay do.

--- Agar phir bhi kaam na karay to ---

3: vi ya koi aur text editor use karke yeh file open karo:
/etc/sysconfig/network-scripts/ifcfg-eth0
Us file mein yeh line check karo ke ONBOOT=yes hai ya nahi. Agar no hai to use yes kar do. Iska matlab hai system start hotay he network interface on ho jaye ga.

4: Network service ko restart karo yeh command de kar:
service network restart

5: Test karo ke ab routing theek hai ya nahi. Yeh command `ip r l`

6: Agar upar walay sab steps karne ke baad bhi masla hal na ho, to apni Virtual Machine (VM) ke settings mein ja kar "Network" section check karo. Wahan par "NAT" setting ko change kar ke "Bridge" kar do. Yeh VM ko apne host computer ke network directly attach kar day ga.


