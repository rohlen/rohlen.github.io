---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* Peer-reviewed publications
------
1.	Rohlén, R., Lubel, E., Sgambato, B.G., Antfolk, C., & Farina, D. (2023). Spatial decomposition of ultrafast ultrasound images to identify motor unit activity – A comparative study with intramuscular and surface EMG. Journal of Electromyography and Kinesiology, 73, 102825.
2.	Lubel, E., Sgambato, B. G., Rohlén, R., Ibáñez, J., Barsakcioglu, D. Y., Tang, M. X., & Farina, D. (2023). Non-linearity in motor unit velocity twitch dynamics: Implications for ultrafast ultrasound source separation. IEEE Transactions on Neural Systems and Rehabilitation Engineering, 31, 3699-3710.
3.	Rohlén, R., Carbonaro, M., Cerone, G.L., Meiburger, K. M., Botter, A., & Grönlund, C. (2023). Spatially repeatable components from ultrafast ultrasound are associated with motor unit activity in human isometric contractions. Journal of Neural Engineering, 20(4), 046016.
4.	Grönlund, C., & Rohlén, R. (2023). Ultrafast ultrasound imaging can be used to access single motor units in deep muscles, but the underlying biomechanical source remains to be understood. Journal of Electromyography and Kinesiology, 71, 102797.
5.	Rohlén, R., Lundsberg, J., Malesevic, N., & Antfolk, C. (2023). A fast blind source separation algorithm for decomposing ultrafast ultrasound images into spatiotemporal motor unit kinematics. Journal of Neural Engineering, 20(3), 034001.
6.	Rohlén, R., Lundsberg, J., & Antfolk, C. (2023). Estimating the neural spike train from an unfused tetanic signal of low threshold motor units using convolutive blind source separation. BioMedical Engineering OnLine, 22(1), 10.
7.	Rohlén, R., Jiang, B., Nyman, E., Wester, P., Näslund, U., & Grönlund, C. (2023). Interframe Echo Intensity Variation of Subregions and Whole Plaque in Two‐Dimensional Carotid Ultrasonography: Simulations and In Vivo Observations. Journal of Ultrasound in Medicine, 42(5), 1033-1046.
8.	Rohlén, R., Antfolk, C., & Grönlund, C. (2022). Optimization and comparison of two methods for spike train estimation in an unfused tetanic contraction of low threshold motor units. Journal of Electromyography and Kinesiology, 67, 102714.
9.	Rohlén, R., Raikova, R., Stålberg, E., & Grönlund, C. (2022). Estimation of contractile parameters of successive twitches in unfused tetanic contractions of single motor units–A proof-of-concept study using ultrafast ultrasound imaging in vivo. Journal of Electromyography and Kinesiology, 67, 102705.
10.	Ali, H., Umander, J., Rohlén, R., Röhrle, O., & Grönlund, C. (2022). Modelling intra-muscular contraction dynamics using in-silico to in-vivo domain translation. BioMedical Engineering OnLine, 8, 170595-170608.
11.	Rohlén, R., Yu, J., & Grönlund, C. (2022). Comparison of decomposition algorithms for identification of single motor units in ultrafast ultrasound image sequences of low force voluntary skeletal muscle contractions. BMC Research Notes, 15, 207.
12.	Rohlén, R., Stålberg, E., & Grönlund, C. (2020). Identification of single motor units in skeletal muscle under low force isometric voluntary contractions using ultrafast ultrasound. Scientific Reports, 10(1), 22382.
13.	Ali, H., Umander, J., Rohlén, R., & Grönlund, C. (2020). A Deep Learning Pipeline for Identification of Motor Units in Musculoskeletal Ultrasound. IEEE Access, 8, 170595-170608.
14.	Rohlén, R., Stålberg, E., Stöverud, K. H., Yu, J., & Grönlund, C. (2020). A Method for Identification of Mechanical Response of Motor Units in Skeletal Muscle Voluntary Contractions using Ultrafast Ultrasound Imaging—Simulations and Experimental Tests. IEEE Access, 8, 50299-50311.

* Preprints
------
15.	Lubel, E., Rohlén, R., Sgambato, B.G., Barsakcioglu, D.Y., Ibáñez, J., Tang, M.X., & Farina, D. Accurate Identification of Motoneuron Discharges from Ultrasound Images Across the Full Muscle Cross-Section. Currently under review in IEEE Transactions on Biomedical Engineering.

* Conference abstracts
------
16.	Rohlén, R., Carbonaro, M., Botter, A., Grönlund, C., & Antfolk, C. (2023). Quantifying the spatial distribution of individual muscle units using high-density surface EMG and ultrafast ultrasound. In the 28th Annual Congress of the European College of Sport Science, July 4-7.
17.	Rohlén, R. (2022). Identification of motor units using ultrasound – From muscle to neural interface. In RehabWeek, Rotterdam, The Netherlands, July 25-29.
18.	Rohlén, R., Stålberg, E., Yu, J., & Grönlund, C. (2020). Imaging recruitment of motor units in voluntary skeletal muscle contractions using decomposition and ultrafast ultrasound imaging: A pilot study. In XXIII ISEK, International Society of Electrophysiology and Kinesiology, Virtual Congress, July 12-14, 2020 (pp. 141-142). International Society of Electrophysiology and Kinesiology.
19.	Rohlén, R., Stålberg, E., & Grönlund, C. (2019). Ultrafast Ultrasound Imaging of Motor Units in Skeletal Muscle during Voluntary Contractions–A Pilot Validation Study by using Needle-EMG. In the 41st International Engineering in Medicine and Biology Conference, Berlin, Germany, July 23-27, 2019.
20.	Rohlén, R., Stålberg, E., Stöverud, K. H., Yu, J., & Grönlund, C. (2018). Ultrasound-based Imaging of Motor Units in Skeletal Muscle Tissue. In the Annual Swedish National Meeting for Biomedical Engineering, Umeå, October 9-10.
21.	Rohlén, R., Stöverud, K. H., Yu, J., & Grönlund, C. (2017). Segmentation of Motor Unit Territories in Ultrasound Image Sequences of Contracting Skeletal Muscle Tissue. In the Annual Swedish National Meeting for Biomedical Engineering, Västerås, October 10-11.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
