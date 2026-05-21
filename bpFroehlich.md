## Froehlich Breach Width Information
Information here was originally developed by LMRFC and has been reformatted to fit here.

Breach width computed using equations developed by Froehlich in 1995. Predictor equations were developed using regression analysis of 63 historical dam breaks. The equation derived from this study was predominantly based upon earthen dams under 50ft high.

Breach width is computed with the following:

$$B_a = 0.1803 \cdot K \cdot [V^{0.32} \cdot H^{0.19}]$$

**Where:**
* **$K$** = 1.0 for Piping Failure or 1.4 for Overtopping Failure
* **$B_a$** = Average Breach Width (m)
* **$V$** = Volume of Reservoir (m³)
* **$H$** = Breach Head (m) - defined as Depth of Water at time of Breaching

> **NOTE:** Units of this equation are in metric, conversion is done internally to English units for consistency with the other relations in this GUI and with the USACE NID database.

He also suggests using a breach side slope (h:v) of 1.4 for overtopping failures and 0.9 for other failure modes.

---

## Froehlich Breach Time Information

Breach time is computed using equations developed by Froehlich in 1995. Predictor equations were developed using regression analysis of 63 historical dam breaks. The equation derived from this study was predominantly based upon earthen dams under 50ft high.

Breach time is computed with the following:

$$T = (0.00254 \cdot [ V^{0.53} \cdot H^{-0.9} ]) \cdot 60$$

**Where:**
* **$T$** = Breach Time (min)
* **$V$** = Volume of Reservoir (m³)
* **$H$** = Breach Head (m) - defined as Depth of Water at time of Breaching

> **NOTE:** Units of this equation are in metric, conversion is done internally to English units for consistency with the other relations in this GUI and with the USACE NID database.

He also suggests using a breach side slope (h:v) of 1.4 for overtopping failures and 0.9 for other failure modes.

---

*Additional information can be found in the document "Embankment Dam Breach Parameters Revisited" by Froehlich, D.; 1995b in Water Resources Engineering, Proceedings of the 1995 ASCE Conference on Water Resources Engineering, San Antonio, Texas, August 14-18, 1995, p. 887-891.*
