# Net&Sys Assignment: Running Containers for Application Development

Group Name: **FnF** 

Team Mates:

**1. FARAH BINTI MAZLAN and 2220338**

**2. NUR FAIZAH BINTI OMAR and 2226856**



## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/



## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository



***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)***

   https://github.com/Faihyaa/FnF-NatSysProject
   
2. How many files and folders are in this repository. ***(1 mark)***

   `1 file`



## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

   <img src="./images/newcodespace.png" width="50%">
   
5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode.

   <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository.

   <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark.

    <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.



***Questions:***

1. What is default OS used to run the virtual environment for codespaces.***(1 mark)***.

   `Ubuntu`
     
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)***.

   `- 4 cores, 8 GB RAM, and 32 GB disk`

   `- 8 cores, 16 GB RAM, and 64 GB disk`
 
4. Why must we commit and sync our current work on source control? ***(1 mark)***

   `- To make sure that every modification is backed up so that it may be restored in the event of a data loss or local difficulty.`
   `- To provide everyone on the team access to the most recent versions to promote seamless integration and reduce disagreement and foster cooperation.`



## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
   ```bash
   @joeynor ➜ /workspaces/OSProject (main) $ whoami
   codespace
   ```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)***

   `/workspaces/FnF-NatSysProject`

2. Run the command **cat /etc/passwd** . ***(1 mark)***

   `bash: cat/etc/passwd: No such file or directory`
   
3. Run the command **df** . ***(1 mark)***
   ````
   Filesystem     1K-blocks     Used Available Use% Mounted on
   overlay         32847680 10380876  20772704  34% /
   tmpfs              65536        0     65536   0% /dev
   shm                65536        8     65528   1% /dev/shm
   /dev/root       30298176 24278780   6003012  81% /vscode
   /dev/sda1       46127956      108  43752272   1% /tmp
   /dev/loop3      32847680 10380876  20772704  34% /workspaces
   ````

4. Run the command **du** . ***(1 mark)***
   ````
   4       ./.git/branches
   16      ./.git/objects/1b
   8       ./.git/objects/83
   8       ./.git/objects/47
   8       ./.git/objects/71
   12      ./.git/objects/62
   8       ./.git/objects/58
   12      ./.git/objects/73
   8       ./.git/objects/a6
   8       ./.git/objects/04
   12      ./.git/objects/fd
   12      ./.git/objects/e5
   8       ./.git/objects/41
   8       ./.git/objects/7b
   8       ./.git/objects/24
   8       ./.git/objects/c6
   12      ./.git/objects/3d
   8       ./.git/objects/0b
   12      ./.git/objects/72
   12      ./.git/objects/d2
   8       ./.git/objects/15
   8       ./.git/objects/86
   12      ./.git/objects/1c
   8       ./.git/objects/eb
   8       ./.git/objects/ab
   12      ./.git/objects/ff
   12      ./.git/objects/af
   8       ./.git/objects/74
   8       ./.git/objects/96
   8       ./.git/objects/cf
   12      ./.git/objects/70
   12      ./.git/objects/6c
   8       ./.git/objects/d8
   8       ./.git/objects/91
   8       ./.git/objects/c3
   8       ./.git/objects/3a
   12      ./.git/objects/9c
   12      ./.git/objects/17
   12      ./.git/objects/2e
   12      ./.git/objects/0d
   8       ./.git/objects/52
   8       ./.git/objects/fc
   8       ./.git/objects/e7
   16      ./.git/objects/fb
   8       ./.git/objects/fa
   8       ./.git/objects/a9
   8       ./.git/objects/ca
   8       ./.git/objects/4b
   12      ./.git/objects/6e
   16      ./.git/objects/b5
   8       ./.git/objects/49
   8       ./.git/objects/60
   12      ./.git/objects/fe
   8       ./.git/objects/20
   8       ./.git/objects/f6
   12      ./.git/objects/3f
   8       ./.git/objects/a3
   8       ./.git/objects/cd
   12      ./.git/objects/f2
   8       ./.git/objects/b2
   8       ./.git/objects/93
   12      ./.git/objects/c7
   8       ./.git/objects/81
   8       ./.git/objects/e9
   8       ./.git/objects/cb
   12      ./.git/objects/64
   8       ./.git/objects/b9
   8       ./.git/objects/b6
   8       ./.git/objects/4f
   8       ./.git/objects/4a
   4       ./.git/objects/info
   12      ./.git/objects/14
   8       ./.git/objects/11
   1824    ./.git/objects/pack
   12      ./.git/objects/44
   2528    ./.git/objects
   8       ./.git/logs/refs/heads
   16      ./.git/logs/refs/remotes/origin
   20      ./.git/logs/refs/remotes
   32      ./.git/logs/refs
   40      ./.git/logs
   68      ./.git/hooks
   4       ./.git/lfs/tmp
   8       ./.git/lfs
   4       ./.git/refs/tags
   8       ./.git/refs/heads
   16      ./.git/refs/remotes/origin
   20      ./.git/refs/remotes
   36      ./.git/refs
   8       ./.git/info
   2728    ./.git
   1972    ./images
   4720    .
   ````

