# Custom Desktop PC Build – Group 7

**Course**: CSARCH2  
**Section**: S20  
**Group Members**:  
- ALONTO, AZZAM AFGHANI PARICO 
- HO, DENISE LIANA PARANA 
- PAJARILLO, JONAH PAOLO STA. ANA
---

## 1. Introduction TODO
Briefly describe your project build (1–2 paragraphs).  
Mention: target use case (e.g., general-purpose desktop, gaming, programming, data science, etc.) and budget constraint.


This PC build is centered on the AMD Ryzen 7 9800X3D, one of the fastest gaming CPUs available today. It delivers top frame rates by fully utilizing the GPU while staying efficient under load, running cooler and drawing less power than many alternatives. The goal of the system is straightforward: maximize gaming performance while keeping thermals and power use in check.

The build uses an MSI GeForce RTX 5060 Ti, a capable midrange GPU for smooth 1440p gaming and playable 4K in lighter titles. It is backed by 32 GB of DDR5-6000 memory, a fast 1 TB NVMe SSD for responsiveness, and a secondary 1 TB HDD for extra storage. Cooling comes from a 240 mm AIO and the case’s four stock fans, which ensures stable airflow. A 750 W gold-rated PSU provides reliable power with room for upgrades. The full build comes in under the ₱100,000 budget while targeting high-end 1440p performance and workable 4K in demanding games.

---

## 2. Draft Build (PCPartPicker)
This build uses **PCPartPicker System Builder** for compatibility check. 
PCPartPicker Permalink: https://pcpartpicker.com/list/JrpX8Q

### PCPartPicker Build Table
| Component       | Model                | Vendor     | Price (USD) | Notes                                  |
|-----------------|----------------------|------------|-------------|----------------------------------------|
| CPU             | AMD Ryzen 7 9800X3D  | B&H        | $469.00     | 8-core, AM5 socket                     |
| CPU Cooler      | MSI MAG CORELIQUID   | Amazon     | $79.98      | 360mm AIO, fits ATX mid-tower          |
| Motherboard     | MSI PRO B650-A WIFI  | Newegg     | $149.99     | ATX, AM5, DDR5 support                 |
| Memory          | Corsair Vengeance    | Amazon     | $122.99     | 32 GB (2x16), DDR5-6000 CL36           |
| Storage (SSD)   | MSI SPATIUM M480 PRO | MSI        | $64.99      | 1 TB, PCIe 4.0 NVMe                    |
| Storage (HDD)   | Seagate BarraCuda    | Amazon     | $55.59      | 1 TB, 7200 RPM                         |
| Video Card      | MSI VENTUS 2X PLUS   | B&H        | $349.95     | RTX 5060 Ti, 8 GB GDDR7                |
| Case            | MSI MAG FORGE 321R   | Newegg     | $84.99      | ATX Mid Tower, airflow design          |
| Power Supply    | MSI MAG A750GL       | Amazon     | $96.00      | 750W, 80+ Gold, fully modular          |
| Case Fan        | Noctua NF-A12x25 PWM | Amazon     | $37.95      | 120mm, high airflow                    |
| Case Fan        | Noctua NF-A12x25 PWM | Amazon     | $37.95      | 120mm, high airflow                    |
| **Total (before rebates)** |                      |            | **$1579.38** |                                        |
| Mail-in Rebates |                      |            | -$30.00     |                                        |
| **Final Total** |                      |            | **$1549.38** |                                        |


---

## 3. Local Manila Build
This build uses **locally available parts** from Manila vendors.
Google spreadsheet link: https://docs.google.com/spreadsheets/d/1jBNYJR_c-P8ae-f79BO1IlZDnWz0AtMGTB1KosIecSo/edit?usp=sharing

