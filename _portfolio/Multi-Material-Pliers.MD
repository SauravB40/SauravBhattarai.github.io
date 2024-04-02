---
title: "Multi-Material Pliers"
excerpt: "Needle nose Mulit-Material Pliers that are capable of gripping and picking up various materials."
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

**Print in Place Parts** 
* Print in Place 3D printed designs are a great way to increase productivity, design intricacies, and flexibility without the hassle of test fitting, clearance issues, or sacrificing practicality. These designs do not sacrifice details but add mobility and flexibility through the use of hinges, links, and joints. These characteristics can be added through intricate geometries or even incorporated by using different materials for different parts using Dual Extrusion printers. 


**What are applications for print-in-place designs?** 
*There are many application for prin in place designs, they can be used in tools liek pliers and wrenches, help respresent anatomical animal models, create toys like slingkies and fidget cubes. Print-in-places have been used in deisnging bearing blocks where the inner area are exposed to more rugged envemrnts, so the mateiral isside cna made of mateiral that cna be abrasion proof whiel the exterior cna be rigid and hard to protect and anchor the block. Another applciation would be hinges where there are anchros and a swivel that allows for smooth turnign with a tight fit. 

**Combination of Print in Place Materials**
*There are many combiantion of print amterial that can be utilized, however it depends on the Surface Energy, Chemical composition, Shrinkage and Cooling Rates, and Mechanical Compatibility. Surface energy is the energy requried to create or maintain the surface of the material. Polar amterials usally have high surfac eerngy while non-pola ramteirals have lower surface energy due to distribution of charges. For the best adhesion, materials with better simialr surface energy is the best. Polycarbonate, polyester, nylon, acrylonitrile butadiene styrene (ABS), and acrylic have medium surface energy. Polyethylene, polyvinyl alcohol (PVA), ethylene vinyl acetate (EVA), and polypropylene have low surface energy. Having simialr chemcial composition which includes type sof intermolecualr forces also adds to the adhereing of diffent mateiral types. 

**Challenges with Mixing Fluids in Microfluidic Devices**
* One of the biggest challenges of microfluidic devices arises from their defining feature: size. The channels in these devices facilitate the transport, sorting, and mixing of reagents at a small volume. However, the flow characteristic of liquids in small volumes is laminar flow. The fluids do not experience turbulent flow or mixing, which is crucial for performing biological assays. For example, antibodies might not interact with the blood sample as effectively, or at all, which would reduce the detection rate mentioned earlier, as diffusion becomes the only medium of mixing. To address this limitation, the effective mixing area has to be increased, altering the surface area-to-volume ratio to promote mixing. The cross-sectional area is expanded through geometries such as serpentine paths, splitting flow paths, adding sharp corners, and incorporating mixing elements like herringbone, chevron, and inclined mixers to introduce chaotic advection.

* Common Material Duos**
  * PLA and TPU
  * PLA and PVA
  * ABS and HIPs

**Print-in-Place Multi-Material Pliers**
* Pliers, found inside every toolbox known to man, are used to grip nails and cables, tighten or loosen bolts, and even cut wires. This tool makes or breaks a toolbox, so a reliable plier is a must. The use of multi materials like TPU and PLA in the pliers allows for more functional parts as well as practicality. For example, the jaws can collapse in and spring back out when the pressure on the grips is released. This design also comes with a tight fit between the TPU and PLA parts which increases the mechanical function of the pliers.

**Mechanics of Mulit-Material Pliers**
* The portion that allwos the pliers to move is the rectangualr spring betwwen the two handles and jaws. When the handles are compressed, the spring shears which allwos for jaws to compress at a hgiehr rate.  This tranlation is due to the TPU's characteristic, high ductility. The inner mesh is lined at a 90 degree angle, which allwos the shearing of spring to be trnalated form the bottom half to the top half with high accruacy and mulitplicty. THe sueprior tear strenght and elasticty of sprign then allwos the aws to bounce bakc to a neutral, open, postion. This along with the durbality allwos for many actuations over the sprigns life time. 

**Design Specification of Pliers**
* The plier was deisgned with ergonimcis, grip, and veraility in mind. The handles hae fillet which allwos the hands to comforatble wrap aorund the corners icnreasing grip and agility when in use. THe large handle also allwos for users with various hands sizes the use the pliters. the alrge handle als allwos the spring to compress and actuate the olier with little to no force. Since the spring is joined with the handle and jaws througha dove tial fit, these aprts can be removed and repalced with other parts that can work with specific applications.  The pliers cna lift items as mall as resistors to item as alrge as mugs. This is allwoed with the slight inward angle of the jaws, making them very versitliy. The total length of the jaw is aorund 30 mm, but the inward portion is aorund 10mm, whicch allows for access of nooks and cranneis. The thickness of the pleirs throughotu the desn is 7.5 mm whihc is aorund the thickness of an iPhone allwos for comfroatbel and nible grip. 


