---
title: "Microfluidic Device"
excerpt: "Microfluidic Device used to analyze the mixing of biological components at a microscale."
header:
  image: /assets/img/Device bannerpng.png
  teaser: /assets/img/Horizontal Mixing.jpg

gallery:
  - url: /assets/img/Device Mold.JPG
    image_path: /assets/img/Device Mold.JPG
  - url: /assets/img/Mold + Device.jpg
    image_path: /assets/img/Mold + Device.jpg
    alt: "placeholder image 2"
  - url: /assets/img/Device Running.jpg
    image_path: /assets/img/Device Running.jpg
---

**What are Microfluidic Devices?** 

* Microfluidic devices are small boards with circuit-like channels that allow for the analysis of the physical and chemical properties of fluids. With channels as small as 60 micrometers, fluids can be analyzed at a microscale, reducing reagent and sample consumption, and in turn resulting in cheaper tests. These devices can be used in several different applications such as medical diagnostics, DNA sequencing, tissue engineering, and even environmental testing.

![Microfluidic Device](https://formlabs.com/_next/image/?url=https%3A%2F%2Fformlabs-media.formlabs.com%2Ffiler_public_thumbnails%2Ffiler_public%2F70%2F81%2F7081d602-babd-4b6a-93a9-3c52fdb075b0%2Fimage3.jpg__1354x0_q85_subsampling-2.jpg&w=3840&q=75)

**Cancer Detection using Microfluidic Devices**
* Microfluidic devices have many applications, with one of the most influential being cancer detection. Most circulating tumor cells (CTCs) are larger than healthy cells. These devices can isolate these cells based on their size using microscale filters and precise pore sizes. These pore sizes allow healthy cells and blood serum to pass through but capture these CTCs. Furthermore, density-based separation can be used to separate CTCs from the blood with density gradients; the sedimentation rate for tumor cells will differ greatly from healthy cells. These devices could also incorporate immunogenic techniques for isolating cancer cells by flowing blood through channels with antibodies that can bind. These antibodies could be tagged with some marker-like fluorescents, which would allow for visual analysis.  

![Circualting Cancer Cells](https://healthcare-in-europe.com/media/story_section_image/2264/image-01-menarini-silicon-biosystems-circulating-tumor-cell.jpg)

**Challenges with Mixing Fluids in Microfluidic Devices**
* One of the biggest challenges of microfluidic devices arises from their defining feature: size. The channels in these devices facilitate the transport, sorting, and mixing of reagents at a small volume. However, the flow characteristic of liquids in small volumes is laminar flow. The fluids do not experience turbulent flow or mixing, which is crucial for performing biological assays. For example, antibodies might not interact with the blood sample as effectively, or at all, which would reduce the detection rate mentioned earlier, as diffusion becomes the only medium of mixing. To address this limitation, the effective mixing area has to be increased, altering the surface area-to-volume ratio to promote mixing. The cross-sectional area is expanded through geometries such as serpentine paths, splitting flow paths, adding sharp corners, and incorporating mixing elements like herringbone, chevron, and inclined mixers to introduce chaotic advection.

![Laminar vs Turbulent Flow](https://www.bronkhorst.com/getmedia/b29e66cb-8121-47d7-ac22-a715eb24e1b8/LaminarVSTurbulent.png?width=)


**CAD Model of Microfluidic Device**
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e0362c82f4acd0594?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>



**Process of Creating a Microfluidic Device**
* This microfluidic device was created using a 3D printing technique called stereolithography (SLA), which involves using UV light to photopolymerize resin. The first step is to design a mold using computer-aided design (CAD) software. Most designs include features that encourage chaotic advection so that mixing occurs within the channels. While many materials can be 3D printed, SLA is superior to other 3D printing technologies due to its high resolutions, smooth surfaces, consistent layering, and relatively faster operating speed. These characteristics allow for the incorporation of fine details like channels, divots, and geometries, which are required for mixing in these devices. 
* Using SLA, the resin is cured using UV light in a layer-by-layer fashion. After all the layers have been created and solidified, the post-processing of this model begins. Post-processing involves washing the resin (monomers) and curing any remaining resin (monomers). This process typically takes around five minutes. The washing and curing process not only increase mechanical properties (monomers inhibit elastomer crosslinking), but also reduce cytotoxicity by removing the monomer. 
* After curing and washing, the mold undergoes Parylene coating. Parylene is an FDA USP Class VI polymer commonly used as a coating for implants in the human body. This coating allows for easier removal of cast polydimethylsiloxane (PDMS) and improves surface quality by making the mold more hydrophobic and biocompatible. This reduces cytotoxicity and other adverse reactions that might occur during sample testing and biological reagent mixing. The coating also increases the lifespan of the mold, enabling fabrication of more devices without degradation or alteration. PDMS is then polymerized on the master mold. The coating could also be applied to the device itself, making it biocompatible and reducing adverse reactions. Additionally, it adds to the durability and lifespan of the device by protecting it from harsh fluids, leakage, contamination, and wear and tear.
* Plasma bonding is used to seal microfluidic devices. When using plasma, the device is exposed to low-pressure plasma to encourage binding to glass slides, eliminating leaks.

* Overall Steps
  * Mold designed using Fusion 360 (Autodesk) and printed using a Form 3 SLA printer (Formlabs). The clear resin was used. 
  * Pritns washed with isopropyl alcohol and then placed in the Formlabs UV cure for 60 seconds at 60 °C.
  * Prints then coated with Parylene-C in Labcoter PDS 2010 perylene deposition machine (Specialty Coating Systems).
  * Prints were cured using curing agents and PDMS (polydimethyl siloxane) was added.
  * Then PDMS devices were bonded to glass coverslips using a PlasmaFlo PDC-FMG plasma cleaner (Harrick Plasma).


**Mixing of Green and Red Fluids Video**
[![Watch the video](https://www.strouse.com/hubfs/iStock-842214296.jpg)](https://youtube.com/shorts/7zwTe8fBs40)

**Mixing Sections**
* On the left side (top) of the device, the design principle for the mixing section includes a series of splitting flow paths, sharp corners, and inclined mixers to introduce chaotic advection. When the fluid enters the device, it comes into contact with another and splits into one pathway. Here, the contact and turn allow for mixing. After this division, the path contains a series of inclined mixers (4), which further disrupt the parallel flow. These inclined mixers are made with half triangles at a width and height of 1 mm. After this short chaotic distance, the paths diverge, and then each path goes through a sharp turn, inducing chaotic advection. The pathways after the mixers are at a height and width of 0.5 mm. The individual channels then converge into a larger channel, increasing the cross-sectional area, which introduces another round of chaotic fluid behavior. The fluid then goes through a series of conversions, diversions, and a final turn to fully mix with one another. These paths have a width and height of 1 mm.

* On the Right side of the device, the design principle for the mixing section involved incorporating an inclined configuration paired with a zig-zag pattern. When the two fluids converge for mixing initiation, they traverse through the inclined mixing segment. Subsequently, the fluid progresses through a zig-zag segment before encountering another inclined portion, followed by another zig-zag. This alternating pattern aims to provide numerous opportunities for the fluids to intermix effectively. The corners of the zig-zag feature a 60° angle, facilitating mixing at the extremities. Additionally, the recesses in the inclined mixing segment aid in disrupting fluid flow uniformity, thereby enhancing mixing. Dimensional specifications were determined by assessing the capacity for accommodating bends in the zig-zag pattern and divots within my portion of the uFluidic device. The divots in the inclined mixing sections, measuring 1 mm in length, width, and height were chosen to strike a balance between size and mixing efficiency.

{% include gallery caption="This is a sample gallery to go along with this case study." %}


