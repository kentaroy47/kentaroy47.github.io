---
title: "Successive-Approximation Based CMOS Process-Scalable Hybrid ADCs"
collection: publications
permalink: /publication/phd
date: 2019-09-13
venue: 'Ph.D thesis.'
---

[Download paper here](https://github.com/kentaroy47/kentaroy47.github.io/blob/master/_publications/yoshioka_thesis_print_20190806.pdf)

**Abstract:**
Along with CMOS scaling, wireless/wireline communication performances have greatly
advanced. To realize a system on chip (SoC) for such products, high-performance
analog circuits are necessary; for example, high-speed and high-precision analog-todigital converters (ADCs) are often required to convert the received analog signal
to digital. While such SoCs utilize the most leading CMOS technologies to cut
down the costs of the digital circuits, the analog circuit performance inconveniently
degrades as the CMOS scaling advance. To name an example, the Opamp gain
performance greatly degrades with scaling with worsened transistor gain and lower
supply voltages. On the contrary, as the communication standards further evolve,
the performance demands toward analog circuits continue to increase. Thus, the
design of ADCs in scaled CMOS process environments become one of the most
challenging and critical fields of circuit design.
In this thesis, we aim to explore Hybrid ADCs utilizing successive-approximation
(SA) circuitry, which can benefit from process scaling. And ultimately, we target
to establish an ADC design methodology suitable for scaled CMOS technologies.
In chapter 1, the technology trends of the CMOS process scaling are discussed and
scaling effects to the analog circuitry are studied. Moreover, we show that SA
circuitry is suitable for scaled CMOS and explore its limitations as well. Finally,
recent research trends of Hybrid ADCs and its design challenges are discussed.
We propose a Hybrid ADC which heavily utilizes the SA circuitry in chapters
2 and 3. In chapter 2, the Digital Amplifier (DA) technique is proposed to realize
power-efficient and accurate amplification in scaled CMOS which utilizes an SA
10.0
circuitry for amplification. DA cancels out all errors of the low-gain amplifier by
feedback based on SA. Moreover, the amplification accuracy can be arbitrary set by
configuring the number of bits of the DA; the amplifier gain is decoupled from the
transistor intrinsic gain and brings in a new design paradigm for amplifier design
in scaled CMOS. The fabricated ADC with DA achieves SNDR of 61.1dB, FoM of
12.8fJ/conv., which is over 3× improvement compared to conventional ADCs.
In chapter 3, we explore power-efficient and process scalable ultra-high-speed
ADCs, required for high-capacity wireless communications. To achieve low-power
and high-speed ADCs, we propose to dynamically configure the ADC architecture
reflecting the ADC clock frequency, which we name Dynamic Architecture and Frequency Scaling (DAFS). The ADC architecture is reconfigured between successiveapproximation and flash every clock cycle, relying on the conversion delay. A prototype subranging ADC is fabricated in 65 nm CMOS, which is 2× more power-efficient
than the previously reported subranging ADCs.
In chapter 4, we propose a comparator with a variable threshold to explore multibit/step comparisons, which can significantly speed up the successive-approximation
circuitry implemented in chapters 2 and 3. Finally, we establish a conclusion in
chapter 5.

