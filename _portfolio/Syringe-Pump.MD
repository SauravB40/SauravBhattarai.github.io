---
title: "Motorized Syringe Pump"
excerpt: "DIY Syringe Pump capable of adjustbale and percise disposal of fluids at various Flow Rates."
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

# Discription

* **Design and Purpose** Syringe pumps are highly accurate and with continuous flow of liquid allwos for sterility. This pump only has a motor, lead screw, basic computer coding, and a housing, which leads to a simple design while being incredibly useful. However, even lower end syringe pums can cost thousadns of dollars, therfore custom fabrication is economcially advisable. With buttons tahta llwo for manual movment fo the pump as wella s continous movment with set dial, this pump can relaiably push fluids. this pump comes iwth auto shut off feature with light indicators that allows for ease of use. The pump has an output rate that is accuate within .1 uL. 

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e4db2342f1295657f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Operating Instructions

* Automatic Use
  1. Extend the carriage
  2.  Simultaneously, lower the full syringe while adjusting the distance of the Flange Holder (carriage) to fit
  3. Slowly lower the syringe to fit into the Flange Holder, make sure plunger is inserted into the Plunger Holder 
  4. Double chek tip is resting in the Tip Support Groove
  4. Adjust desired flow rate suing dial or enter value in Program
  6. Automated Use
  7. Adjust desired flow rate 
  8. Hit Red Button with silver Casing
* Manual use
  1. Hit third button for forward movement
  2. Hit fourth button for backwards movement

# Recreating the Syringe Pump
* [Arduino Code for the Syringe Pump](https://docs.google.com/document/d/147egtqbcQQGJZjOecSnNWvDvt_aaKVB95mmNoiG48J8/edit?usp=sharing)
* Parts
  | Name     | Character |
  | ---      | ---       |
  | [250 mm lead screw with 2 mm pitch and 2 mm lead](https://www.amazon.com/dp/B07R1H5ZMV/ref=cm_sw_em_r_mt_dp_0YZ13D4HQBGW2Z86PBV1_encoding=UTF8&psc=1)| `         |
  | 1/4" x 8mm Flexible Coupling | \|        |
  | 200 mm linear rod with 8 mm diameter | \|        |
  | LM8UU Linear bearing for 8 mm diameter rod | \|        |
  | 2040 Aluminum Extrusion 1' Length | \|        |
  | Nema 17 Stepper Motor | \|        |
  | MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp | \|        |
  | Arduino Uno | \|        |
  | A4988 Stepper Driver | \|        |
  | Small Breadboard | \|        |
  | A4988 Stepper Driver | \|        |
  | Panel Mount Latching Push Buttons | \|        |
  | Limit Switch | \|        |
  | RGB Common Cathode LED | \|        |

  

{% include gallery caption="This is a sample gallery to go along with this case study." %}