5. Run the command **ls** . ***(1 mark)***

   `README.md  images`
   
6. Run the command **ls -asl** . ***(1 mark)***
   ````
   total 32
   4 drwxrwxrwx+ 4 codespace root  4096 Jun 18 15:13 .
   4 drwxr-xrwx+ 5 codespace root  4096 Jun 18 15:13 ..
   4 drwxrwxrwx+ 9 codespace root  4096 Jun 18 15:25 .git
   16 -rw-rw-rw-  1 codespace root 12708 Jun 18 15:17 README.md
   4 drwxrwxrwx+ 2 codespace root  4096 Jun 18 15:13 images
   ````

7. Run the command **free -h** . ***(1 mark)***
   ````
                 total        used        free      shared  buff/cache   available
   Mem:          7.7Gi       1.4Gi       216Mi        67Mi       6.1Gi       6.0Gi
   Swap:            0B          0B          0B
   ````
 
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)***
   ````
   processor       : 0
   vendor_id       : AuthenticAMD
   cpu family      : 25
   model           : 1
   model name      : AMD EPYC 7763 64-Core Processor
   stepping        : 1
   microcode       : 0xffffffff
   cpu MHz         : 2994.390
   cache size      : 512 KB
   physical id     : 0
   siblings        : 2
   core id         : 0
   cpu cores       : 1
   apicid          : 0
   initial apicid  : 0
   fpu             : yes
   fpu_exception   : yes
   cpuid level     : 13
   wp              : yes
   flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
   bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
   bogomips        : 4890.85
   TLB size        : 2560 4K pages
   clflush size    : 64
   cache_alignment : 64
   address sizes   : 48 bits physical, 48 bits virtual
   power management:

   processor       : 1
   vendor_id       : AuthenticAMD
   cpu family      : 25
   model           : 1
   model name      : AMD EPYC 7763 64-Core Processor
   stepping        : 1
   microcode       : 0xffffffff
   cpu MHz         : 3093.116
   cache size      : 512 KB
   physical id     : 0
   siblings        : 2
   core id         : 0
   cpu cores       : 1
   apicid          : 1
   initial apicid  : 1
   fpu             : yes
   fpu_exception   : yes
   cpuid level     : 13
   wp              : yes
   flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
   bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
   bogomips        : 4890.85
   TLB size        : 2560 4K pages
   clflush size    : 64
   cache_alignment : 64
   address sizes   : 48 bits physical, 48 bits virtual
   power management:
   ````

