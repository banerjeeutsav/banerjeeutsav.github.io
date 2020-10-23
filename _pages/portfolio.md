---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<!-- 
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

<span style="color:#CC00CC;">[2019]</span> Energy-Efficient Configurable Quantum-Secure Lattice Cryptography Processor
---------------

Modern public key protocols, such as RSA and ECC, will be rendered insecure by Shor’s algorithm when large-scale quantum computers are built. Therefore, cryptographers are working on quantum-resistant algorithms, and lattice-based cryptography has emerged as a prime candidate. However, high computational complexity of these algorithms makes it challenging to implement lattice-based protocols on resource-constrained IoT devices which need to secure data against both present and future adversaries. To address this challenge, we present a lattice cryptography processor with configurable parameters which enables up to two orders of magnitude energy savings and 124k-gate reduction in system area through architectural optimizations. This is also the first ASIC implementation which demonstrates multiple lattice-based protocols proposed in the NIST post-quantum standardization process.

![](/images/portfolio-fig4.png)

<b>Press Mentions:</b> <a href="http://news.mit.edu/2019/securing-internet-things-in-quantum-age-0301" style="color:#0645AD;">MIT News</a>, <a href="https://spectrum.ieee.org/tech-talk/computing/embedded-systems/circuit-secures-the-iot-against-quantum-attack" style="color:#0645AD;">IEEE Spectrum</a>, <a href="https://techxplore.com/news/2019-03-internet-quantum-age.html" style="color:#0645AD;">TechXplore</a>, <a href="https://scienceblog.com/506455/securing-the-internet-of-things-in-the-quantum-age/
" style="color:#0645AD;">Science Blog</a>, <a href="https://pqczoo.com/hardware/design/2019/08/09/SapphireLatticeCrypto.html" style="color:#0645AD;">PQCzoo</a>

<b>References:</b>
* <b>U. Banerjee</b>, T. S. Ukyab, A. P. Chandrakasan, "A Low-Power Side-Channel-Secure Configurable Accelerator for Post-Quantum Lattice-Based Cryptography", <i>ACM/IEEE International Symposium on Low Power Electronics and Design (ISLPED) Design Contest</i>, August 2020. [<a href="https://banerjeeutsav.github.io/files/2020-islped-design-contest-demo-proposal.pdf" style="color:#0645AD;">link</a>]
* <b>U. Banerjee</b>, A. P. Chandrakasan, "Sapphire-Sim: Macro-Op-Level Simulator for Ring-LWE and Module-LWE Hardware Acceleration," <i>GitHub</i>, December 2019. [<a href="https://github.com/banerjeeutsav/sapphire_sim" style="color:#0645AD;">link</a>]
* <b>U. Banerjee</b>, T. S. Ukyab, A. P. Chandrakasan, "Sapphire: A Configurable Crypto-Processor for Post-Quantum Lattice-based Protocols (Extended Version)," <i>IACR Cryptology ePrint Archive</i>, October 2019. [<a href="https://eprint.iacr.org/2019/1140" style="color:#0645AD;">link</a>]
* <b>U. Banerjee</b>, T. S. Ukyab, A. P. Chandrakasan, "Sapphire: A Configurable Crypto-Processor for Post-Quantum Lattice-based Protocols," <i>IACR Transactions on Cryptographic Hardware and Embedded Systems</i>, August 2019. [<a href="https://tches.iacr.org/index.php/TCHES/article/view/8344/" style="color:#0645AD;">link</a>] [<a href="https://arxiv.org/abs/1910.07557" style="color:#0645AD;">arXiv</a>] [<a href="https://ches.iacr.org/2019/src/slides/Day1/Session1_Lattice_onlypdfs/Paper3_PPT_CHES_2019_UtsavBanerjee.pdf" style="color:#0645AD;">slides</a>]
* <b>U. Banerjee</b>, A. Pathak, A. P. Chandrakasan, "An Energy-Efficient Configurable Lattice Cryptography Processor for the Quantum-Secure Internet of Things," <i>IEEE International Solid-State Circuits Conference (ISSCC)</i>, February 2019. [<a href="https://ieeexplore.ieee.org/document/8662528/" style="color:#0645AD;">link</a>] [<a href="https://arxiv.org/abs/1903.04570" style="color:#0645AD;">arXiv</a>]

<span style="color:#CC00CC;">[2018]</span> Energy-Efficient Reconfigurable DTLS Cryptographic Engine for IoT Security
---------------

End-to-end security protocols, like Datagram Transport Layer Security (DTLS), enable the establishment of mutually authenticated confidential channels between edge nodes and the cloud, even in the presence of untrusted and potentially malicious network infrastructure. While this makes DTLS an ideal solution for IoT, the associated computational cost makes software-only implementations prohibitively expensive for resource-constrained embedded devices. We address this challenge through three key contributions: reconfigurable cryptographic accelerators enable two orders of magnitude energy savings, a dedicated DTLS engine offloads control flow to hardware, reducing program code and memory usage by ~10x, and an on-chip RISC-V core exercises the flexibility of the cryptographic accelerators to demonstrate security applications beyond DTLS.

![](/images/portfolio-fig3.png)

