---
title: "Microfluidic Device"
excerpt: "Microfluidic Device used to analyze the mixing of biological components at a microscale."
header:
  image: /assets/img/Syringe Pump Github.JPG
  teaser: /assets/img/Syringe Pump Github.JPG
gallery:
  - url: /assets/img/Syringepump Enclosure.png
    image_path: assets/img/Syringepump Enclosure.png
  - url: /assets/img/Syringe Pump Lid.png
    image_path: assets/img/Syringe Pump Lid.png
    alt: "placeholder image 2"
  - url: /assets/img/Syringe Pump Controls.png
    image_path: /assets/img/Syringe Pump Controls.png
  - url: /assets/img/Syringe Pump Wiring.png
    image_path: /assets/img/Syringe Pump Wiring.png

---

**What are Microfluidic Devices?** 
* Microfluidic Devices are small boards with circuit-like channels that allow for analysis of the physical and chemical properties of fluids. With channels as small as 60-micrometer fluids can be analyzed at a microscale, reducing reagent and sample consumption and in turn resulting in cheaper tests. These devices can be used in several different applications such as medical diagnostics, DNA sequencing, tissue engineering, and even environmental testing. 

*Image of Devices*

**Cancer Detection using Microfluidic Devices**
* Microfluidic Devices have many applications, one of the most influential being cancer detection. Most Circulating Tumor Cells (CTCs) are larger than healthy cells, these devices can isolate these cells based on their size using microscale filters and precise pore sizes. These pore sizes allow healthy cells and blood serum to pass through but capture these CTCs. Furthermore, Density-Based separation can be used to separate CTCs from the blood with density gradients, the sedimentation rate for Tumor cells will differ greatly from healthy cells. These devices could also incorporate immunogenic techniques for isolating Cancer cells by flowing blood through channels with antibodies that can bind. These antibodies could be tagged with some maker-like fluorescents which would allow for visual analysis.   

* Image of Cancer Detection Microfluidic Device Devices

**Challenges with Mixing Fluids in Microfluidic Devices**
* One of the biggest challenges of Microfluidic Devices comes with what is so great about these devices: The size. The channels in these devices allow for the transport, sorting, and mixing of reagents at a small volume. However, the flow characteristic of liquids in small volumes is Laminar Flow. The fluids do not experience turbulent flow or mixing, but mixing is important for performing biological assays. For example, antibodies might not interact with the blood sample as well or if at all which will reduce the detection rate from the example above since diffusion is the only medium of mixing. To combat this caveat, the correction area has to be increased, altering the surface area to volume ratio to promote mixing. The cross-sectional area is increased through geometries like serpentine path, splitting flow paths, adding sharp corners, Herringbone, Chevron, and inclined mixers to introduce Chaotic Advection. 

* Image of Laminar Flow and Geometries from Paper


**CAD Model of Microfluidic Device**
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e4db2342f1295657f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

**Process of Creating a Microfluidic Device**
* Hi


**Mixing of Green and Red Fluids**
* Video

**Mixing Sections**
* On the Left side of the device, the design principle for the mixing section included a series of splitting flow paths, sharp corners, and inclined mixers to introduce Chaotic Advection. When the fluid enters the device, it comes into contact with another and splits into one pathway. Here the contact and turn allow for contact and mixing. After this conversion, the path has a series of inclined mixers (4), which disrupt the parallel flow further. These inclined mixers were made with half triangles at a width and a height of 1 mm. After this chaotic short distance, the paths diverge, and then each path goes through a sharp turn inducing Chaotic Advection. pathway after the mixers are at a height and width of .5 mm. The individual channels then converge into a larger channel increasing the cross-sectional area which introduces another round of chaotic fluid behavior. The fluid then goes through a series of conversions and diversions and a final turn to fully mix with one another. These paths have a width and height of 1mm. 

* On the Right side of the device, the design principle for the mixing section involved incorporating an inclined configuration paired with a zig-zag pattern. When the two fluids converge for mixing initiation, they traverse through the inclined mixing segment. Subsequently, the fluid progresses through a zig-zag segment before encountering another inclined portion, followed by another zig-zag. This alternating pattern aims to provide numerous opportunities for the fluids to intermix effectively. The corners of the zig-zag feature a 60° angle, facilitating mixing at the extremities. Additionally, the recesses in the inclined mixing segment aid in disrupting fluid flow uniformity, thereby enhancing mixing. Dimensional specifications were determined by assessing the capacity for accommodating bends in the zig-zag pattern and divots within my portion of the uFluidic device. The divots in the inclined mixing sections, measuring 1 mm in length, width, and height were chosen to strike a balance between size and mixing efficiency.

{% include gallery caption="This is a sample gallery to go along with this case study." %}


