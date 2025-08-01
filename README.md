# Laser Passthrough Lenses
These are an alternative to standard laser glasses when working with high powered or supercontinuum lasers. 

With lasers of sufficient power, glancing blows or even the laser dot on a wall can be intense enough to cause permanent eye damage before our blink reflexes can save us. Traditionally to mitigate these risks, laser glasses that attenuate the light of the specific wavelengths being worked with are used. For example, when working with 10W 450nm diodes, one must use ~OD7 goggles rated for 450nm light. These goggles then reduce the amount of 450nm light that pass through them by a factor of 10^7, making working with the laser eye-safe. 

This poses a problem when working with lasers of such power where eyewear may be impossible to make or extremely expensive and fragile, namely large pulsed lasers reaching gigawatts or even terawatts of power. This will only pose a larger issue in the future, as more and more powerful lasers are continually being built. 
Another area in which traditional laser safety goggles are limited is when working with supercontinuum lasers, particularly those that may emit light across the entire visible spectrum. No laser goggles can block all visible light and still achieve their goal of letting the user actually see for obvious reasons. 

In these cases, cameras are often utilized to safely work with the lasers, however it can be cumbersome without a dedicated system or only work remotely. 

I made this project as a proof of concept for LaPL, Laser Passthrough Lenses that fully cover they eyes and use cameras mounted on a headset to stream POV video onto screen mounted near the eyes, similar to a VR headset. This uses FPV goggles and 3D printed mounts for both a head and wireless camera system, however a future version will use specifically designed housings, PCBs, and mounts. This project is simply to test whether a headset style laser goggle is comfortable, easy, and intuitive to work with over trasitional laser glasses using a cheap FPV headset and mid-tier FPV cameras. 


Complete Setup:

<img width="845" height="639" alt="image" src="https://github.com/user-attachments/assets/0650a664-bef4-4ded-a352-06ab0b59e2e1" />


Wireless Mount (with battery and camera modeled):

<img width="697" height="700" alt="image" src="https://github.com/user-attachments/assets/e52d2062-fcb9-4a66-888c-5b2f427e1701" />


Wired Mount (without cabling and headset):

<img width="632" height="644" alt="image" src="https://github.com/user-attachments/assets/43a4736d-41b3-4e28-8db8-115b39a39174" />




BOM:
|Item Name|Price|Amazon Link|
|----------|-------|--------|
|ARRIS VR-009|$78.09|https://www.amazon.com/5-8Ghz-Goggles-Arris-VR-009-Headset/dp/B07DGB252B|
|RCA to AV Adapter|$5.33|https://www.amazon.com/Adapter-Video-Component-Cable-Replacement/dp/B08NV48MHP?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A27H62YKOAOIF7&gQT=1|
|RunCam FPV Camera|$23.52|https://www.amazon.com/RunCam-Camera-800TVL-Switchable-Quadcopter/dp/B08M38C1DM?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1CA0481MF6RWW&gQT=2|
|WT03 VTX|$32.09|https://www.amazon.com/Wolfwhoop-Adjustable-Transmitter-Cloverleaf-Aircraft/dp/B06XB2ZRBP?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1738MU39IWURM&gQT=1|
|LiPO|Already Own|N/A|
|Wires|Already Own|N/A|
|Battery Pack|Already Own|N/A|

Prices with tax as of 7/28/25

Connections:
Connect a LiPO Battery to the wireless VTX and connect the wired camera to the RCA to AV adapter (yellow is data, black is ground, power camera seperately through red cable)