9. Run the command **top** and type **q** to quit. ***(1 mark)***
    ````
    top - 16:26:59 up  1:21,  0 users,  load average: 0.61, 0.33, 0.17
    Tasks:  22 total,   1 running,  21 sleeping,   0 stopped,   0 zombie
    %Cpu(s):  1.8 us,  2.9 sy,  0.0 ni, 95.0 id,  0.2 wa,  0.0 hi,  0.2
    MiB Mem :   7929.6 total,    223.3 free,   1422.0 used,   6284.3 buf
    MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6124.6 ava

    PID USER       PR  NI    VIRT    RES    SHR S  %CPU  %MEM
    2735 codespa+  20   0   21.5g 337892  49920 S   1.3   4.2
    2561 codespa+  20   0 1335936 111236  45440 S   0.3   1.4
    3246 codespa+  20   0 1120444  65836  42368 S   0.3   0.8
       1 codespa+  20   0    1136    640    640 S   0.0   0.0
       7 codespa+  20   0    7236   1792   1792 S   0.0   0.0
    ````

10. Run the command **uname -a**. ***(1 mark)***
    ````
    Linux codespaces-126583 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
    ````
    
11. What is the available free memory in the system. ***(1 mark)***

    `6.0Gi`
    
12. What is the available disk space mounted on /workspace. ***(1 mark)***

    `20G`
    
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)***

    `Name: Ubuntu 22.04 LTS`

    `Version: 22.04 LTS`

    `Hardware Architecture: x86_64`
    
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)***

    `- 'ls' is used to list the contents of a directory`

    `- '-asl' is a combination of '-a', '-s', and '-l'`

    `- '-a' : List all entries including hidden files.`

    `- '-s' : Print the size of each file in blocks.`

    `- '-l' : Use a long listing format which includes detailed information such as permissions, number of links, owner, group, size, and timestamp.`
    
15. What is the TLB size of the Virtual CPU. ***(1 mark)***

    `2560 4K pages`
    
16. What is the CPU speed of the Virtual CPU. ***(1 mark)***

    `3243.078 MHz`
    
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)***

    `44690 codespa+ (13.3 %CPU)`



## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command.
   ```
   docker pull debian
   docker run --detach -it debian
   ```

2. This will run the debian container. To check if the debian container is running, type
   ```bash
   @joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
   CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
   f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
   ```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here.
   ```bash
   docker exec -i -t romantic_jackson /bin/bash
   ```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor.
   ```bash
   root@f65be1987f84:~# apt-get update
   root@f65be1987f84:~# apt-get install nano
   root@f65be1987f84:~# cd /root
   root@f65be1987f84:~# nano helloworld.txt
   ```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
   ```bash
   @joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson
   @joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
   CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
   f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson
   @joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
   ```

   `Yes, the file is still available.`
   
7. Stop the container and delete the container. What happened to your helloworld.txt?
   ```bash
   @joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson
   @joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
   CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
   f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson
   @joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
   ```

   `'helloworld.txt' is lost because the container's filesystem is deleted.`



***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)***

   `No. In a GitHub Actions workflow, every task operates in a totally separated environment to maintain uniformity and avoid side effects from one operation impacting another. The file system is also isolated, so unless specifically controlled, no data is retained between tasks.`

3. Can we run two, or three instances of debian linux? . ***(1 mark)***

   `Yes`



## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 

2. Create a file in /root on the container, the files should also appear in myroot of your host VM.
   ```bash
   @joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
   @joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
   @joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
   /workspaces/OSProject/myroot
   @joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
   ```



***Questions:***

