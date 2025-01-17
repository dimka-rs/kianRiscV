<img src="kianv_linux_soc.jpg" alt="Kianv Soc" width="300"/>
KianV Linux RISC-V Harris Edition (SOC)
RISC-V is an open standard instruction set architecture (ISA) based on 
reduced instruction set computer (RISC) principles. 
After successfully earning my **HarveyMuddX-ENGR85B** certification, 
I acquired the skills to design a hierarchical RISC-V CPU.

In the previous year, I completed an exam on **Building a RISC-V CPU Core**. 
This experience led me to refine my prior RISC-V SOC, the kianv simple edition. 
This initial endeavor was a significant learning curve, crafted through trial and error without simulation. 
It provided invaluable insights into **logical design** thinking.
[Review the archived implementation.](https://github.com/splinedrive/kianRiscV/tree/master/archive).

<img src="./certificates.png" width="80%" height="80%"/>

Quick start
===========

```
curl -sL https://tinyurl.com/4cbt7um7 | openFPGALoader  --board=tangnano20k --file-type ext --external-flash -f && picocom -b 2000000 /dev/ttyUSB1
```

You need to have **openFPGALoader** installed either from [source](https://github.com/trabucayre/openFPGALoader) or [prebuilt](https://github.com/YosysHQ/oss-cad-suite-build/releases)


Linux SOC
=========
```
 __  __ __               ___ ___ _____   __
|  |/  |__|.---.-.-----.|   |   |     |_|__|.-----.--.--.--.--.
|     <|  ||  _  |     ||   |   |       |  ||     |  |  |_   _|
|__|\__|__||___._|__|__| \_____/|_______|__||__|__|_____|__.__|
```
## KianV RISC-V Linux: Booting Linux like never before!

With KianV RISC-V Linux, booting Linux is not just possible, it's exhilarating. That's right! If you've ever wanted to experience Linux booting in a whole new light, this is your chance.
🔗 Dive deep into the [implementation details here](https://github.com/splinedrive/kianRiscV/blob/master/linux_socs/kianv_harris_mcycle_edition/README.md).
🎥 Or, if you're more of a visual learner, [watch the Kian Linux Soc in action!](https://twitter.com/i/status/1649359364010983424)

# Some Hardware designs can be found here
[Hardware designs](https://github.com/splinedrive/kianRiscV/blob/master/pcb)
