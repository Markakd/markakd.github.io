---
title: About
---
<font face="Menlo" size=6><b>Zhenpeng Lin</b></font>

Email: zplin<span>@<span>u.northwestern.edu

[Twitter](https://twitter.com/markak_) [Google Scholar](https://scholar.google.com/citations?user=-V2OvtwAAAAJ&hl=en) [CV](./ZhenpengLin.pdf) [PGP Key](./pgp_pub.txt)

I am a Security Researcher at Apple. I obtained my Ph.D. degree from [Northwestern University](https://www.northwestern.edu) under the supervision of [Dr. Xinyu Xing](http://xinyuxing.org/). My Research focuses on OS exploitation and defense. I love hacking in the real world. I have done many Linux kernel exploitation and contributed many security fixes to Linux kernel. I used to play CTF a lot with team [Nu1L](https://nu1l.com), now with [StrawHat](https://strawhat.team/).

# News

**06/2024** One paper studying "page spray" technique in Linux kernel is accepted to USENIX Security 2024!

**02/2024** SeaK is accepted to USENIX Security 2024!

**09/2023** CAMP is accepted to USENIX Security 2024!

**08/2023** I passed my dissertation defense!

**07/2023** One paper introducing a new kernel exploitation technique is accepted to CCS 2023.

**06/2023** One briefing about rooting Android with io\_uring is accepted to Black Hat USA 2023.

**06/2023** One paper about evaluating kernel patch correctness is accepted to USENIX Security 2023.

**06/2023** I will be joining Apple as a Security Researcher this summer.

**10/2022** GREBE is accepted to CSAW 2022 Finalists.

**08/2022** DirtyCred is accepted to CCS.

**07/2022** I report (and exploit) a kernel 0day that could affect millions of Android devices to Google. [[pixel 6 demo]](./pixel6_demo.mp4) [[s22 demo]](./s22_demo.mp4)

**06/2022** Our [submission](https://www.blackhat.com/us-22/briefings/schedule/#cautious-a-new-exploitation-method-no-pipe-but-as-nasty-as-dirty-pipe-27169) of a new exploitation approach is accepted to Black Hat USA.

**05/2022** We (team TUTELARY at NU) pwned lastest Ubuntu system at [Pwn2Own](https://www.zerodayinitiative.com/blog/2022/5/18/pwn2own-vancouver-2022-the-results). [[press]](https://therecord.media/tesla-microsoft-and-ubuntu-bugs-found-during-pwn2own-hacking-competition/)

**11/2021** I am the very first to successfully exploit Google's [COS](https://cloud.google.com/container-optimized-os/docs) through [KCTF VRP](https://security.googleblog.com/2022/02/roses-are-red-violets-are-blue-giving.html).

# Publications

[**Take a Step Further: Understanding Page Spray in Linux Kernel Exploitation**](./papers/page_spray.pdf)
<font size=2>*Ziyi Guo, Dang K Le, **Zhenpeng Lin**, Kyle Zeng, Ruoyu Wang, Tiffany Bao, Yan Shoshitaishvili, Adam Doupé, Xinyu Xing*</font>
USENIX Security 2024

[**SeaK: Rethinking the Design of a Secure Allocator for OS Kernel**](./papers/SeaK.pdf)
<font size=2>*Zicheng Wang, Yicheng Guang, Yueqi Chen, **Zhenpeng Lin**, Michael Le, Dang K Le, Dan Williams, Xinyu Xing, Zhongshu Gu, Hani Jamjoom*</font>
USENIX Security 2024

[**CAMP: Compiler and Allocator-based Heap Memory Protection**](./papers/CAMP.pdf)
<font size=2>***Zhenpeng Lin**, Zheng Yu, Ziyi Guo, Simone Campanoni, Peter Dinda, and Xinyu Xing*</font>
USENIX Security 2024

[**RetSpill: Igniting User-Controlled Data to Burn Away Linux Kernel Protections**]()
<font size=2>*Kyle Zeng, **Zhenpeng Lin**, Kangjie Lu, Xinyu Xing, Fish Wang, Adam Doupé, Yan Shoshitaishvili, Tiffany Bao*</font>
CCS 2023

[**Bad io_uring: A New Era of Rooting for Android**](https://www.blackhat.com/us-23/briefings/schedule/index.html#bad-io_uring-a-new-era-of-rooting-for-android-32243)
<font size=2>***Zhenpeng Lin***, *Xinyu Xing, Zhaofeng Chen, Kang Li*</font>
Black Hat USA 2023 [[slides]]() [[exploit]](https://github.com/Markakd/bad_io_uring)  [[pixel 6 demo]](./pixel6_demo.mp4) [[s22 demo]](./s22_demo.mp4)

[**Mitigating Security Risks in Linux with KLAUS: A Method for Evaluating Patch Correctness**](./papers/KLAUS.pdf)
<font size=2>*Yuhang Wu, **Zhenpeng Lin**, Yueqi Chen, Dang K Le, Dongliang Mu, Xinyu Xing*</font>
USENIX Security 2023

[**DirtyCred: Escalating Privilege in Linux Kernel**](./papers/DirtyCred.pdf)
<font size=2>***Zhenpeng Lin***, *Yuhang Wu, Xinyu Xing*</font>
ACM CCS 2022 [[code]](https://github.com/markakd/DirtyCred) [[slides]](./papers/DirtyCred_CCS_slides.pdf) [[qualify exam slides]](./papers/Qualify_ZhenpengLin.pdf)

[**Cautious! A New Exploitation Method! No Pipe but as Nasty as Dirty Pipe**](https://www.blackhat.com/us-22/briefings/schedule/#cautious-a-new-exploitation-method-no-pipe-but-as-nasty-as-dirty-pipe-27169)
<font size=2>***Zhenpeng Lin***, *Yuhang Wu, Xinyu Xing*</font>
Black Hat USA 2022 [[slides]](./papers/DirtyCred-BH22-Zhenpeng.pdf)

[**GREBE: Unveiling Exploitation Potential for Linux Kernel Bugs**](./papers/GREBE.pdf)
<font size=2>***Zhenpeng Lin***, *Yueqi Chen, Yuhang Wu, Dongliang Mu, Chensheng Yu, Xinyu Xing, Kang Li*</font>
IEEE S&P 2022 (CSAW 22 Finalist)  [[code]](https://github.com/markakd/GREBE) [[slides]](./papers/GREBE_slides.pdf)

[**An In-depth Analysis of Duplicated Linux Kernel Bug Reports**](./papers/bug_analysis.pdf)
<font size=2>*Dongliang Mu, Yuhang Wu, Yueqi Chen, **Zhenpeng Lin**, Chensheng Yu, Xinyu Xing, Gang Wang*</font>
NDSS 2022

[**Your Trash Kernel Bug, My Precious 0-day**](https://www.blackhat.com/eu-21/briefings/schedule/#your-trash-kernel-bug-my-precious--day-24849)
<font size=2>***Zhenpeng Lin***, *Yueqi Chen, Xinyu Xing, Kang Li*</font>
Black Hat Europe 2021 [[slides]](./talks/BHEU21_trash_kernel_bug.pdf)

[**Finding Multiple Bug Effects for More Precise Exploitability Estimation**]()
<font size=2>***Zhenpeng Lin***, *Yueqi Chen*</font>
Linux Security Summit North America 2021 [[slides]](./talks/LSS_2021_Multiple_Error_Behavior.pdf)

[**A General Approach to Bypassing Many Kernel Protections and its Mitigation**](https://www.blackhat.com/asia-21/briefings/schedule/#a-general-approach-to-bypassing-many-kernel-protections-and-its-mitigation-22345)
<font size=2>*Yueqi Chen, **Zhenpeng Lin**, Xinyu Xing*</font>
Black Hat Asia 2021 [[slides]](./talks/bhasia21.pdf)

[**A Systematic Study of Elastic Objects in Kernel Exploitation**](./papers/ELOISE.pdf)
<font size=2>*Yueqi Chen, **Zhenpeng Lin**, Xinyu Xing*</font>
ACM CCS 2020 [[code]](https://github.com/chenyueqi/W2L) [[slides]](./papers/ELOISE_slides.pdf) [[video]](./papers/ELOISE_presentation.mp4)

[**Bypassing Many Kernel Protections Using Elastic Objects**]()
<font size=2>*Yueqi Chen*, ***Zhenpeng Lin***</font>
Linux Security Summit Europe 2020 [[slides]](./talks/Bypassing-Many-Kernel-Protections-Using-Elastic-Objects.pdf)

# Hacking

CVE-2021-3715
CVE-2017-8187
CVE-2017-8188
CVE-2017-8190
CVE-2017-8191
CVE-2017-17223
CVE-2017-17221
CVE-2017-17222

# Articles

[**How AUTOSLAB Changes the Memory Unsafety Game**](https://grsecurity.net/how_autoslab_changes_the_memory_unsafety_game)

# Honors and Awards

**2022**, Google, $50337 reward
**2022**, Pwn2Own Winner
**2021**, LSS North America, Student Travel Grant Award
**2021**, 7th at DEF CON 29 CTF Finals, Team Nu1L
**2021**, Black Hat USA, Student Scholarship
**2020**, Black Hat USA, Student Scholarship

# Community Services

**External reviewer**

* IEEE S&P 2023
* IEEE S&P 2022, USENIX Security 2022, ACM CCS 2022
* USENIX Security 2021, ACM CCS 2021
* USENIX Security 2020, ACM CCS 2020