1. Check the permission of the files created in myroot, what user and group are the files created in docker container on the host virtual machine? . ***(2 mark)***
   ````
   @Faihyaa ➜ /workspaces/FnF-NatSysProject/myroot (main) $ ls -l HiFarahFaizah.txt
   -rw-rw-rw- 1 codespace codespace 56 Jun 18 17:32 HiFarahFaizah.txt
   ````
   
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
   ```bash
   //use sudo and chown
   sudo chown -R codespace:codespace myroot
   ````

   ````
   @Faihyaa ➜ /workspaces/FnF-NatSysProject (main) $ ls -l
   total 24
   -rw-rw-rw-  1 codespace root      12708 Jun 18 15:17 README.md
   drwxrwxrwx+ 2 codespace root       4096 Jun 18 15:13 images
   drwxrwxrwx+ 3 codespace codespace  4096 Jun 18 18:07 myroot
   ````



## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
   ```bash
   ## the -p 8080:80 flag points the host port 8080 to the container port 80

   docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
   ```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

   <img src="./images/websitelink.png" width="70%">

5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below.

   <img src="./images/helloworldweb.png" width="70%">



***Questions:***

1. What is the permission of folder /usr/local/apache2/htdocs and what user and group owns the folder? . ***(2 mark)***

   `drwxr-xr-x 2 codespace codespace 4096 Jun 19 11:08 /usr/local/apache/htdocs`
   
3. What port is the apache web server running. ***(1 mark)***
   ````
   @Faihyaa ➜ /workspaces/FnF-NatSysProject/myroot (main) $ sudo netstat -tulpn | grep apache2
   tcp6       0      0 :::80                   :::*                    LISTEN      62531/apache2
   ````
   
4. What port is open for http protocol on the host machine? ***(1 mark)***
   ````
   @Faihyaa ➜ /workspaces/FnF-NatSysProject/myroot (main) $ sudo nmap -p 80 codespaces-126583
   Starting Nmap 7.80 ( https://nmap.org ) at 2024-06-19 11:23 UTC
   Nmap scan report for codespaces-126583 (127.0.0.1)
   Host is up (0.000036s latency).
   rDNS record for 127.0.0.1: localhost

   PORT   STATE SERVICE
   80/tcp open  http

   Nmap done: 1 IP address (1 host up) scanned in 0.09 seconds
   ````



## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below

   **STEP 1:**

   **Create Networks**
   ```bash
   docker network create bluenet
   docker network create rednet
   ```

   ````
   bluenet:
   @Faihyaa ➜ /workspaces/FnF-NatSysProject/myroot (main) $ docker network create bluenet
   Error response from daemon: network with name bluenet already exists

   rednet:
   @Faihyaa ➜ /workspaces/FnF-NatSysProject/myroot (main) $ docker network create rednet
   Error response from daemon: network with name rednet already exists
   ````

   
   **STEP 2: (automatically running)**

   **Create (1) Container in background called "c1" running busybox image**
   ```bash
   docker run -itd --net bluenet --name c1 busybox sh
   docker run -itd --net rednet --name c2 busybox sh
   ```

   ````
   c1:
   @Faihyaa ➜ /workspaces/FnF-NatSysProject/myroot (main) $ docker run -itd --net bluenet --name c1 busybox sh
   0b018cb546d051d0e083d690e4a3741330f2c5cbd8f1b3b699926bf87b9c089b

   c2:
   @Faihyaa ➜ /workspaces/FnF-NatSysProject/myroot (main) $ docker run -itd --net rednet --name c2 busybox sh
   8cda9310bf9e71e9d8f9be3eb8a381a8758403745999d561bffc8866fd4eb547
   ````


***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)**
````
- Busybox is a software application that offers a number of condensed Unix capabilities in a single executable file. Compact versions of several popular UNIX utilities are combined into a single compact executable, which makes it perfect for usage with embedded computers.

- When building or operating a container in Docker, users may give it a unique name by using the
--name switch.
````
   
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
````
NETWORK ID     NAME        DRIVER    SCOPE
f7b86e681cd3   bluenet     bridge    local
a64965cf0345   bridge      bridge    local
93045d6c4efe   bridgenet   bridge    local
50cbbc3ab98c   host        host      local
fe28af3f52e9   none        null      local
078275c3f4ac   rednet      bridge    local
````
    
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
````
- Gateway bluenet : 172.18.0.1

- Gateaway rednet : 172.19.0.1
````

4. What is the network address for the running container c1 and c2.
````
- IPAddress c1: 172.18.0.2

-IPAddress c2 : 172.19.0.2
````

5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***
````
- Yes, we are able to ping.

Output: 
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.061 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.079 ms
````
## Bridging two SUB Networks

1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
   ```
   docker network create bridgenet
   docker network connect bridgenet c1
   docker network connect bridgenet c2
   docker exec c1 ping c2
   ```



## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