### Local Build Table
| Component       | Model                | Vendor     | Price (Php) | Compatibility Notes                                   |
|-----------------|----------------------|------------|-------------|-------------------------------------------------------|
| CPU             | AMD Ryzen 7 9800X3D  | Datablitz  | ₱29,950.00  | Works with AM5 motherboards.                          |
|                 |                      |            |             | Requires B650, X670, or newer chipset.                |
|                 |                      |            |             | Best paired with DDR5 RAM.                            |
| CPU Cooler      | MSI MAG CoreLiquid   | DataBlitz  | ₱2,195.00   | Fits case clearance.                                  |
| Motherboard     | MSI Pro B650M-A WIFI | Datablitz  | ₱9,450.00   | Supports AMD Ryzen 7 9800X3D with BIOS v7D75vA3.      |
|                 |                      |            |             | Update may be required.                               |
| RAM             | G.Skill Flare X5     | DynaQuestPC| ₱6,275.00   | DDR5-6000, 32GB (2 x 16 GB) CL36                      |
|                 |                      |            |             | TeamGroup also compatible.                            |
| Storage 1 (SSD) | MSI SPATIUM M480     | Microless  | ₱6,176.33   | Fully supported by motherboard’s PCIe 4.0 M.2 slots.  |
| Storage 2 (HDD) | Seagate BarraCuda    | EasyPC     | ₱2,060.00   | Additional bulk storage.                              |
| GPU             | MSI SHADOW 3X OC     | Datablitz  | ₱39,895.00  | Good for 4K gaming. GeForce RTX 5070 12 GB            |
|                 |                      |            |             | May struggle with very demanding titles.              |
| PSU             | MSI MAG A750GL       | Datablitz  | ₱4,750.00   | Sufficient for CPU & GPU.                             |
|                 |                      |            |             | 80+ Gold certified.                                   |
| Case            | MSI MAG FORGE 321R   | Datablitz  | ₱3,675.00   | ATX Mid-Tower, good airflow.                          |
| Case Fans       | Stock chassis fans   | —          | ₱0.00       | Included with case.                                   |
| **Total**       |                      |            | **₱104,426.33** | Within 105% of budget.                            |


---

## 4. Compatibility Justification 
TODO
For each part, explain compatibility and choices.  
Example:  
- **CPU + Motherboard**: Intel i5-13400F (LGA1700) works with ASUS B760M board (LGA1700 socket, BIOS compatible).  
- **RAM**: DDR5 RAM supported by motherboard slots (up to 128GB).  
- **GPU**: 

---

## 5. Budget Analysis
- **Budget Limit**: ₱105,000 (105% of 100,000)
- **Final Total**: ₱104,426.33
- ✅ Within budget
- Initially, we chose an 8GB GPU and added two aftermarket Noctua case fans, which brought the build to ₱k. However, since the tower already included four fans (3 front + 1 rear), we decided to use the stock fans instead. This gave room for the 12GB GPU that we chose, as further analysis showed that the previous 8GB GPU we chose could potentially bottleneck the performance of the PC. 5070 will ensure smooth 4K gaming even in demanding games.

---

## 6. Conclusion & Learnings
Reflections on:  
- Price differences (international vs. Manila vendors)
    Based on PC Part Picker, the total build is estimated to be lower when sourced internationally, around ₱10,000 less than Philippine-based parts. The prices from Philippine-based vendors are noticeably higher.
- Challenges in finding stock or cheaper equivalents
    Most of the credible PC parts sites listed parts with higher prices, and a lot of the "cheaper" listings were Shopee/Lazada stores with no reviews. There were also a few times we found a perfect part given its capabilities and budget, but it would be out of stock everywhere. When we finalized our build we were slightly over budget, so we had to go back and find cheaper equivalents for some parts. Luckily however we didn't require much trade-offs with the alternative parts we chose (CPU Cooler and RAM).
- What the group learned about PC components and system design  TODO

---
## 7. Video pitch
- Your video link here  TODO

## 8. References
- Vendor links (PCX, VillMan, etc.)  
    - TODO
- PCPartPicker build link 
    - https://pcpartpicker.com/list/zMKWkf
- Any technical documentation consulted
    - https://www.pcgamer.com/best-cpu-for-gaming/
    - https://www.msi.com/Graphics-Card/GeForce-RTX-5060-Ti-16G-VENTUS-2X-OC-PLUS
    - https://www.msi.com/Graphics-Card/GeForce-RTX-4070-Ti-SUPER-16G-GAMING-X-SLIM

