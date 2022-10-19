# Size-Conforming-Arterial-Plaque-Eliminator-and-Lipid-Nanoparticle-Embedded-Silicone-Stent-for-CHD

Authors: Victoria Albanese, Brian Bishara, Matan Blitz, Cameron Erber, Yeonju Kim, Gloria Ni, Alice Zhou

## The Central Problem 
Coronary Heart Disease presents a major healthcare burden across the world, as it is the leading cause of mortality in the United States and third worldwide. According to the NIH, CHD accounts for roughly 25%, or 610,000 annual deaths in the US and 17.8 million annual deaths globally.

## Problem Statement
The SCRAPE–LNP aims to treat adults with CHD in a cost-effective, time-efficient, and non-invasive manner while minimizing vessel damage and restoring blood flow.

## Design Overview
The Size-Conforming Rotational Arterial Plaque Eliminator – Lipid Nanoparticles (SCRAPE-LNP) combines radial catheterization, a plaque removal device, a downstream filter, and the addition of a modified stent (see Appendix A). To remove plaque, a flexible blade travels along a helically-threaded guidewire by rotating along its threads. The blade’s flexibility allows it to uniquely conform to the width of the artery, allowing for optimal plaque removal and minimal damage to the artery walls as compared to existing solutions. As plaque is cut, it is contained within the device’s mesh body. There is also a filter that operates with a modified umbrella mechanism downstream of the blade, contributing to a bilateral filtration system for the plaque removal apparatus. After the plaque removal stage is complete, an expandable, silicone-coated stent is placed into the artery. Within nanopores on the silicone surface, there are lipid nanoparticles (LNPs) filled with mRNA encoding for endothelial nitric oxide synthase (eNOS), an enzyme that generates the vasoprotective molecule nitric oxide. This vasodilator mitigates the thrombosis and restenosis associated with existing stents.

<img width="593" alt="Screen Shot 2022-05-02 at 10 51 30 PM" src="https://user-images.githubusercontent.com/48959871/166402635-e789592c-06b4-4e9c-8194-369c797c4b84.png">

## The Final Prototype
The UltraVisor-C is a face shield. Figure 1 shows the final prototype of our device. The overall product has dimensions of 200mm x 170mm x 290mm, and weight of 916g. The battery holder is situated on top of the sanitation chamber, which is situated on top of the head. The chamber is divided into 2 compartments (one for inhaled air and the other for exhaled), both containing LED strips that act as a substitute for UV-C. Two fans turning in opposite directions direct air between the chamber and the visor. A detachable vinyl visor allows for full face visibility, and the elastic fabric and foam lining prevent air leakage. An adjustable hat helps fix the device on the head. It is detachable and can be replaced to fit the user’s preference.

The prototype used 3D-printed materials for the main structure with Open Source SLDPRT files. These printed parts are attached using epoxy, hot glue, and superglue. For the removable cloth parts, consisting of the hat and the sealing cloth, velcro strips help to attach them to the chamber and visor. Finally, the visor is removable, in case the user needs to eat, drink, or touch their face.

<img width="574" alt="SCRAPE-LNP" src="https://user-images.githubusercontent.com/104453485/196781342-21472471-eda4-48c6-9d33-4528e722b0f2.PNG">

YouTube link of how our prototype works: 
https://youtu.be/ixSwmfPEwCU

## Airflow Testing
Since we did not use real UV-C light, we conducted airflow testing to make sure that air is circulating well throughout the device. To do this, we measured the air being directed into the chamber and the air being directed out the other chamber. Data was collected with an airflow probe, and we placed this airflow probe over the openings of each of the chambers in the back at the same distance. We placed the probe in front of the inhale chamber for about 20 seconds until it had a steady reading, then did the same for the exhale chamber.

We ran 3 trials of this test and our results are shown below in Table 1. Our probe measured the flow rate in and flow rate out in cubed feet per meter. The flow rate in represents the air going into the chamber, while the flow rate out is the flow rate going out the other chamber. We were then able to calculate the volume of air collected in 1 min by making the necessary conversion, which was multiplying the flow rate by about 28. The target value we were trying to achieve is a volume of 6 L/min for both the air going in and the air going out, because that it the average volume that an adult breathes in and out in one minute. As you can see from Table 1 below, all 3 of our trials passed this test. 

<img width="644" alt="Table 1" src="https://user-images.githubusercontent.com/48959871/167058794-d19490d4-7b55-44f4-b871-4c1519b24243.png">


## Audibility Testing
We conducted audibility testing to measure how much the device affects audibility. For our testing procedure, we first recorded ourselves saying “UltraVisor-C” using voice memos. We played the recording and measured the decibel level it reached using an online decibel meter. Then, we measured the decibel level while a team member wore the device and played the voice memo from inside the visor. Since N95 masks have been proven to reduce speech audibility by about 2.7 decibels, the target value of reduction for each recording is ≤ 2.7 decibels. We conducted 3 trials of this process, and the data is shown below in Table 2. We calculated the average of all 3 trials and then calculated the difference. There was only a 1.867 dB reduction between wearing the device versus speaking normally, so our prototype passed this test. 

<img width="635" alt="Table 2" src="https://user-images.githubusercontent.com/48959871/167058807-2384e6a5-dbd0-4815-9f57-6e36534a7b99.png">

