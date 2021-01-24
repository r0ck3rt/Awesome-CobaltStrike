# Awesome CobaltStrike ![Awesome CobaltStrike](https://img.shields.io/badge/awesome-cobaltstrike-red.svg) ![Awesome community](https://img.shields.io/badge/awesome-community-green.svg)

### 目录

- [0x00 Introduction](#0x00-introduction)
- [0x01 Articles & Videos](#0x01-articles---videos)
  * [1. 基础知识参考](#1-------)
  * [2. 破解以及定制参考](#2---------)
  * [3. 使用技巧参考](#3-------)
  * [4. CobaltStrike隐匿参考](#4-cobaltstrike----)
  * [5. CobaltStrike分析参考](#5-cobaltstrike----)
  * [6. CobaltStrike视频资料](#6-cobaltstrike----)
- [0x02 C2 Profiles](#0x02-c2-profiles)
- [0x03 BOF](#0x03-bof)
- [0x04 Aggressor Script](#0x04-aggressor-script)
- [0x05 Related Tools](#0x05-related-tools)
- [0x06 Related Resources](#0x06-related-resources)

### 0x00 Introduction
1. 第一部分是关于CobaltStrike优质文章的集合
2. 第三部分是关于新特性BOF资源的整合
3. 解决要用的时候找不到合适aggressor script或者BOF的问题
4. 如果有本repo没有涉及的优质内容，欢迎大家提交pr

### 0x01 Articles & Videos

#### 1. 基础知识参考
1. [Cobalt_Strike_wiki](https://github.com/aleenzz/Cobalt_Strike_wiki)
2. [Cobalt Strike Book](https://wbglil.gitbook.io/cobalt-strike/)
3. [CobaltStrike4.0笔记](https://github.com/Snowming04/CobaltStrike4.0_related)
4. [CobaltStrike相关网络文章集合](https://4hou.win/wordpress/?cat=306)
5. [Cobalt Strike 外部 C2 之原理篇](http://blog.leanote.com/post/snowming/50448511de58)
6. [Cobalt Strike 桌面控制问题的解决（以及屏幕截图等后渗透工具）](http://blog.leanote.com/post/snowming/32fabf2deae1)
7. [Cobalt Strike & MetaSploit 联动](http://blog.leanote.com/post/snowming/43cef4b64cbd)
8. [Cobalt-Strike-CheatSheet](https://github.com/S1ckB0y1337/Cobalt-Strike-CheatSheet)
9. [Cobalt Strike MITRE TTPs](https://github.com/MichaelKoczwara/Awesome-CobaltStrike-Defence)

#### 2. 破解以及定制参考
1. [IntelliJ-IDEA修改cobaltstrike](https://pingmaoer.github.io/2020/06/08/IntelliJ-IDEA修改cobaltstrike/)
2. [CobaltStrike二次开发环境准备](https://pingmaoer.github.io/2020/06/24/CobaltStrike二次开发环境准备/)
3. [Cobal Strike 自定义OneLiner](https://evi1cg.me/archives/Custom_Oneliner.html)
4. [通过反射DLL注入来构建后渗透模块（第一课）](https://payloads.online/archivers/2020-03-02/1)
5. [Cobalt Strike Aggressor Script （第一课）](https://payloads.online/archivers/2020-03-02/4)
6. [Cobalt Strike Aggressor Script （第二课）](https://payloads.online/archivers/2020-03-02/5)
7. [Implementing Syscalls In The Cobaltstrike Artifact Kit](https://br-sn.github.io/Implementing-Syscalls-In-The-CobaltStrike-Artifact-Kit/)
8. [Cobalt Strike 4.0 认证及修补过程](https://xz.aliyun.com/t/8557)
9. [使用ReflectiveDLLInjection武装你的CobaltStrike](https://mp.weixin.qq.com/s/-Inh6uWV9YCz0zQYfitceA)
10. [Bypass cobaltstrike beacon config scan](https://mp.weixin.qq.com/s/fhcTTWV4Ddz4h9KxHVRcnw)

#### 3. 使用技巧参考
1. [Cobalt Strike Spear Phish](https://evi1cg.me/archives/spear_phish.html)
2. [run CS in win -- teamserver.bat](https://evi1cg.me/archives/teamserver.html)
3. [Remote NTLM relaying through CS -- related to CVE_2018_8581](https://evi1cg.me/archives/Remote_NTLM_relaying_through_CS.html)
4. [Cobalt Strike Convet VPN](http://blog.leanote.com/post/snowming/82b418239c13)
5. [渗透神器CS3.14搭建使用及流量分析](https://mp.weixin.qq.com/s/DG87HFrwHf25_M2Dnfdx3g)
6. [CobaltStrike生成免杀shellcode](https://mp.weixin.qq.com/s/G1hmsDVTO2208Ymlia_ggQ)
7. [CS-notes](https://github.com/kluo84/CS-notes)--一系列CS的使用技巧笔记
8. [使用 Cobalt Strike 对 Linux 主机进行后渗透](http://blog.leanote.com/post/snowming/c34f9defe00c)
9. [Cobalt Strike Listener with Proxy](http://blog.leanote.com/post/snowming/2ec80f7823e0)
10. [Cobalt Strike Convet VPN](http://blog.leanote.com/post/snowming/82b418239c13)
11. [CS 4.0 SMB Beacon](http://blog.leanote.com/post/snowming/8b7ce0f84c03)
12. [Cobalt Strike 浏览器跳板攻击](http://blog.leanote.com/post/snowming/4e07af1cab60)
13. [Cobalt Strike 中 Bypass UAC](http://blog.leanote.com/post/snowming/b6f671477095)
14. [一起探索Cobalt Strike的ExternalC2框架](https://www.anquanke.com/post/id/103395/)
15. [深入探索Cobalt Strike的ExternalC2框架](https://xz.aliyun.com/t/2239)
16. [Cobalt Strike的特殊功能（external_C2）探究](https://www.anquanke.com/post/id/86980/)
17. [A tale of .NET assemblies, cobalt strike size constraints, and reflection](https://redteamer.tips/a-tale-of-net-assemblies-cobalt-strike-size-constraints-and-reflection/)
18. [AppDomain.AssemblyResolve](https://offensivedefence.co.uk/posts/assembly-resolve/)
19. [从webshell建立代理上线不出网的内网机器](https://mp.weixin.qq.com/s/mNCROss5pa4rkrWIIfjVfQ)
20. [在Cobalt Strike BOF中进行直接系统调用](https://mp.weixin.qq.com/s/TLyQOupzep1BN7_nbjCXeQ)
21. [Using Direct Syscalls in Cobalt Strike's Artifact Kit](https://www.youtube.com/watch?v=mZyMs2PP38w&feature=youtu.be&ab_channel=RaphaelMudge)
22. [Cobalt Strike Staging and Extracting Configuration Information](https://blog.securehat.co.uk/cobaltstrike/extracting-config-from-cobaltstrike-stager-shellcode)

#### 4. CobaltStrike隐匿参考
1. [CobaltStrike证书修改躲避流量审查](https://mp.weixin.qq.com/s/sYfvD0XQqi6BFw70_jrv5Q)
2. [CS 合法证书 + Powershell 上线](http://blog.leanote.com/post/snowming/6a724671de78)
3. [Cobalt Strike 团队服务器隐匿](http://blog.leanote.com/post/snowming/d5d2b4ba20d0)
4. [红队基础建设:隐藏你的C2 server](https://xz.aliyun.com/t/4509)
5. [Cobalt Strike HTTP C2 Redirectors with Apache mod_rewrite](https://bluescreenofjeff.com/2016-06-28-cobalt-strike-http-c2-redirectors-with-apache-mod_rewrite/)
6. [深入研究cobalt strike malleable C2配置文件](https://xz.aliyun.com/t/2796)
7. [A Brave New World: Malleable C2](http://www.harmj0y.net/blog/redteaming/a-brave-new-world-malleable-c2/)
8. [How to Write Malleable C2 Profiles for Cobalt Strike](https://bluescreenofjeff.com/2017-01-24-how-to-write-malleable-c2-profiles-for-cobalt-strike/)
9. [Randomized Malleable C2 Profiles Made Easy](https://bluescreenofjeff.com/2017-08-30-randomized-malleable-c2-profiles-made-easy/)
10. [关于CobaltStrike的Stager被扫问题](https://mp.weixin.qq.com/s/0MPM3bysJJYr5jbRnES_Vg)
11. [Beacon Stager listener 去特征](https://mp.weixin.qq.com/s/HibtLfikI_0ezcLVCRxqaA)
12. [检测与隐藏Cobaltstrike服务器](https://hosch3n.github.io/2020/12/16/%E6%A3%80%E6%B5%8B%E4%B8%8E%E9%9A%90%E8%97%8FCobaltstrike%E6%9C%8D%E5%8A%A1%E5%99%A8/)

#### 5. CobaltStrike分析参考
1. Volatility Plugin for Detecting Cobalt Strike Beacon. [blog](https://blogs.jpcert.or.jp/en/2018/08/volatility-plugin-for-detecting-cobalt-strike-beacon.html)|[Toolset](https://github.com/RomanEmelyanov/CobaltStrikeForensic)
2. [逆向分析Cobalt Strike安装后门](https://mp.weixin.qq.com/s/VHpcHzLc829hmQjrx1139A)
3. [分析cobaltstrike c2 协议](https://github.com/verctor/Cobalt_Homework)
4. Small [tool](https://github.com/Mkv4/cobaltstrike-authfile-decrypt) to decrypt a Cobalt Strike auth file
5. [Cobalt Strike 的 ExternalC2](https://xz.aliyun.com/t/6565)
6. [Detecting Cobalt Strike Default Modules via Named Pipe Analysis](https://labs.f-secure.com/blog/detecting-cobalt-strike-default-modules-via-named-pipe-analysis/)
7. [浅析CobaltStrike Beacon Staging Server扫描](https://mp.weixin.qq.com/s/WUf96myUi8F3X_eNWPRTdw)
8. [Striking Back at Retired Cobalt Strike: A look at a legacy vulnerability](https://research.nccgroup.com/2020/06/15/striking-back-at-retired-cobalt-strike-a-look-at-a-legacy-vulnerability/)
9. [Analyzing Cobalt Strike for Fun and Profit](https://www.randhome.io/blog/2020/12/20/analyzing-cobalt-strike-for-fun-and-profit/)
10. [Cobalt Strike Remote Threads detection](https://medium.com/@olafhartong/cobalt-strike-remote-threads-detection-206372d11d0f)
11. [The art and science of detecting Cobalt Strike](https://talos-intelligence-site.s3.amazonaws.com/production/document_files/files/000/095/031/original/Talos_Cobalt_Strike.pdf)
12. [A Multi-Method Approach to Identifying Rogue Cobalt Strike Servers](https://go.recordedfuture.com/hubfs/reports/cta-2019-0618.pdf)
13. [How to detect Cobalt Strike activities in memory forensics](https://www.andreafortuna.org/2020/11/22/how-to-detect-cobalt-strike-activity-in-memory-forensics/)
14. [Detecting Cobalt Strike by Fingerprinting Imageload Events](https://redhead0ntherun.medium.com/detecting-cobalt-strike-by-fingerprinting-imageload-events-6c932185d67c)
15. [The Anatomy of an APT Attack and CobaltStrike Beacon’s Encoded Configuration](https://labs.sentinelone.com/the-anatomy-of-an-apt-attack-and-cobaltstrike-beacons-encoded-configuration/)
16. [CobaltStrike - beacon.dll : Your No Ordinary MZ Header](https://tccontre.blogspot.com/2019/11/cobaltstrike-beacondll-your-not.html)
17. [GitHub-hosted malware calculates Cobalt Strike payload from Imgur pic](https://www.bleepingcomputer.com/news/security/github-hosted-malware-calculates-cobalt-strike-payload-from-imgur-pic/)
18. [Detecting Cobalt Strike beacons in NetFlow data](https://delaat.net/rp/2019-2020/p29/report.pdf)
19. [Volatility Plugin for Detecting Cobalt Strike Beacon](https://blogs.jpcert.or.jp/en/2018/08/volatility-plugin-for-detecting-cobalt-strike-beacon.html)
20. [Easily Identify Malicious Servers on the Internet with JARM](https://engineering.salesforce.com/easily-identify-malicious-servers-on-the-internet-with-jarm-e095edac525a)
21. [Cobalt Strike Beacon Analysis](https://isc.sans.edu/forums/diary/Quick+Tip+Cobalt+Strike+Beacon+Analysis/26818/)
22. [Hancitor infection with Pony, Evil Pony, Ursnif, and Cobalt Strike](https://isc.sans.edu/forums/diary/Hancitor+infection+with+Pony+Evil+Pony+Ursnif+and+Cobalt+Strike/25532/)
23. [Attackers Exploiting WebLogic Servers via CVE-2020-14882 to install Cobalt Strike](https://isc.sans.edu/forums/diary/Attackers+Exploiting+WebLogic+Servers+via+CVE202014882+to+install+Cobalt+Strike/26752/)
24. [Hiding in the Cloud: Cobalt Strike Beacon C2 using Amazon APIs](https://rhinosecuritylabs.com/aws/hiding-cloudcobalt-strike-beacon-c2-using-amazon-apis/)
25. [Identifying Cobalt Strike team servers in the wild](https://blog.fox-it.com/2019/02/26/identifying-cobalt-strike-team-servers-in-the-wild/)
26. [Multi-stage APT attack drops Cobalt Strike using Malleable C2 feature](https://blog.malwarebytes.com/threat-analysis/2020/06/multi-stage-apt-attack-drops-cobalt-strike-using-malleable-c2-feature/)
27. [Operation Cobalt Kitty](http://cdn2.hubspot.net/hubfs/3354902/Cybereason%20Labs%20Analysis%20Operation%20Cobalt%20Kitty.pdf)
28. [Detecting and Advancing In-Memory .NET Tradecraft](https://www.mdsec.co.uk/2020/06/detecting-and-advancing-in-memory-net-tradecraft/)
29. [Analysing Fileless Malware: Cobalt Strike Beacon](https://newtonpaul.com/analysing-fileless-malware-cobalt-strike-beacon/)
30. [IndigoDrop spreads via military-themed lures to deliver Cobalt Strike](https://blog.talosintelligence.com/2020/06/indigodrop-maldocs-cobalt-strike.html)
31. [Cobalt Group Returns To Kazakhstan](https://research.checkpoint.com/2019/cobalt-group-returns-to-kazakhstan/)
32. [Striking Back at Retired Cobalt Strike: A look at a legacy vulnerability](https://research.nccgroup.com/2020/06/15/striking-back-at-retired-cobalt-strike-a-look-at-a-legacy-vulnerability/)
33. [Azure Sentinel Quick-Deploy with Cyb3rWard0g’s Sentinel To-Go – Let’s Catch Cobalt Strike!](https://www.blackhillsinfosec.com/azure-sentinel-quick-deploy-with-cyb3rward0gs-sentinel-to-go-lets-catch-cobalt-strike/)
34. [Cobalt Strike stagers used by FIN6](https://malwarelab.eu/posts/fin6-cobalt-strike/)
35. [Malleable C2 Profiles and You](https://haggis-m.medium.com/malleable-c2-profiles-and-you-7c7ab43e7929)
36. [C2 Traffic patterns including Cobalt Strike](https://marcoramilli.com/2021/01/09/c2-traffic-patterns-personal-notes/)

#### 6. CobaltStrike视频资料

1. [Malleable Memory Indicators with Cobalt Strike's Beacon Payload](https://www.youtube.com/watch?v=93GyP-mEUAw&feature=emb_title)
2. [STAR Webcast: Spooky RYUKy: The Return of UNC1878](https://www.youtube.com/watch?v=BhjQ6zsCVSc)
3. [Excel 4.0 Macros Analysis - Cobalt Strike Shellcode Injection](https://www.youtube.com/watch?v=XnN_UWfHlNM)
4. [Profiling And Detecting All Things SSL With JA3](https://www.youtube.com/watch?v=oprPu7UIEuk)

### 0x02 C2 Profiles

|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  ALL   |   [Malleable-C2-Profiles](https://github.com/rsmudge/Malleable-C2-Profiles)  |   Official Malleable C2 Profiles  |  ![](https://img.shields.io/github/stars/rsmudge/Malleable-C2-Profiles)   | ![](https://img.shields.io/github/languages/top/rsmudge/Malleable-C2-Profiles) |
|  ALL   |   [Malleable-C2-Randomizer](https://github.com/bluscreenofjeff/Malleable-C2-Randomizer)  |   This script randomizes Cobalt Strike Malleable C2 profiles through the use of a metalanguage  |  ![](https://img.shields.io/github/stars/bluscreenofjeff/Malleable-C2-Randomizer)   | ![](https://img.shields.io/github/languages/top/bluscreenofjeff/Malleable-C2-Randomizer)|
|  ALL   |   [malleable-c2](https://github.com/threatexpress/malleable-c2)  | Cobalt Strike Malleable C2 Design and Reference Guide  |  ![](https://img.shields.io/github/stars/threatexpress/malleable-c2)   | ![](https://img.shields.io/github/languages/top/threatexpress/malleable-c2) |
|  ALL   |   [C2concealer](https://github.com/FortyNorthSecurity/C2concealer)  | C2concealer is a command line tool that generates randomized C2 malleable profiles for use in Cobalt Strike.  |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/C2concealer)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/C2concealer) |
|  ALL   |   [MalleableC2-Profiles](https://github.com/mhaskar/MalleableC2-Profiles)  | A collection of Cobalt Strike Malleable C2 profiles. now have Windows Updates Profile  |  ![](https://img.shields.io/github/stars/mhaskar/MalleableC2-Profiles)   | ![](https://img.shields.io/github/languages/top/mhaskar/MalleableC2-Profiles) |

### 0x03 BOF

|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  ALL   |   [BOF_Collection](https://github.com/rvrsh3ll/BOF_Collection)  |   Various Cobalt Strike BOFs  |  ![](https://img.shields.io/github/stars/rvrsh3ll/BOF_Collection)   | ![](https://img.shields.io/github/languages/top/rvrsh3ll/BOF_Collection)     |
|  ALL   |   [Situational Awareness BOF](https://github.com/trustedsec/CS-Situational-Awareness-BOF)  |   Its larger goal is providing a code example and workflow for others to begin making more BOF files. [Blog](https://www.trustedsec.com/blog/a-developers-introduction-to-beacon-object-files/)  |  ![](https://img.shields.io/github/stars/trustedsec/CS-Situational-Awareness-BOF)   | ![](https://img.shields.io/github/languages/top/trustedsec/CS-Situational-Awareness-BOF)     |
|  ALL   |   [bof_helper](https://github.com/dtmsecurity/bof_helper)  |   Beacon Object File (BOF) Creation Helper  |  ![](https://img.shields.io/github/stars/dtmsecurity/bof_helper)   | ![](https://img.shields.io/github/languages/top/dtmsecurity/bof_helper)     |
|  ALL   |   [BOF-DLL-Inject](https://github.com/tomcarver16/BOF-DLL-Inject)  |   BOF DLL Inject is a custom Beacon Object File that uses manual map DLL injection in order to migrate a dll into a process all from memory.  |  ![](https://img.shields.io/github/stars/tomcarver16/BOF-DLL-Inject)   | ![](https://img.shields.io/github/languages/top/tomcarver16/BOF-DLL-Inject)     |
|  ALL   |   [cobaltstrike_bofs](https://github.com/m57/cobaltstrike_bofs)  |   BOF spawns a process of your choice under a specified parent, and injects a provided shellcode file via QueueUserAPC().  |  ![](https://img.shields.io/github/stars/m57/cobaltstrike_bofs)   | ![](https://img.shields.io/github/languages/top/m57/cobaltstrike_bofs)     |
|  ALL   |   [BOF-RegSave](https://github.com/EncodeGroup/BOF-RegSave)  |   Beacon Object File(BOF) for CobaltStrike that will acquire the necessary privileges and dump SAM - SYSTEM - SECURITY registry keys for offline parsing and hash extraction.  |  ![](https://img.shields.io/github/stars/EncodeGroup/BOF-RegSave)   | ![](https://img.shields.io/github/languages/top/EncodeGroup/BOF-RegSave)     |
|  ALL   |   [CobaltStrike BOF](https://github.com/Yaxser/CobaltStrike-BOF)  |   DCOM Lateral Movement; WMI Lateral Movement - Win32_Process Create; WMI Lateral Movement - Event Subscription  |  ![](https://img.shields.io/github/stars/Yaxser/CobaltStrike-BOF)   | ![](https://img.shields.io/github/languages/top/Yaxser/CobaltStrike-BOF)     |
|  ALL   |   [BOFs](https://github.com/ajpc500/BOFs)  |   ETW Patching; API Function Utility; Syscalls Shellcode Injection  |  ![](https://img.shields.io/github/stars/ajpc500/BOFs)   | ![](https://img.shields.io/github/languages/top/ajpc500/BOFs)     |
|  Dev   |   [bof](https://github.com/nccgroup/nccfsas/blob/main/Tools/bof-vs-template/README.md)  |   This is a template project for building Cobalt Strike BOFs in Visual Studio.  |  ![](https://img.shields.io/github/stars/nccgroup/nccfsas)   | ![](https://img.shields.io/github/languages/top/nccgroup/nccfsas)     |
|  Dev   |   [BOF.NET](https://github.com/CCob/BOF.NET)  |   A .NET Runtime for Cobalt Strike's Beacon Object Files.  |  ![](https://img.shields.io/github/stars/CCob/BOF.NET)   | ![](https://img.shields.io/github/languages/top/CCob/BOF.NET)     |
|  Dev   |   [beacon-object-file](https://github.com/realoriginal/beacon-object-file)  |   The format, described by Mudge [here](https://youtube.com/watch?v=gfYswA_Ronw), asks that the operator construct an COFF file using a mingw-w64 compiler or the msvc compiler that holds an symbol name indicating its entrypoint, and underlying function calls.  |  ![](https://img.shields.io/github/stars/realoriginal/beacon-object-file)   | ![](https://img.shields.io/github/languages/top/realoriginal/beacon-object-file)     |
|  Dev   |   [InlineWhispers](https://github.com/outflanknl/InlineWhispers)  |   Demonstrate the ability to easily use syscalls using inline assembly in BOFs.  |  ![](https://img.shields.io/github/stars/outflanknl/InlineWhispers)   | ![](https://img.shields.io/github/languages/top/outflanknl/InlineWhispers)     |
|  Dev   |   [WdToggle](https://github.com/outflanknl/WdToggle)  |   A Proof of Concept Cobalt Strike Beacon Object File which uses direct system calls to enable WDigest credential caching and circumvent Credential Guard (if enabled).  |  ![](https://img.shields.io/github/stars/outflanknl/WdToggle)   | ![](https://img.shields.io/github/languages/top/outflanknl/WdToggle)     |
|  Dev   |   [Situational Awareness BOF](https://github.com/trustedsec/CS-Situational-Awareness-BOF)  |   This Repo intends to serve two purposes. First it provides a nice set of basic situational awareness commands implemented in BOF. This allows you to perform some checks on a host before you begin executing commands that may be more invasive.  |  ![](https://img.shields.io/github/stars/trustedsec/CS-Situational-Awareness-BOF)   | ![](https://img.shields.io/github/languages/top/trustedsec/CS-Situational-Awareness-BOF)     |
|  Auxiliary   |   [EnumCLR.c](https://gist.github.com/G0ldenGunSec/8ca0e853dd5637af2881697f8de6aecc)  |   Cobalt Strike BOF to identify processes with the CLR loaded with a goal of identifying SpawnTo / injection candidates.  |  ![](https://img.shields.io/github/stars/G0ldenGunSec)   | ![](https://img.shields.io/github/languages/top/G0ldenGunSec)     |
|  Auxiliary   |   [FindObjects-BOF](https://github.com/outflanknl/FindObjects-BOF)  |   A Cobalt Strike Beacon Object File (BOF) project which uses direct system calls to enumerate processes for specific modules or process handles.  |  ![](https://img.shields.io/github/stars/outflanknl/FindObjects-BOF)   | ![](https://img.shields.io/github/languages/top/outflanknl/FindObjects-BOF)     |
|  Auxiliary   |   [ChromeKeyDump](https://github.com/crypt0p3g/bof-collection/tree/main/ChromeKeyDump)  |   BOF implementation of Chlonium tool to dump Chrome Masterkey and download Cookie/Login Data files  |  ![](https://img.shields.io/github/stars/crypt0p3g/bof-collection)   | ![](https://img.shields.io/github/languages/top/crypt0p3g/bof-collection)     |
|  Auxiliary   |   [Sleeper](https://github.com/crypt0p3g/bof-collection/tree/main/Sleeper)  |   BOF to call the SetThreadExecutionState function to prevent host from Sleeping  |  ![](https://img.shields.io/github/stars/crypt0p3g/bof-collection)   | ![](https://img.shields.io/github/languages/top/crypt0p3g/bof-collection)     |
|  Auxiliary   |   [LSASS](https://github.com/pwn1sher/CS-BOFs/tree/main/lsass)  |   Beacon Object File to dump Lsass memory by obtaining a snapshot handle. Does MiniDumpWriteDump/NtReadVirtualMemory on SnapShot of LSASS instad of original LSASS itself hence evades some AV/EDR.  |  ![](https://img.shields.io/github/stars/pwn1sher/CS-BOFs)   | ![](https://img.shields.io/github/languages/top/pwn1sher/CS-BOFs)     |
|  Auxiliary   |   [getsystem](https://github.com/pwn1sher/CS-BOFs/tree/main/get-system)  |   get system by duplicating winlogon's token.  |  ![](https://img.shields.io/github/stars/pwn1sher/CS-BOFs)   | ![](https://img.shields.io/github/languages/top/pwn1sher/CS-BOFs)     |
|  Exploit   |   [CVE-2020-0796-BOF](https://github.com/rsmudge/CVE-2020-0796-BOF)  |   SMBGhost LPE  |  ![](https://img.shields.io/github/stars/rsmudge/CVE-2020-0796-BOF)   | ![](https://img.shields.io/github/languages/top/rsmudge/CVE-2020-0796-BOF)     |
|  Exploit   |   [ZeroLogon-BOF](https://github.com/rsmudge/ZeroLogon-BOF)  |   ZeroLogon  |  ![](https://img.shields.io/github/stars/rsmudge/ZeroLogon-BOF)   | ![](https://img.shields.io/github/languages/top/rsmudge/ZeroLogon-BOF)     |


### 0x04 Aggressor Script

|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  BypassAV   |   [BypassAV](https://github.com/hack2fun/BypassAV)  |   用于快速生成免杀的可执行文件  |  ![](https://img.shields.io/github/stars/hack2fun/BypassAV)   | ![](https://img.shields.io/github/languages/top/hack2fun/BypassAV)     |
|  BypassAV   |   [scrun](https://github.com/k8gege/scrun)  |   BypassAV ShellCode Loader (Cobaltstrike/Metasploit) [Useage](https://www.cnblogs.com/k8gege/p/11223393.html)  |  ![](https://img.shields.io/github/stars/k8gege/scrun)   | ![](https://img.shields.io/github/languages/top/k8gege/scrun)     |
|  BypassAV   |   [beacon-c2-go](https://github.com/wahyuhadi/beacon-c2-go)  |   beacon-c2-go (Cobaltstrike/Metasploit)  |  ![](https://img.shields.io/github/stars/wahyuhadi/beacon-c2-go)   | ![](https://img.shields.io/github/languages/top/wahyuhadi/beacon-c2-go)  |
|  BypassAV   |   [C--Shellcode](https://github.com/OneHone/C--Shellcode)  |   python ShellCode Loader (Cobaltstrike&Metasploit)  [Useage](http://hone.cool/2019/11/26/%E5%85%8D%E6%9D%80-C-Shellcode%E5%8A%A0%E8%BD%BD%E5%99%A8/) |  ![](https://img.shields.io/github/stars/OneHone/C--Shellcode)   | ![](https://img.shields.io/github/languages/top/OneHone/C--Shellcode)  |
|  BypassAV   |   [Doge-Loader](https://github.com/timwhitez/Doge-Loader)  |   Cobalt Strike Shellcode Loader by Golang |  ![](https://img.shields.io/github/stars/timwhitez/Doge-Loader)   | ![](https://img.shields.io/github/languages/top/timwhitez/Doge-Loader)  |
|  BypassAV   |   [CS-Loader](https://github.com/Gality369/CS-Loader)  |   CS免杀,包括python版和C版本的 |  ![](https://img.shields.io/github/stars/Gality369/CS-Loader)   | ![](https://img.shields.io/github/languages/top/Gality369/CS-Loader)  |
|  BypassAV   |   [CSSG](https://github.com/RCStep/CSSG)  |   Cobalt Strike Shellcode Generator. Generates beacon stageless shellcode with exposed exit method, additional formatting, encryption, encoding, compression, multiline output, etc |  ![](https://img.shields.io/github/stars/RCStep/CSSG)   | ![](https://img.shields.io/github/languages/top/RCStep/CSSG)  |
|  BypassUAC   |   [UAC-SilentClean](https://github.com/EncodeGroup/UAC-SilentClean)  |   This project implements a DLL planting technique to bypass UAC Always Notify and execute code in a high integrity process. |  ![](https://img.shields.io/github/stars/EncodeGroup/UAC-SilentClean)   | ![](https://img.shields.io/github/languages/top/EncodeGroup/UAC-SilentClean)  |
|  Recon   |   [red-team-scripts](https://github.com/threatexpress/red-team-scripts)  |   perform some rudimentary Windows host enumeration with Beacon built-in commands   |  ![](https://img.shields.io/github/stars/threatexpress/red-team-scripts)   | ![](https://img.shields.io/github/languages/top/threatexpress/red-team-scripts)     |
|  Recon   |   [aggressor-powerview](https://github.com/tevora-threat/aggressor-powerview)  |   All functions listed in the PowerView about page are included in this with all arguments for each function. [PowerView](https://github.com/PowerShellMafia/PowerSploit/blob/master/Recon/PowerView.ps1)   |  ![](https://img.shields.io/github/stars/tevora-threat/aggressor-powerview)   | ![](https://img.shields.io/github/languages/top/tevora-threat/aggressor-powerview)     |
|  Recon   |   [PowerView3-Aggressor](https://github.com/tevora-threat/PowerView3-Aggressor)  |   PowerView Aggressor Script for CobaltStrike [PowerView](https://github.com/PowerShellMafia/PowerSploit/blob/master/Recon/PowerView.ps1)   |  ![](https://img.shields.io/github/stars/tevora-threat/PowerView3-Aggressor)   | ![](https://img.shields.io/github/languages/top/tevora-threat/PowerView3-Aggressor)     |
|  Recon   |   [AggressorScripts](https://github.com/C0axx/AggressorScripts)  |   Sharphound-Aggressor- A user menu for the SharpHound ingestor  |  ![](https://img.shields.io/github/stars/C0axx/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/C0axx/AggressorScripts)     |
|  Recon   |   [ServerScan](https://github.com/Adminisme/ServerScan)  |   内网横向信息收集的高并发网络扫描、服务探测工具。  |  ![](https://img.shields.io/github/stars/Adminisme/ServerScan)   | ![](https://img.shields.io/github/languages/top/Adminisme/ServerScan)     |
|  Recon   |   [AggressiveProxy](https://github.com/EncodeGroup/AggressiveProxy)  |   LetMeOutSharp will try to enumerate all available proxy configurations and try to communicate with the Cobalt Strike server over HTTP(s) using the identified proxy configurations.  |  ![](https://img.shields.io/github/stars/EncodeGroup/AggressiveProxy)   | ![](https://img.shields.io/github/languages/top/EncodeGroup/AggressiveProxy)     |
|  Exploit   |   [XSS-Fishing2-CS](https://github.com/TheKingOfDuck/XSS-Fishing2-CS)  |   鱼儿在cs上线后自动收杆 / Automatically stop fishing in javascript after the fish is hooked   |  ![](https://img.shields.io/github/stars/TheKingOfDuck/XSS-Fishing2-CS)   | ![](https://img.shields.io/github/languages/top/TheKingOfDuck/XSS-Fishing2-CS)     |
|  Exploit   |   [XSS-Phishing](https://github.com/timwhitez/XSS-Phishing)  |   xss钓鱼，cna插件配合php后端收杆   |  ![](https://img.shields.io/github/stars/timwhitez/XSS-Phishing)   | ![](https://img.shields.io/github/languages/top/timwhitez/XSS-Phishing)     |
|  Exploit   |   [custom_payload_generator](https://github.com/offsecginger/AggressorScripts)  |   CobaltStrike3.0+ --> creates various payloads for Cobalt Strike's Beacon. Current payload formats   |  ![](https://img.shields.io/github/stars/offsecginger/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/offsecginger/AggressorScripts)     |
|  Exploit   |   [CrossC2](https://github.com/gloxec/CrossC2)  |   CrossC2 framework - Generator CobaltStrike's cross-platform beacon   |  ![](https://img.shields.io/github/stars/gloxec/CrossC2)   | ![](https://img.shields.io/github/languages/top/gloxec/CrossC2)     |
|  Exploit   |   [GECC](https://github.com/Lz1y/GECC)  |   Go External C2 Client implementation for cobalt strike.   |  ![](https://img.shields.io/github/stars/Lz1y/GECC)   | ![](https://img.shields.io/github/languages/top/Lz1y/GECC)     |
|  Exploit   |   [Cobaltstrike-MS17-010](https://github.com/phink-team/Cobaltstrike-MS17-010)  |   ms17-010 exploit tool and scanner.   |  ![](https://img.shields.io/github/stars/phink-team/Cobaltstrike-MS17-010)   | ![](https://img.shields.io/github/languages/top/phink-team/Cobaltstrike-MS17-010)     |
|  Exploit   |   [AES-PowerShellCode](https://github.com/offsecginger/AES-PowerShellCode)  |   Standalone version of my AES Powershell payload for Cobalt Strike.   |  ![](https://img.shields.io/github/stars/offsecginger/AES-PowerShellCode)   | ![](https://img.shields.io/github/languages/top/offsecginger/AES-PowerShellCode)     |
|  Exploit   |   [SweetPotato_CS](https://github.com/Tycx2ry/SweetPotato_CS)  |   CobaltStrike4.x --> SweetPotato   |  ![](https://img.shields.io/github/stars/Tycx2ry/SweetPotato_CS)   | ![](https://img.shields.io/github/languages/top/Tycx2ry/SweetPotato_CS)     |
|  Exploit   |   [ElevateKit](https://github.com/rsmudge/ElevateKit)  |   privilege escalation exploits   |  ![](https://img.shields.io/github/stars/rsmudge/ElevateKit)   | ![](https://img.shields.io/github/languages/top/rsmudge/ElevateKit)     |
|  Exploit   |   [CVE-2018-4878](https://github.com/vysecurity/CVE-2018-4878)  |   CVE-2018-4878   |  ![](https://img.shields.io/github/stars/vysecurity/CVE-2018-4878)   | ![](https://img.shields.io/github/languages/top/vysecurity/CVE-2018-4878)     |
|  Exploit   |   [Aggressor-Scripts](https://github.com/RhinoSecurityLabs/Aggressor-Scripts)  |   The only current public is UACBypass, whose readme can be found inside its associated folder.   |  ![](https://img.shields.io/github/stars/RhinoSecurityLabs/Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/RhinoSecurityLabs/Aggressor-Scripts)     |
|  Exploit   |   [CVE_2020_0796_CNA](https://github.com/Rvn0xsy/CVE_2020_0796_CNA)  |   基于[ReflectiveDLLInjection](https://github.com/stephenfewer/ReflectiveDLLInjection)实现的本地提权漏洞   |  ![](https://img.shields.io/github/stars/Rvn0xsy/CVE_2020_0796_CNA)   | ![](https://img.shields.io/github/languages/top/Rvn0xsy/CVE_2020_0796_CNA)     |
|  Exploit   |   [DDEAutoCS](https://github.com/p292/DDEAutoCS)  |   setup our stage(d) Web Delivery attack   |  ![](https://img.shields.io/github/stars/p292/DDEAutoCS)   | ![](https://img.shields.io/github/languages/top/p292/DDEAutoCS)     |
|  Exploit   |   [geacon](https://github.com/darkr4y/geacon)  |   Implement CobaltStrike's Beacon in Go (can be used in Linux)   |  ![](https://img.shields.io/github/stars/darkr4y/geacon)   | ![](https://img.shields.io/github/languages/top/darkr4y/geacon)     |
|  Persistence   |   [persistence-aggressor-script](https://github.com/ZonkSec/persistence-aggressor-script)  |   persistence-aggressor-script   |  ![](https://img.shields.io/github/stars/ZonkSec/persistence-aggressor-script)   | ![](https://img.shields.io/github/languages/top/ZonkSec/persistence-aggressor-script)     |
|  Persistence   |   [Peinject_dll](https://github.com/m0ngo0se/Peinject_dll)  |   弃用winexec函数，使用shellexecute函数，程序流不在卡顿，达到真正的无感。  |  ![](https://img.shields.io/github/stars/m0ngo0se/Peinject_dll)   | ![](https://img.shields.io/github/languages/top/m0ngo0se/Peinject_dll)     |
|  Persistence   |   [TikiTorch](https://github.com/rasta-mouse/TikiTorch)  |   TikiTorch follows the same concept([CACTUSTORCH](https://github.com/vysecurity/CACTUSTORCH)) but has multiple types of process injection available, which can be specified by the user at compile time.   |  ![](https://img.shields.io/github/stars/rasta-mouse/TikiTorch)   | ![](https://img.shields.io/github/languages/top/rasta-mouse/TikiTorch)     |
|  Persistence   |   [CACTUSTORCH](https://github.com/mdsecactivebreach/CACTUSTORCH)  |   A JavaScript and VBScript shellcode launcher. This will spawn a 32 bit version of the binary specified and inject shellcode into it.   |  ![](https://img.shields.io/github/stars/mdsecactivebreach/CACTUSTORCH)   | ![](https://img.shields.io/github/languages/top/mdsecactivebreach/CACTUSTORCH)     |
|  Persistence   |   [UploadAndRunFrp](https://github.com/Ch1ngg/AggressorScript-UploadAndRunFrp)  |   上传frpc并且运行frpc   |  ![](https://img.shields.io/github/stars/Ch1ngg/AggressorScript-UploadAndRunFrp)   | ![](https://img.shields.io/github/languages/top/Ch1ngg/AggressorScript-UploadAndRunFrp)     |
|  Persistence   |   [persistence-aggressor-script](https://github.com/threatexpress/persistence-aggressor-script)  |   [Persistence Aggressor Script](https://zonksec.com/blog/persistence-aggressor-script/)   |  ![](https://img.shields.io/github/stars/threatexpress/persistence-aggressor-script)   | ![](https://img.shields.io/github/languages/top/threatexpress/persistence-aggressor-script)     |
|  Persistence   |   [AggressiveGadgetToJScript](https://github.com/EncodeGroup/AggressiveGadgetToJScript)  |   Automate the generation of payloads using the GadgetToJScript technique.   |  ![](https://img.shields.io/github/stars/EncodeGroup/AggressiveGadgetToJScript)   | ![](https://img.shields.io/github/languages/top/EncodeGroup/AggressiveGadgetToJScript)     |
|  Auxiliary   |   [Cobaltstrike-atexec](https://github.com/Rvn0xsy/Cobaltstrike-atexec)  |   利用任务计划进行横向，需要与135端口、445端口进行通信    |  ![](https://img.shields.io/github/stars/Rvn0xsy/Cobaltstrike-atexec)   | ![](https://img.shields.io/github/languages/top/Rvn0xsy/Cobaltstrike-atexec)     |
|  Auxiliary   |   [Sharp-HackBrowserData](https://github.com/S3cur3Th1sSh1t/Sharp-HackBrowserData)  |   C#的HackBrowserData工具，方便在cs中直接内存加载    |  ![](https://img.shields.io/github/stars/S3cur3Th1sSh1t/Sharp-HackBrowserData)   | ![](https://img.shields.io/github/languages/top/S3cur3Th1sSh1t/Sharp-HackBrowserData)     |
|  Auxiliary   |   [SharpeningCobaltStrike](https://github.com/cube0x0/SharpeningCobaltStrike)  |   In realtime compiling of dotnet v35/v40 exe/dll binaries + obfuscation with ConfuserEx on your linux cobalt strike server.   |  ![](https://img.shields.io/github/stars/cube0x0/SharpeningCobaltStrike)   | ![](https://img.shields.io/github/languages/top/cube0x0/SharpeningCobaltStrike)     |
|  Auxiliary   |   [SharpCompile](https://github.com/SpiderLabs/SharpCompile)  |   SharpCompile is an aggressor script for Cobalt Strike which allows you to compile and execute C# in realtime.    |  ![](https://img.shields.io/github/stars/SpiderLabs/SharpCompile)   | ![](https://img.shields.io/github/languages/top/SpiderLabs/SharpCompile)     |
|  Auxiliary   |   [Quickrundown](https://github.com/icebearfriend/Quickrundown)  |   Utilizing QRD will allow an operator to quickly characterize what processes are both known and unknown on a host through the use of colors and notes about the processes displayed.     |  ![](https://img.shields.io/github/stars/icebearfriend/Quickrundown)   | ![](https://img.shields.io/github/languages/top/icebearfriend/Quickrundown)     |
|  Auxiliary   |   [Phant0m_cobaltstrike](https://github.com/p292/Phant0m_cobaltstrike)  |   This script walks thread stacks of Event Log Service process (spesific svchost.exe) and identify Event Log Threads to kill Event Log Service Threads. So the system will not be able to collect logs and at the same time the Event Log Service will appear to be running.  |  ![](https://img.shields.io/github/stars/p292/Phant0m_cobaltstrike)   | ![](https://img.shields.io/github/languages/top/p292/Phant0m_cobaltstrike)     |
|  Auxiliary   |   [NoPowerShell](https://github.com/bitsadmin/nopowershell)  |   NoPowerShell is a tool implemented in C# which supports executing PowerShell-like commands while remaining invisible to any PowerShell logging mechanisms.    |  ![](https://img.shields.io/github/stars/bitsadmin/nopowershell)   | ![](https://img.shields.io/github/languages/top/bitsadmin/nopowershell)     |
|  Auxiliary   |   [EventLogMaster](https://github.com/QAX-A-Team/EventLogMaster)  |   RDP EventLog Master  |  ![](https://img.shields.io/github/stars/QAX-A-Team/EventLogMaster)   | ![](https://img.shields.io/github/languages/top/QAX-A-Team/EventLogMaster)     |
|  Auxiliary   |   [ANGRYPUPPY](https://github.com/vysecurity/ANGRYPUPPY)  |  Bloodhound Attack Path Execution for Cobalt Strike    |  ![](https://img.shields.io/github/stars/vysecurity/ANGRYPUPPY)   | ![](https://img.shields.io/github/languages/top/vysecurity/ANGRYPUPPY)     |
|  Auxiliary   |   [CobaltStrike_Script_Wechat_Push](https://github.com/a1ices/CobaltStrike_Script_Wechat_Push)  |  上线微信提醒的插件,通过微信Server酱提醒    |  ![](https://img.shields.io/github/stars/a1ices/CobaltStrike_Script_Wechat_Push)   | ![](https://img.shields.io/github/languages/top/a1ices/CobaltStrike_Script_Wechat_Push)     |
|  Auxiliary   |   [CS-Aggressor-Scripts](https://github.com/secgroundzero/CS-Aggressor-Scripts)  |  slack and webhooks reminder    |  ![](https://img.shields.io/github/stars/secgroundzero/CS-Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/secgroundzero/CS-Aggressor-Scripts)     |
|  Auxiliary   |   [Aggressor-Scripts](https://github.com/skyleronken/Aggressor-Scripts)  |  surveying of powershell on targets (在对应的目标上检测powershell的相关信息)    |  ![](https://img.shields.io/github/stars/skyleronken/Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/skyleronken/Aggressor-Scripts)     |
|  Auxiliary   |   [cs-magik](https://github.com/tomsteele/cs-magik)  |  Implements an events channel and job queue using Redis for Cobalt Strike. |  ![](https://img.shields.io/github/stars/tomsteele/cs-magik)   | ![](https://img.shields.io/github/languages/top/tomsteele/cs-magik)     |
|  Auxiliary   |   [AggressorScripts](https://github.com/zer0yu/AggressorScripts)  | 查看进程的时候讲av进程标注为红色 |  ![](https://img.shields.io/github/stars/zer0yu/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/zer0yu/AggressorScripts)     |
|  Auxiliary   |   [Raven](https://github.com/xorrior/raven)  | CobaltStrike External C2 for Websockets |  ![](https://img.shields.io/github/stars/xorrior/raven)   | ![](https://img.shields.io/github/languages/top/xorrior/raven)     |
|  Auxiliary   |   [CobaltStrikeParser](https://github.com/Sentinel-One/CobaltStrikeParser)  | Python parser for CobaltStrike Beacon's configuration |  ![](https://img.shields.io/github/stars/Sentinel-One/CobaltStrikeParser)   | ![](https://img.shields.io/github/languages/top/Sentinel-One/CobaltStrikeParser)     |
|  Auxiliary   |   [fakelogonscreen](https://github.com/bitsadmin/fakelogonscreen)  | FakeLogonScreen is a utility to fake the Windows logon screen in order to obtain the user's password. |  ![](https://img.shields.io/github/stars/bitsadmin/fakelogonscreen)   | ![](https://img.shields.io/github/languages/top/bitsadmin/fakelogonscreen)     |
|  Auxiliary   |   [SyncDog](https://github.com/Lz1y/SyncDog)  | Make bloodhound sync with cobaltstrike. |  ![](https://img.shields.io/github/stars/Lz1y/SyncDog)   | ![](https://img.shields.io/github/languages/top/Lz1y/SyncDog)     |
|  Auxiliary   |   [360SafeBrowsergetpass](https://github.com/hayasec/360SafeBrowsergetpass)  | 一键辅助抓取360安全浏览器密码的CobaltStrike脚本，通过下载浏览器数据库、记录密钥来离线解密浏览器密码。 |  ![](https://img.shields.io/github/stars/hayasec/360SafeBrowsergetpass)   | ![](https://img.shields.io/github/languages/top/hayasec/360SafeBrowsergetpass)     |
|  Auxiliary   |   [SharpDecryptPwd](https://github.com/uknowsec/SharpDecryptPwd)  | 对密码已保存在 Windwos 系统上的部分程序进行解析,包括：Navicat,TeamViewer,FileZilla,WinSCP,Xmangager系列产品（Xshell,Xftp)。 |  ![](https://img.shields.io/github/stars/uknowsec/SharpDecryptPwd)   | ![](https://img.shields.io/github/languages/top/uknowsec/SharpDecryptPwd)     |
|  Auxiliary   |   [List-GitHubAssembly](https://github.com/mdsecactivebreach/Execute-GithubAssembly-Aggressor)  | Fetch a list of avaialble artifacts from the configured GitHub repo. |  ![](https://img.shields.io/github/stars/mdsecactivebreach/Execute-GithubAssembly-Aggressor)   | ![](https://img.shields.io/github/languages/top/mdsecactivebreach/Execute-GithubAssembly-Aggressor)     |
|  Synthesis   |   [Erebus](https://github.com/DeEpinGh0st/Erebus)  |   CobaltStrike4.x --> Erebus CobaltStrike后渗透测试插件   |  ![](https://img.shields.io/github/stars/DeEpinGh0st/Erebus)   | ![](https://img.shields.io/github/languages/top/DeEpinGh0st/Erebus)     |
|  Synthesis   |   [Cobalt-Strike-Aggressor-Scripts](https://github.com/timwhitez/Cobalt-Strike-Aggressor-Scripts)  |   CobaltStrike后渗透测试插件集合 [Usage](https://github.com/timwhitez/Cobalt-Strike-Aggressor-Scripts/wiki/Usage)   |  ![](https://img.shields.io/github/stars/timwhitez/Cobalt-Strike-Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/timwhitez/Cobalt-Strike-Aggressor-Scripts)     |
|  Synthesis   |   [AggressorScripts](https://github.com/bluscreenofjeff/AggressorScripts)  |   Aggressor scripts for use with Cobalt Strike 3.0+   |  ![](https://img.shields.io/github/stars/bluscreenofjeff/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/bluscreenofjeff/AggressorScripts)     |
|  Synthesis   |   [RedTeamTools](https://github.com/lengjibo/RedTeamTools)  |   RedTeamTools for use with Cobalt Strike   |  ![](https://img.shields.io/github/stars/lengjibo/RedTeamTools)   | ![](https://img.shields.io/github/languages/top/lengjibo/RedTeamTools)     |
|  Synthesis   |   [cobalt-arsenal](https://github.com/mgeeky/cobalt-arsenal)  |Aggressor Scripts for Cobalt Strike 4.0+   |  ![](https://img.shields.io/github/stars/mgeeky/cobalt-arsenal)   | ![](https://img.shields.io/github/languages/top/mgeeky/cobalt-arsenal)     |
|  Synthesis   |   [MoveKit](https://github.com/0xthirteen/MoveKit)  |The aggressor script handles payload creation by reading the template files for a specific execution type. [intro](https://www.4hou.com/posts/jO1y)   |  ![](https://img.shields.io/github/stars/0xthirteen/MoveKit)   | ![](https://img.shields.io/github/languages/top/0xthirteen/MoveKit)     |
|  Synthesis   |   [StayKit](https://github.com/0xthirteen/StayKit)  |The aggressor script handles payload creation by reading the template files for a specific execution type. [intro](https://www.4hou.com/posts/jO1y)   |  ![](https://img.shields.io/github/stars/0xthirteen/StayKit)   | ![](https://img.shields.io/github/languages/top/0xthirteen/StayKit)     |
|  Synthesis   |   [AggressorScripts](https://github.com/ramen0x3f/AggressorScripts)  | AggressorScripts  |  ![](https://img.shields.io/github/stars/ramen0x3f/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/ramen0x3f/AggressorScripts)     |
|  Synthesis   |   [AggressorScripts](https://github.com/harleyQu1nn/AggressorScripts)  | Collection of Aggressor scripts for Cobalt Strike 3.0+ pulled from multiple sources  |  ![](https://img.shields.io/github/stars/harleyQu1nn/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/harleyQu1nn/AggressorScripts)     |
|  Synthesis   |   [AggressorScripts](https://github.com/ramen0x3f/AggressorScripts)  | AggressorScripts  |  ![](https://img.shields.io/github/stars/ramen0x3f/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/ramen0x3f/AggressorScripts)     |
|  Synthesis   |   [Aggressor-VYSEC](https://github.com/vysecurity/Aggressor-VYSEC)  | Contains a bunch of CobaltStrike Aggressor Scripts  |  ![](https://img.shields.io/github/stars/vysecurity/Aggressor-VYSEC)   | ![](https://img.shields.io/github/languages/top/vysecurity/Aggressor-VYSEC)     |
|  Synthesis   |   [AggressorAssessor](https://github.com/FortyNorthSecurity/AggressorAssessor)  | AggressorAssessor  |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/AggressorAssessor)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/AggressorAssessor)     |
|  Synthesis   |   [AggressorAssessor](https://github.com/FortyNorthSecurity/AggressorAssessor)  | AggressorAssessor  |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/AggressorAssessor)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/AggressorAssessor)     |
|  Synthesis   |   [aggressor-scripts](https://github.com/threatexpress/aggressor-scripts)  | Collection of Cobalt Strike Aggressor Scripts  |  ![](https://img.shields.io/github/stars/threatexpress/aggressor-scripts)   | ![](https://img.shields.io/github/languages/top/threatexpress/aggressor-scripts)     |
|  Synthesis   |   [Aggressor-scripts](https://github.com/Und3rf10w/Aggressor-scripts)  | This is just a random collection of Aggressor Scripts I've written for Cobalt Strike 3.x. (其中有一个debug脚本比较好用)  |  ![](https://img.shields.io/github/stars/Und3rf10w/Aggressor-scripts)   | ![](https://img.shields.io/github/languages/top/Und3rf10w/Aggressor-scripts)     |
|  Synthesis   |   [Aggressor-Script](https://github.com/rasta-mouse/Aggressor-Script)  | Collection of Aggressor Scripts for Cobalt Strike(主要包含了提权和权限维持脚本)  |  ![](https://img.shields.io/github/stars/rasta-mouse/Aggressor-Script)   | ![](https://img.shields.io/github/languages/top/rasta-mouse/Aggressor-Script)     |
|  Synthesis   |   [Aggressor-Script](https://github.com/QAX-A-Team/CobaltStrike-Toolset)  | Aggressor Script, Kit, Malleable C2 Profiles, External C2 and so on  |  ![](https://img.shields.io/github/stars/QAX-A-Team/CobaltStrike-Toolset)   | ![](https://img.shields.io/github/languages/top/QAX-A-Team/CobaltStrike-Toolset)     |
|  Synthesis   |   [aggressor_scripts_collection](https://github.com/michalkoczwara/aggressor_scripts_collection)  | Collection of various aggressor scripts for Cobalt Strike from awesome people. Will be sure to update this repo with credit to each person.  |  ![](https://img.shields.io/github/stars/michalkoczwara/aggressor_scripts_collection)   | ![](https://img.shields.io/github/languages/top/michalkoczwara/aggressor_scripts_collection)     |
|  Synthesis   |   [CobaltStrike-ToolKit](https://github.com/killswitch-GUI/CobaltStrike-ToolKit)  | googlesearch.profile and script related to AD.  |  ![](https://img.shields.io/github/stars/killswitch-GUI/CobaltStrike-ToolKit)   | ![](https://img.shields.io/github/languages/top/killswitch-GUI/CobaltStrike-ToolKit)     |
|  Synthesis   |   [Arsenal](https://github.com/Cliov/Arsenal)  | Cobalt Strike 3.13 Arsenal Kit  |  ![](https://img.shields.io/github/stars/Cliov/Arsenal)   | ![](https://img.shields.io/github/languages/top/Cliov/Arsenal)     |
|  Synthesis   |   [cobalt-arsenal](https://github.com/mgeeky/cobalt-arsenal)  | My collection of battle-tested Aggressor Scripts for Cobalt Strike 4.0+  |  ![](https://img.shields.io/github/stars/mgeeky/cobalt-arsenal)   | ![](https://img.shields.io/github/languages/top/mgeeky/cobalt-arsenal)     |
|  Synthesis   |   [aggressor_scripts](https://github.com/001SPARTaN/aggressor_scripts)  | code execution via DCOM;the privilege escalation techniques included in ElevateKit;etc.  |  ![](https://img.shields.io/github/stars/Cliov/Arsenal)   | ![](https://img.shields.io/github/languages/top/Cliov/Arsenal)     |
|  Synthesis   |   [aggressor_scripts](https://github.com/001SPARTaN/aggressor_scripts)  | code execution via DCOM;the privilege escalation techniques included in ElevateKit;etc.  |  ![](https://img.shields.io/github/stars/001SPARTaN/aggressor_scripts)   | ![](https://img.shields.io/github/languages/top/001SPARTaN/aggressor_scripts)     |
|  Synthesis   |   [aggressor](https://github.com/gaudard/scripts/tree/master/red-team/aggressor)  | creating tunnels with netsh; changed default to bit.ly redirect to mcdonalds;using powershell to kill parent process;  |  ![](https://img.shields.io/github/stars/001SPARTaN/aggressor_scripts)   | ![](https://img.shields.io/github/languages/top/001SPARTaN/aggressor_scripts)     |
|  Synthesis   |   [CobaltStrikeCNA](https://github.com/branthale/CobaltStrikeCNA)  | A collection of scripts - from various sources - see script for more info. |  ![](https://img.shields.io/github/stars/branthale/CobaltStrikeCNA)   | ![](https://img.shields.io/github/languages/top/branthale/CobaltStrikeCNA)     |
|  Synthesis   |   [AggressorScripts](https://github.com/oldb00t/AggressorScripts)  | Highlights selected processes from the ps command in beacon;Loads various aliases into beacon;sets a few defaults for scripts to be used later.. |  ![](https://img.shields.io/github/stars/oldb00t/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/oldb00t/AggressorScripts)     |
|  Synthesis   |   [AggressorAssessor](https://github.com/FortyNorthSecurity/AggressorAssessor)  | 从C2生成到横向移动的全辅助脚本套件 |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/AggressorAssessor)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/AggressorAssessor)     |
|  Synthesis   |   [AggressorCollection](https://github.com/invokethreatguy/AggressorCollection)  | Collection of awesome Cobalt Strike Aggressor Scripts. All credit due to the authors |  ![](https://img.shields.io/github/stars/invokethreatguy/AggressorCollection)   | ![](https://img.shields.io/github/languages/top/invokethreatguy/AggressorCollection)     |
|  Synthesis   |   [Cobaltstrike-Aggressor-Scripts-Collection](https://github.com/bytecod3r/Cobaltstrike-Aggressor-Scripts-Collection)  | The collection of tested cobaltstrike aggressor scripts. |  ![](https://img.shields.io/github/stars/bytecod3r/Cobaltstrike-Aggressor-Scripts-Collection)   | ![](https://img.shields.io/github/languages/top/bytecod3r/Cobaltstrike-Aggressor-Scripts-Collection)     |
|  Synthesis   |   [aggressorScripts](https://github.com/Matrix20085/aggressorScripts)  | CobaltStrike AggressorScripts for the lazy |  ![](https://img.shields.io/github/stars/Matrix20085/aggressorScripts)   | ![](https://img.shields.io/github/languages/top/Matrix20085/aggressorScripts)     |
|  Synthesis   |   [cobalt_strike_extension_kit](https://github.com/josephkingstone/cobalt_strike_extension_kit)  | 集成了SharpHound,SharpRDP,SharpWMI等在内的各种内网工具，使用AggressorScripts构建workflow |  ![](https://img.shields.io/github/stars/josephkingstone/cobalt_strike_extension_kit)   | ![](https://img.shields.io/github/languages/top/josephkingstone/cobalt_strike_extension_kit)     |
|  Synthesis   |   [cobaltstrike](https://github.com/wafinfo/cobaltstrike)  | 具备域管理员定位、域信息收集、权限维持、内网扫描、数据库hash dump、Everything内网搜索文件等功能的插件集合 |  ![](https://img.shields.io/github/stars/wafinfo/cobaltstrike)   | ![](https://img.shields.io/github/languages/top/wafinfo/cobaltstrike)     |
|  Synthesis   |   [365CobaltStrike](https://github.com/0e0w/CobaltStrike)  | 兼容CobaltStrike4.0的插件集合 |  ![](https://img.shields.io/github/stars/0e0w/CobaltStrike)   | ![](https://img.shields.io/github/languages/top/0e0w/CobaltStrike)     |
|  Synthesis   |   [CSPlugins](https://github.com/Al1ex/CSPlugins)  | 一个对Cobaltstrike第三方插件进行收集的项目，持续更新。 |  ![](https://img.shields.io/github/stars/Al1ex/CSPlugins)   | ![](https://img.shields.io/github/languages/top/Al1ex/CSPlugins)     |
|  Synthesis   |   [CobaltStrike-xor](https://github.com/WBGlIl/CobaltStrike-file)  | third-party --> vnc_x86_dll and vnc_x64_dll |  ![](https://img.shields.io/github/stars/WBGlIl/CobaltStrike-file)   | ![](https://img.shields.io/github/languages/top/WBGlIl/CobaltStrike-file)     |
|  Synthesis   |   [Z1-AggressorScripts](https://github.com/z1un/Z1-AggressorScripts)  | 适用于Cobalt Strike 3.x & 4.x 的内网渗透插件集合 |  ![](https://img.shields.io/github/stars/z1un/Z1-AggressorScripts)   | ![](https://img.shields.io/github/languages/top/z1un/Z1-AggressorScripts)     |

### 0x05 Related Tools
|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  AntiCobaltStrike   |   [cobaltstrike_brute](https://github.com/isafe/cobaltstrike_brute)  |   Cobalt Strike Team Server Password Brute Forcer  |  ![](https://img.shields.io/github/stars/isafe/cobaltstrike_brute)   | ![](https://img.shields.io/github/languages/top/isafe/cobaltstrike_brute)     |
|  AntiCobaltStrike   |   [CobaltStrikeScan](https://github.com/Apr4h/CobaltStrikeScan)  |   Scan files or process memory for Cobalt Strike beacons and parse their configuration.  |  ![](https://img.shields.io/github/stars/Apr4h/CobaltStrikeScan)   | ![](https://img.shields.io/github/languages/top/Apr4h/CobaltStrikeScan)     |
|  AntiCobaltStrike   |   [grab_beacon_config](https://github.com/whickey-r7/grab_beacon_config)  |   Simple PoC script to scan and acquire CobaltStrike Beacon configurations.  |  ![](https://img.shields.io/github/stars/whickey-r7/grab_beacon_config)   | ![](https://img.shields.io/github/languages/top/whickey-r7/grab_beacon_config)     |
|  AntiCobaltStrike   |   [C2-JARM](https://github.com/cedowens/C2-JARM)  | 通过ssl实现所产生的JARM hash来识别不同的c2，例如CobaltStrike  |  ![](https://img.shields.io/github/stars/cedowens/C2-JARM)   | ![](https://img.shields.io/github/languages/top/cedowens/C2-JARM)     |
|  AntiCobaltStrike   |   [JARM](https://github.com/salesforce/jarm)  | JARM fingerprints scanner |  ![](https://img.shields.io/github/stars/salesforce/jarm)   | ![](https://img.shields.io/github/languages/top/salesforce/jarm)     |
|  AntiCobaltStrike   |   [DetectCobaltStomp](https://github.com/slaeryan/DetectCobaltStomp)  | A quick(and perhaps dirty!) PoC tool to detect Module Stomping as implemented by Cobalt Strike with moderate to high confidence  |  ![](https://img.shields.io/github/stars/slaeryan/DetectCobaltStomp)   | ![](https://img.shields.io/github/languages/top/slaeryan/DetectCobaltStomp)     |
|  AntiCobaltStrike   |   [cobaltstrike](https://github.com/Te-k/cobaltstrike)  |  Code and yara rules to detect and analyze Cobalt Strike   |  ![](https://img.shields.io/github/stars/Te-k/cobaltstrike)   | ![](https://img.shields.io/github/languages/top/Te-k/cobaltstrike)     |
|  AntiCobaltStrike  |   [CS_Decrypt](https://github.com/WBGlIl/CS_Decrypt)  | 解密可以帮助你理解cs beacon通信原理，但注意密钥是在本地teamserver中  |  ![](https://img.shields.io/github/stars/WBGlIl/CS_Decrypt)   | ![](https://img.shields.io/github/languages/top/WBGlIl/CS_Decrypt)     |
|  AntiCobaltStrike  |   [PyBeacon](https://github.com/nccgroup/pybeacon)  | A collection of scripts for dealing with Cobalt Strike beacons in Python Resources  |  ![](https://img.shields.io/github/stars/nccgroup/pybeacon)   | ![](https://img.shields.io/github/languages/top/nccgroup/pybeacon)     |
|  AntiCobaltStrike  |   [cobaltstrikescan](https://github.com/JPCERTCC/aa-tools/blob/master/cobaltstrikescan.py)  | Detecting CobaltStrike for Volatility  |  ![](https://img.shields.io/github/stars/JPCERTCC/aa-tools)   | ![](https://img.shields.io/github/languages/top/JPCERTCC/aa-tools)     |
|  AntiCobaltStrike  |   [CobaltStrikeForensic](https://github.com/RomanEmelyanov/CobaltStrikeForensic)  | Toolset for research malware and Cobalt Strike beacons  |  ![](https://img.shields.io/github/stars/RomanEmelyanov/CobaltStrikeForensic)   | ![](https://img.shields.io/github/languages/top/RomanEmelyanov/CobaltStrikeForensic)     |
|  Analysis  |   [Beacon](https://github.com/SecIdiot/Beacon)  | Open Source Cobalt Strike Beacon. Unreleased, in research stages  |  ![](https://img.shields.io/github/stars/SecIdiot/Beacon)   | ![](https://img.shields.io/github/languages/top/SecIdiot/Beacon)     |\
|  BypassAV   |   [Cooolis-ms](https://github.com/Rvn0xsy/Cooolis-ms)  | Cooolis-ms是一个包含了Metasploit Payload Loader、Cobalt Strike External C2 Loader、Reflective DLL injection的代码执行工具，它的定位在于能够在静态查杀上规避一些我们将要执行且含有特征的代码，帮助红队人员更方便快捷的从Web容器环境切换到C2环境进一步进行工作。 |  ![](https://img.shields.io/github/stars/Rvn0xsy/Cooolis-ms)   | ![](https://img.shields.io/github/languages/top/Rvn0xsy/Cooolis-ms)     |
|  Auxiliary   |   [CobaltPatch](https://github.com/SecIdiot/CobaltPatch)  | PyCobalt is a Python API for Cobalt Strike. |  ![](https://img.shields.io/github/stars/SecIdiot/CobaltPatch)   | ![](https://img.shields.io/github/languages/top/SecIdiot/CobaltPatch)     |
|  Auxiliary   |   [pycobalt](https://github.com/dcsync/pycobalt)  | Cobalt Strike Malleable Profile Inline Patch Template: A Position Independent Code (PIC) Code Template For Creating Shellcode That Can Be Appended In Stage / Post-Ex Blocks. Made for C Programmers. |  ![](https://img.shields.io/github/stars/dcsync/pycobalt)   | ![](https://img.shields.io/github/languages/top/dcsync/pycobalt)     |
|  Auxiliary   |   [redshell](https://github.com/Verizon/redshell)  | An interactive command prompt that executes commands through proxychains and automatically logs them on a Cobalt Strike team server. |  ![](https://img.shields.io/github/stars/Verizon/redshell)   | ![](https://img.shields.io/github/languages/top/Verizon/redshell)     |
|  Auxiliary   |   [CobaltStrikeToGhostWriter](https://github.com/hausec/CobaltStrikeToGhostWriter)  | Log converter from CS logs to a CSV in Ghostwriter's operation log format. |  ![](https://img.shields.io/github/stars/hausec/CobaltStrikeToGhostWriter)   | ![](https://img.shields.io/github/languages/top/hausec/CobaltStrikeToGhostWriter)  |
|  Auxiliary   |   [Ansible-Cobalt-Strike](https://github.com/jfmaes/Ansible-Cobalt-Strike)  | An Ansible role to install cobalt-strike on debian based architectures, let's be honest it's for kali. |  ![](https://img.shields.io/github/stars/jfmaes/Ansible-Cobalt-Strike)   | ![](https://img.shields.io/github/languages/top/jfmaes/Ansible-Cobalt-Strike)     |
|  AVBypass   |   [UrbanBishopLocal](https://github.com/slyd0g/UrbanBishopLocal)  | A port of FuzzySecurity's [UrbanBishop](https://github.com/FuzzySecurity/Sharp-Suite#urbanbishop) project for inline shellcode execution. |  ![](https://img.shields.io/github/stars/slyd0g/UrbanBishopLocal)   | ![](https://img.shields.io/github/languages/top/slyd0g/UrbanBishopLocal)     |
|  Synthesis   |   [redi](https://github.com/taherio/redi)  | Automated script for setting up CobaltStrike redirectors (nginx reverse proxy, letsencrypt) |  ![](https://img.shields.io/github/stars/taherio/redi)   | ![](https://img.shields.io/github/languages/top/taherio/redi)     |
|  Synthesis   |   [cs2modrewrite](https://github.com/threatexpress/cs2modrewrite)  | Automatically Generate Rulesets for Apache mod_rewrite or Nginx for Intelligent HTTP C2 Redirection |  ![](https://img.shields.io/github/stars/threatexpress/cs2modrewrite)   | ![](https://img.shields.io/github/languages/top/threatexpress/cs2modrewrite)     |
|  Synthesis   |   [Red-EC2](https://github.com/jfmaes/Red-EC2)  | Deploy RedTeam Specific EC2 via ansible. |  ![](https://img.shields.io/github/stars/jfmaes/Red-EC2)   | ![](https://img.shields.io/github/languages/top/jfmaes/Red-EC2)     |
|  Synthesis   |   [RedCommander](https://github.com/guidepointsecurity/RedCommander)  | Creates two Cobalt Strike C2 servers (DNS and HTTPS), with redirectors, and RedELK in Amazon AWS. Minimal setup required! Companion Blog [here](https://www.guidepointsecurity.com/2020/08/31/introducing-red-commander-a-guidepoint-security-open-source-project/) |  ![](https://img.shields.io/github/stars/guidepointsecurity/RedCommander)   | ![](https://img.shields.io/github/languages/top/guidepointsecurity/RedCommander)     |
|  Synthesis   |   [CobaltPatch](https://github.com/SecIdiot/CobaltPatch)  | Cobalt Strike Malleable Profile Inline Patch Template: A Position Independent Code (PIC) Code Template For Creating Shellcode That Can Be Appended In Stage / Post-Ex Blocks. Made for C Programmers |  ![](https://img.shields.io/github/stars/SecIdiot/CobaltPatch)   | ![](https://img.shields.io/github/languages/top/SecIdiot/CobaltPatch)     |
|  Synthesis   |   [CPLResourceRunner](https://github.com/rvrsh3ll/CPLResourceRunner)  | Run shellcode(Cobalt Strike) from resource |  ![](https://img.shields.io/github/stars/rvrsh3ll/CPLResourceRunner)   | ![](https://img.shields.io/github/languages/top/rvrsh3ll/CPLResourceRunner)     |

### 0x06 Related Resources
|  Type   |   Name  |  Description   |  Popularity   |
|:---:|:---:|:---:|:---:|
|  DATA   |   [SilasCutler JARM Scan CobaltStrike Beacon Config.json](https://pastebin.com/DzsPgH9w)  |  SilasCutler JARM Scan CobaltStrike Beacon Config  |  ![](https://img.shields.io/static/v1?label=data&message=hot&color=red)   |
|  DATA   |   [Cobalt Strike hashes](https://bazaar.abuse.ch/browse/yara/CobaltStrike/)  |  This page shows some basic information the Yara rule CobaltStrike including corresponding malware samples.  |  ![](https://img.shields.io/static/v1?label=data&message=hot&color=red)   |
|  DATA   |   [List of Cobalt Strike servers](https://docs.google.com/spreadsheets/d/1bYvBh6NkNYGstfQWnT5n7cSxdhjSn1mduX8cziWSGrw/edit#gid=766378683)  |  List of Cobalt Strike servers  |  ![](https://img.shields.io/static/v1?label=data&message=hot&color=red)   |
|  DATA   |   [CobaltStrike samples pass=infected](https://www.dropbox.com/s/o5493msqarg3iyu/Cobalt%20Strike.7z?dl=0)  |  CobaltStrike samples  |  ![](https://img.shields.io/static/v1?label=data&message=hot&color=red)   |
|  DATA   |   [List of spawns from exposed Cobalt Strike C2](https://gist.github.com/MHaggis/bdcd0e6d5c727e5b297a3e69e6c52286)  |  List of spawns from exposed Cobalt Strike C2  |  ![](https://img.shields.io/static/v1?label=data&message=hot&color=red)   |
|  YARA   |   [apt_cobaltstrike](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cobaltstrike.yar)  |  Cobalt Strike Yara  |  ![](https://img.shields.io/static/v1?label=yara&message=hot&color=red)   |
|  YARA   |   [apt_cobaltstrike_evasive](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cobaltstrike_evasive.yar)  |  Cobalt Strike Yara  |  ![](https://img.shields.io/static/v1?label=yara&message=hot&color=red)   |
|  YARA   |   [rules](https://github.com/Te-k/cobaltstrike/blob/master/rules.yar)  |  Cobalt Strike Yara  |  ![](https://img.shields.io/static/v1?label=yara&message=hot&color=red)   |