**Print Settings**
* For the PlA prtion of pliters, Handle and Jaws, the settings were Voron Rigid DF settings. The settings for TPU was same setting for the Voron Elastic DF settings. 

**Process of Creating a Microfluidic Device**
* This microfluidic device was created using a 3D printing technique called stereolithography (SLA), which involves using UV light to photopolymerize resin. The first step is to design a mold using computer-aided design (CAD) software. Most designs include features that encourage chaotic advection so that mixing occurs within the channels. While many materials can be 3D printed, SLA is superior to other 3D printing technologies due to its high resolutions, smooth surfaces, consistent layering, and relatively faster operating speed. These characteristics allow for the incorporation of fine details like channels, divots, and geometries, which are required for mixing in these devices. 
* Using SLA, the resin is cured using UV light in a layer-by-layer fashion. After all the layers have been created and solidified, the post-processing of this model begins. Post-processing involves washing the resin (monomers) and curing any remaining resin (monomers). This process typically takes around five minutes. The washing and curing process not only increase mechanical properties (monomers inhibit elastomer crosslinking), but also reduce cytotoxicity by removing the monomer. 
* After curing and washing, the mold undergoes Parylene coating. Parylene is an FDA USP Class VI polymer commonly used as a coating for implants in the human body. This coating allows for easier removal of cast polydimethylsiloxane (PDMS) and improves surface quality by making the mold more hydrophobic and biocompatible. This reduces cytotoxicity and other adverse reactions that might occur during sample testing and biological reagent mixing. The coating also increases the lifespan of the mold, enabling the fabrication of more devices without degradation or alteration. PDMS is then polymerized on the master mold. The coating could also be applied to the device itself, making it biocompatible and reducing adverse reactions. Additionally, it adds to the durability and lifespan of the device by protecting it from harsh fluids, leakage, contamination, and wear and tear.
* Plasma bonding is used to seal microfluidic devices. When using plasma, the device is exposed to low-pressure plasma to encourage binding to glass slides, eliminating leaks.

* Overall Steps
  * Mold designed using Fusion 360 (Autodesk) and printed using a Form 3 SLA printer (Formlabs). The clear resin was used. 
  * Prints washed with isopropyl alcohol and washed device for 5 minutes on the print bed, then washed again for 5 minutes in fresh IPA.
  * Device dried for at least 30 minutes, make sure no debris is present.
  * Device cured for 10 seconds using no heat.  
  * Prints then coated with Parylene-C in Labcoter PDS 2010 perylene deposition machine (Specialty Coating Systems).
  * Prints were cured using curing agents and PDMS (polydimethyl siloxane) was added.
  * Then PDMS devices were bonded to glass coverslips using a PlasmaFlo PDC-FMG plasma cleaner (Harrick Plasma).


**Mixing of Green and Red Fluids Video**
[![Watch the video](https://www.strouse.com/hubfs/iStock-842214296.jpg)](https://youtube.com/shorts/7zwTe8fBs40)

**Mixing Sections**
* On the left side (top) of the device, the design principle for the mixing section includes a series of splitting flow paths, sharp corners, and inclined mixers to introduce chaotic advection. When the fluid enters the device, it comes into contact with another and splits into one pathway. Here, the contact and turn allow for mixing. After this division, the path contains a series of inclined mixers (4), which further disrupt the parallel flow. These inclined mixers are made with half triangles at a width and height of 1 mm. After this short chaotic distance, the paths diverge, and then each path goes through a sharp turn, inducing chaotic advection. The pathways after the mixers are at a height and width of 0.5 mm. The individual channels then converge into a larger channel, increasing the cross-sectional area, which introduces another round of chaotic fluid behavior. The fluid then goes through a series of conversions, diversions, and a final turn to fully mix with one another. These paths have a width and height of 1 mm.

* On the Right side of the device, the design principle for the mixing section involved incorporating an inclined configuration paired with a zig-zag pattern. When the two fluids converge for mixing initiation, they traverse through the inclined mixing segment. Subsequently, the fluid progresses through a zig-zag segment before encountering another inclined portion, followed by another zig-zag. This alternating pattern aims to provide numerous opportunities for the fluids to intermix effectively. The corners of the zig-zag feature a 60° angle, facilitating mixing at the extremities. Additionally, the recesses in the inclined mixing segment aid in disrupting fluid flow uniformity, thereby enhancing mixing. Dimensional specifications were determined by assessing the capacity for accommodating bends in the zig-zag pattern and divots within my portion of the uFluidic device. The divots in the inclined mixing sections, measuring 1 mm in length, width, and height were chosen to strike a balance between size and mixing efficiency.

{% include gallery caption="This is a sample gallery to go along with this case study." %}