## Comfortability Testing
In our Comfortability test, we asked 22 people of varying head sizes to wear the device and rate their opinions on a user defined scale, and we then calculated the average of all the ratings according to our User Defined Scale (Table 3). The target value was an average rating of ≥ 4, which specified that the device is easier to breathe in than an N95 mask and components do not get in the way of work. Our final average rating was 3.7, so the device failed the test, and we cannot conclude that the device is comfortable to wear.

<img width="644" alt="Table 3" src="https://user-images.githubusercontent.com/48959871/167058832-af7bb549-d1d4-4f10-a2e0-006f8eb81f39.png">

## Safety and Battery Life
In our Safety test, we first rubbed a balloon across the device surface to ensure that there were no sharp corners, and it did not pop. Secondly, we observed whether electrical wires are exposed on the exterior, and they are not. Thirdly, we ensured that the battery is fully covered and not potentially exposed to sunlight. We repeated the test twice to account for regions that may have been missed by the balloon or battery areas and wires that may have been missed. The device passed all rounds of testing, so we conclude that our device is safe to use. 

In our Battery Life test, we calculated the battery life from our data, given in terms of voltage, milliamp hours. Since it is a straightforward calculation, we performed this test only once. The target battery life is ≥ 8 hours because we assume hospital staff will have a break every 8 hours. The calculated battery life of our device was 32.5 hours, so our device passed the test, and we can conclude that the battery does not need to be recharged during a single shift.

## Limitations and Feasbility
While SCRAPE-LNP offers numerous advantages compared to existing solutions, it also has some limitations that need to be acknowledged. The use of novel technologies such as the size-conforming blade, downstream filter, and rotating body prevent the determination of overall feasibility. The mechanisms of each component must be experimentally tested in order to ensure that the device can function as a single, cohesive unit without harmful complications.
Both the lateral and rotational velocities of the blade must be determined, since they are directly related to thermal damage of the artery. An optimal velocity for removing plaque while limiting thermal damage can be determined by testing different velocities with an artificial artery model. Since we have no similar reference, the rotational velocity of the blade must be determined experimentally. Once the optimal blade velocity is found with which the blade effectively breaks apart the plaque without causing thermal damage to the artery, the rotational velocity of the body can easily be found by using a 5 to 1 ratio, which is the ratio of the pitches of the blade and body (1.27 mm and 0.254 mm, respectively). The linear velocity of the body can also be determined from the rotational velocity, since it moves 0.254 mm laterally for every rotation. This value was also determined from the body screw thread pitch of 0.254 mm. Since the body of the device is rigid and does not conform to the diameter of the artery wall in the way the helical blade does, there is a chance that the plaque that is cut may fall through the space between the vessel wall and cylindrical body. Due to the rotational motion of the blade, we assumed that the cut plaque will be swept by the blade radially inward and that plaque moving in other directions is extremely unlikely, which prevents it from leaving the plaque removal system. If future testing reveals that plaque escapes through the gap between the device body and artery wall, then another upstream filter will be implemented on the surface of the body opposite to the blade in order to capture excess plaque.
In addition, while research suggests the possibility of drug loading on the silicone rubber membrane and adsorption of phospholipids on silicone particles,39 a clear mechanism that stabilizes the interaction between the silicone pores and lipid nanoparticles needs to be defined. As suggested in the previous section, a covalent attachment with PEG linker is one possibility, as PEG is also a part of the outer membrane of the lipid nanoparticles. However, other methods such as oxidation and electrostatic adsorption should be analyzed as well while testing the surface chemistry.40 Additional experimental variables include the pore size, the number of pores, and the concentration of LNPs in each pore. These quantities determine the drug release rate and must be established experimentally. Another limitation is the cost of the device. One of the design goals for SCRAPE–LNP was to reduce the cost in order to make the device more financially accessible. However, it is unclear if the cost of the device will be less than the set target value of $9,345 (see Table 1),13 mainly because the manufacturing process of LNPs is very expensive.56 Furthermore, while our device is expected to reduce distal embolization and increase plaque removal relative to existing solutions, the lingering risk of thrombosis and restenosis cannot be overlooked, since the plaque cannot be completely removed, and a stent remains in the artery post-procedure.

## Future Work
For future teams that plan on continuing this project, we hope that our prototype's current limitations can be addressed. First, to address the issue of muffled speech, a microphone speaker system could possibly be implemented in the device. Second, for issues regarding adjustability, different visor sizes could be made for individuals who have larger or smaller head sizes. Lastly, to address the issue of comfortability and dropping battery voltage, a smaller, rechargeable battery could be used to reduce weight on top of the user's head. 

The modified CAD files we created are added to this post, as well as photos of our prototypes. 

## References
https://www.uvisor.org/

https://doi.org/10.1086/503643

https://www.mdpi.com/1996-1944/13/15/3363/htm

https://doi.org/10.37624/ijert/13.7.2020.1562-1566

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7882915/

https://www.sciencedirect.com/science/article/pii/S1477893920302301

https://doi.org/10.1063/5.0022968

## Acknowledgements
Instructor: Dr. Renata Ramos

Presentation Mentor: Dr. Tracy Volz
