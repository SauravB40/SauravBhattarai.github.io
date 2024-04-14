---
title: "Bike Phone Mount"
excerpt: "Versatile Bike Phone Mount designed using Top-Down Modeling"
header:
  image: /assets/img/DFL2.1.jpg

  teaser: /assets/img/DFL2.1.jpg



gallery:
  - url: /assets/img/PI.JPG
    image_path: /assets/img/PI.JPG
  - url: /assets/img/PT.JPG
    image_path: /assets/img/PT.JPG
  - url: /assets/img/PW.JPG
    image_path: /assets/img/PW.JPG
  - url: assets/img/Pliers+Res.jpg
    image_path: assets/img/Pliers+Res.jpg
  - url: /assets/img/Verticle Pliers.jpg
    image_path: /assets/img/Verticle Pliers.jpg
  - url: /assets/img/PLiersGIF.MOV
    image_path: /assets/img/PLiersGIF.MOV

---

**Print in Place Parts** 
* Print in Place 3D printed designs are a great way to increase productivity, design intricacies, and flexibility without the hassle of test fitting, clearance issues, or sacrificing practicality. These designs do not sacrifice details but add mobility and flexibility through the use of hinges, links, and joints. These characteristics can be added through intricate geometries or even incorporated by using different materials for different parts using Dual Extrusion printers. 


**What are applications for print-in-place designs?** 
* There are many applications for print-in-place designs. They can be used in tools like pliers and wrenches, help represent anatomical animal models, and create toys like slinkies and fidget cubes. Print-in-place designs have been used in designing bearing blocks where the inner areas are exposed to more rugged environments. Therefore, the material inside can be made abrasion-proof, while the exterior can be rigid and hard to protect and anchor the block. Another application would be hinges where there are anchors and a swivel that allows for smooth turning with a tight fit.

**Combination of Print-in-Place Materials**
* Many combinations of printing materials can be utilized; however, it depends on the Surface Energy, Chemical Composition, Shrinkage and Cooling Rates, and Mechanical Compatibility. Surface energy is the energy required to create or maintain the surface of the material. Polar materials usually have high surface energy, while non-polar materials have lower surface energy due to the distribution of charges. For the best adhesion, materials with similar surface energy are ideal. Polycarbonate, polyester, nylon, acrylonitrile butadiene styrene (ABS), and acrylic have medium surface energy. Polyethylene, polyvinyl alcohol (PVA), ethylene vinyl acetate (EVA), and polypropylene have low surface energy. Having similar chemical compositions, which include types of intermolecular forces, also contributes to the adherence of different material types.

* Common Material Duos
  * PLA and TPU
  * PLA and PVA
  * ABS and HIPs

**Print-in-Place Multi-Material Pliers**
* Pliers, found in every toolbox known to man, are used to grip nails and cables, tighten or loosen bolts, and even cut wires. This tool can make or break a toolbox, so a reliable plier is a must. The use of multiple materials like TPU and PLA in the pliers allows for more functional parts as well as practicality. For example, the jaws can collapse in and spring back out when the pressure on the grips is released. This design also ensures a tight fit between the TPU and PLA parts, which increases the mechanical function of the pliers. 

**Mechanics of Multi-Material Pliers**
* The portion that allows the pliers to move is the rectangular spring between the two handles and jaws. When the handles are compressed, the spring shears, allowing the jaws to compress at a higher rate. This translation is due to the TPU's characteristic high ductility. The inner mesh is aligned at a 90-degree angle, which allows the shearing of the spring to be translated from the bottom half to the top half with high accuracy and multiplicity. The superior tear strength and elasticity of the spring then allow the jaws to bounce back to a neutral, open position. This, along with the durability, allows for many actuations over the spring's lifetime


**CAD Model of Print-in-Place Pliers**
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e88060f78c0e555c7?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>



**Design Specification of Pliers**
* The pliers were designed with ergonomics, grip, and versatility in mind. The handles have fillets that allow the hands to comfortably wrap around the corners, increasing grip and agility when in use. The large handle also allows users with various hand sizes to use the pliers. The large handle also allows the spring to compress and actuate the pliers with little to no force. Since the spring is joined with the handle and jaws through a dovetail fit, these parts can be removed and replaced with jaws and handles that can work for specific applications. The pliers can lift items as small as resistors to items as large as mugs. This is enabled by the slight inward angle of the jaws, making them very versatile. The total length of the jaw is around 30 mm, but the inward portion is around 10 mm, which allows for access to nooks and crannies. The thickness of the pliers throughout the design is 7.5 mm, which is around the thickness of an iPhone, allowing for a comfortable and nimble grip but also mechanical strength.



**Print Settings and Iterative Process**
* For the PLA portion of the pliers, including the handles and jaws, the settings were Voron Rigid DF settings. For PLA, the extrusion temperature was 200 degrees Celsius and the bed temp was 50 degrees Celsius. The settings for TPU were the same as the settings for the Voron Elastic DF settings. For TPU, the extrusion temperature was around 235 degrees Celcius, and the bed temperature was 60. 

* Originally, the spring component was printed at a very high fill density and a rectilinear fill pattern which increased the rigidity. This made the actuation of the jaws difficult. Also, the angle of the jaws to the handle had to be adjusted by 5 mm to ensure the jaws remained open at the neutral state and were able to fully close. 

* For the spring component, the bottom and top layers were eliminated in Super Slicer. This was done to increase the elasticity and decrease rigidness. Further, the base layer height was .3 mm increasing layer adherence. The fill density was at 13% in a Grid fill pattern to maximize the spring-like characteristic. The settings for the handles and jaws were standard PLA variables, nothing was manually changed. 


{% include gallery caption="This is a sample gallery to go along with this case study." %}



