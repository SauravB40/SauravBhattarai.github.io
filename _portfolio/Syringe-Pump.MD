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
* Manual Use
  1. Hit third button for forward movement
  2. Hit fourth button for backwards movement

# Recreating the Syringe Pump
* [Arduino Code for the Syringe Pump](https://docs.google.com/document/d/147egtqbcQQGJZjOecSnNWvDvt_aaKVB95mmNoiG48J8/edit?usp=sharing)
* Parts

  | Name     | Quantity |
  | ---      | ---       |
  | [250 mm lead screw with 2 mm pitch and 9 mm lead](https://amzn.to/3infwI0)| 1         |
  | [1/4" x 8mm Flexible Coupling](https://openbuildspartstore.com/1-4-x-8mm-flexible-coupling/) | 1        |
  | [200 mm linear rod with 8 mm diameter](https://www.amazon.com/dp/B07MPGWJMS/ref=cm_sw_em_r_mt_dp_X5AQS0ES7JH8JG83AAZ3) | 2        |
  | [LM8UU Linear bearing for 8 mm diameter rod](https://www.amazon.com/gp/product/B087WPGQ8T/ref=ppx_yo_dt_b_asin_image_o00_s00?ie=UTF8&psc=1) | 2        |
  | [2040 Aluminum Extrusion 1' Length](https://openbuildspartstore.com/v-slot-20x40-linear-rail/) | 1        |
  | [Nema 17 Stepper Motor](https://www.amazon.com/gp/product/B07LF898KN/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1) | 1        |
  | [MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp](https://www.amazon.com/dp/B005T9HGLI/ref=cm_sw_em_r_mt_dp_A8CZ056TM52EJGZTGZGR?_encoding=UTF8&psc=1) | 1        |
  | [Arduino Uno](https://www.amazon.com/dp/B007R9TUJE/ref=cm_sw_em_r_mt_dp_TY8JGK0CJD1JEJM4BNNJ) | 1        |
  | [A4988 Stepper Driver](https://www.amazon.com/dp/B01FFGAKK8/ref=cm_sw_em_r_mt_dp_V0YKTYKDWMR8WHTKA53T?_encoding=UTF8&psc=1) | 1        |
  | [Small Breadboard](https://www.amazon.com/dp/B082VYXDF1/ref=cm_sw_em_r_mt_dp_N6Q28CAGPAYCKCSJKDDC?_encoding=UTF8&psc=1) | 1        |
  | [Panel Mount Latching Push Buttons](https://amzn.to/3VxQ29h) | 1        |
  | [Limit Switch](https://www.amazon.com/gp/product/B073TYWX86/ref=ppx_yo_dt_b_asin_image_o01_s00?ie=UTF8&psc=1) | 1        |
  | [RGB Common Cathode LED](https://www.amazon.com/dp/B0194Y6MW2/ref=cm_sw_em_r_mt_dp_FW3CFQT7ZGFQ2R04N6G3?_encoding=UTF8&psc=1) | 1        |


* Parts

   | Name     | Character |
   | ---      | ---       |
   | Backtick | `         |
   | Pipe     | \|        |

  

{% include gallery caption="This is a sample gallery to go along with this case study." %}