<b>Press Mentions:</b> <a href="http://news.mit.edu/2018/energy-efficient-encryption-internet-of-things-0213" style="color:#0645AD;">MIT News</a>, <a href="https://www.ft.com/content/08fcd0f2-86a3-11e8-9199-c2a4754b5a0e" style="color:#0645AD;">Financial Times</a>, <a href="https://www.techrepublic.com/article/new-iot-chips-speed-encryption-dramatically-reduce-power-consumption-and-memory-requirements/" style="color:#0645AD;">TechRepublic</a>, <a href="http://www.zdnet.com/article/mit-creates-energy-efficient-chips-for-internet-of-things-device-encryption/" style="color:#0645AD;">ZDNet</a>, <a href="https://www.techexplorist.com/new-energy-efficient-encryption-technique-internet-things/11714/" style="color:#0645AD;">TechExplorist</a>, <a href="https://www.engadget.com/2018/02/13/mit-low-power-encryption-chip-internet-of-things-secure/" style="color:#0645AD;">Engadget</a>, <a href="https://www.bitdefender.com/box/blog/iot-news/mit-reveals-public-key-encryption-chip-secure-iot-devices/" style="color:#0645AD;">BitDefender Blog</a>, <a href="https://fuse.wikichip.org/news/1068/isscc-2018-mits-low-power-hardware-crypto-risc-v-iot-processor/" style="color:#0645AD;">WikiChip</a>

<b>References:</b>
* <b>U. Banerjee</b>, A. Wright, C. Juvekar, M. Waller, Arvind, A. P. Chandrakasan, "An Energy-Efficient Reconfigurable DTLS Cryptographic Engine for Securing Internet-of-Things Applications," <i>IEEE Journal of Solid-State Circuits</i>, May 2019. [<a href="https://ieeexplore.ieee.org/document/8721457/" style="color:#0645AD;">link</a>] [<a href="https://arxiv.org/abs/1907.04455" style="color:#0645AD;">arXiv</a>]
* <b>U. Banerjee</b>, C. Juvekar, A. Wright, Arvind, A. P. Chandrakasan, "An Energy-Efficient Reconfigurable DTLS Cryptographic Engine for End-to-End Security in IoT Applications," <i>IEEE International Solid-State Circuits Conference (ISSCC)</i>, February 2018. [<a href="https://ieeexplore.ieee.org/document/8310174/" style="color:#0645AD;">link</a>] [<a href="https://arxiv.org/abs/1903.04387" style="color:#0645AD;">arXiv</a>] [<a href="https://pdfs.semanticscholar.org/6b3f/8ca05dfd2f9e2ad9de5093f972c9b759592f.pdf" style="color:#0645AD;">slides</a>]

<span style="color:#CC00CC;">[2017]</span> Energy-Efficient Datagram Transport Layer Security for the Internet of Things
---------------

In the fast growing world of the Internet of Things (IoT), security has become a major concern. Datagram Transport Layer Security (DTLS) is considered one of the most suited protocols for securing the IoT. However, computation and communication overheads make it very expensive to implement DTLS on resource-constrained IoT sensor nodes. We profile the energy costs of DTLS 1.3 using experimental models for cryptographic computations and radio-frequency (RF) communications. Based on this analysis, we present eeDTLS, a low-energy variant of DTLS, that provides the same security strength as DTLS, but has lower energy requirements. By employing a combination of packet size reduction and optimized handshake computations, eeDTLS can provide up to 45% energy savings in a typical IoT use case. eeDTLS can be implemented in conjunction with any low-energy IoT RF protocol, and the proposed energy models and protocol optimizations can also be used to improve the energy efficiency of custom IoT security architectures.

![](/images/portfolio-fig2.png)

<b>References:</b>
* <b>U. Banerjee</b>, C. Juvekar, S. H. Fuller, A. P. Chandrakasan, "eeDTLS: Energy-Efficient Datagram Transport Layer Security for the Internet of Things," <i>IEEE Global Communications Conference (GLOBECOM)</i>, December 2017. [<a href="https://ieeexplore.ieee.org/document/8255053/" style="color:#0645AD;">link</a>]

<span style="color:#CC00CC;">[2015]</span> Power Side-Channel Attack on Embedded Software Encryption
---------------

We demonstrate the extraction of an AES secret key from flash memory on the ATMega328 microcontroller (the microcontroller used on the popular Arduino Genuino/Uno board). We loaded a standard AVR-architecture AES-128 implementation onto the chip and encrypted randomly chosen plaintexts with several different keys. We measured the chip’s power consumption during encryption, correlated observed power consumption with the expected power consumption of the plaintexts with every possible key, and ultimately extracted the 128-bit key used during AES.

![](/images/portfolio-fig1.png)

<b>References:</b>
* <b>U. Banerjee</b>, L. Ho, S. Koppula, "Power-Based Side-Channel Attack for AES Key Extraction on the ATMega328 Microcontroller," <i>MIT Computer Systems Security</i>, December 2015. [<a href="https://css.csail.mit.edu/6.858/2015/projects/utsav-lisayz-skoppula.pdf" style="color:#0645AD;">link</a>]