---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can find all of my articles on [Google Scholar](https://scholar.google.com/citations?user=sSAQkAgAAAAJ&hl=en&oi=ao).

Selected publications are below:

<style>
  ul li {
    margin-bottom: 2px;  /* Decreases the space between different bullets */
    padding-bottom: 0px; 
    line-height: 1.35;   /* Tightens the text lines inside a single bullet */
  }
</style>

* Mathuros, Kornkamon, Sarad Venugopalan, and **Sridhar Adepu**. "WaXAI: Explainable Anomaly Detection in Industrial Control Systems and Water Systems." In *Proceedings of the 10th ACM Cyber-Physical System Security Workshop*, pp. 3-15. 2024. <span style="color: #0056b3; font-weight: bold;">🏆 Awarded Best Paper Award</span>
* Alfageh, Alyah, **Sridhar Adepu**, and Charalambos Konstantinou. "Water Risk-Proofed: Risk Assessment in Water Desalination." In *Proceedings of the 5th Workshop on CPS&IoT Security and Privacy*, pp. 11-23. 2023.
* Zhu, Yuqing, **Sridhar Adepu**, Kushagra Dixit, Ying Yang, and Xin Lou. "Adversarial attacks and mitigations on scene segmentation of autonomous vehicles." In *European Symposium on Research in Computer Security*, pp. 46-66. 2022.
* **Sridhar Adepu**, Nianyu Li, Eunsuk Kang, and David Garlan. "Modeling and analysis of explanation for secure industrial control systems." *ACM Transactions on Autonomous and Adaptive Systems* 17, no. 3-4 (2022): 1-26.
* Balaji, Madhumitha, Siddhant Shrivastava, **Sridhar Adepu**, and Aditya Mathur. "Super Detector: An Ensemble Approach for Anomaly Detection in Industrial Control Systems." In *International Conference on Critical Information Infrastructures Security*, pp. 24-43. 2021. <span style="color: #0056b3; font-weight: bold;">🏆 Awarded the Critical Infrastructures Preparedness and Resilience Research Network (CIPRNET) Young CRITIS Award</span>
* Tanmoy Kanti Das, **Sridhar Adepu**, and Jianying Zhou. "Anomaly Detection in Industrial Control Systems using Logical Analysis of Data." *Computers & Security*, 2020.
* **Sridhar Adepu**, Luis Garcia, Ferdinand Brasser, Michael Rodler, Lucas Davi, Ahmad Reza Sadeghi, and Saman Zonouz. "Control Behavior Integrity for Distributed Cyber-Physical Systems." In Proceedings of the *11th ACM/IEEE International Conference on Cyber-Physical Systems (ICCPS)*, 2020.
* **Sridhar Adepu**, Nandha Kumar Kandasamy, Jianying Zhou, and Aditya Mathur. "Attacks on smart grid: Power supply interruption and malicious power generation." *International Journal of Information Security* 19, no. 2 (2020): 189-211.
* **Sridhar Adepu**, Nandha Kumar Kandhasamy, and Aditya Mathur. "EPIC: An Electric Power Testbed for Research and Training in Cyber Physical Systems Security." In *4th Workshop On The Security Of Industrial Control Systems & Of Cyber-Physical Systems (CyberICPS 2018)*.
* **Sridhar Adepu** and Aditya Mathur. "Distributed Attack Detection in a Water Treatment Plant: Method and Case Study." *IEEE Transactions on Dependable and Secure Computing*, 2018.
* Giedre Sabaliauskaite and **Sridhar Adepu**. "Integrating Six-Step Model with Information Flow Diagrams for Comprehensive Analysis of Cyber-Physical System Safety and Security." In *IEEE 18th International Symposium on High Assurance Systems Engineering (HASE)*, Singapore, 2017.
* **Sridhar Adepu**, Jonathan Goh, Khurum Nazir Junejo, and Aditya Mathur. "A Dataset to Support Research in the Design of Secure Water Treatment Systems." In *The 11th International Conference on Critical Information Infrastructures Security*, 2016. <span style="color: #0056b3; font-weight: bold;">🏅 Finalist Award for CIPRNET Young Critis Award CYCA (by European Union)</span>
* Eunsuk Kang, **Sridhar Adepu**, Daniel Jackson, and Aditya Mathur. "Model-Based Security Analysis of a Water Treatment System." In *2nd International Workshop on Software Engineering for Smart Cyber-Physical Systems (SEsCPS)*, pp. 22-28, @ ICSE 2016.
* **Sridhar Adepu** and Aditya Mathur. "Distributed Detection of Single-Stage Multipoint Cyber Attacks in a Water Treatment Plant." In *11th ACM on Asia Conference on Computer and Communications Security (ASIACCS 2016)*, Xi'an, China, pp. 449-460, 2016.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{*
<!--
Impact:
======

My research efforts have led to high impact research outputs such as patents (x3), research publications (70+, 5x best paper awards, 4000+ Citations), training deliveries (15+ to government agencies), workshops (10+) and teachings (300+ advanced students, Best Teaching Awards).

<style>
  ul li {
    margin-bottom: 3px;  /* Decreases the space between different bullets */
    padding-bottom: 0px; 
    line-height: 1.35;   /* Tightens the text lines inside a single bullet */
  }
</style>

* Security Assurance of Semiconductor Manufacturing (SASM) project (funded by EPSRC-UK) helped audit and assurance processes in the
semiconductor industry across the globe, and we engaged more than 32 global companies for this work. [SEMI](https://www.semi.org/en/industry-groups/semiconductor-cybersecurity) is publishing our work as a policy in the global semiconductor ecosystem.
* I led Industrial Internet of Things and Industrial Control System Security units in the MSc Cyber Security (Infrastructure
Security) programme. I also led the Resilient Infrastructures unit in the interdisciplinary doctoral programme.
* I am also actively collaborating with industrial partners (Synoptix, Airbus, Qinetiq, Siemens) in CPS security.
* Invited to give a keynote at Cybersecurity Education and Research Conference (CERC), Kuwait by British Embassy, 2023 and 2024.
* I was awarded [NCSC RITICS](https://www.ncsc.gov.uk/blog-post/ritics-securing-cyber-physical-systems) fellowship as thought leader in the UK within the CPS security. A key outcome is the [NCSC blog](https://www.ncsc.gov.uk/blog-post/digital-twins-secure-design-development) post on Digital Twins: secure design and development, establishing foundational [security guidance](https://www.dataguidance.com/news/uk-ncsc-publishes-blog-secure-design-and-development) for the sector. By integrating security-by-design into policy and practice, the fellowship strengthens research infrastructure and human capital, ensuring the safe, sustainable adoption of Smart Nation technologies while addressing vital national security needs through global thought leadership.
* Actively involved in **research led startups** in CPS security; 1) Head of research in Reperion (now [Cequra](https://cequra.io/)), Singapore based maritime security startup where we designed, developed and deployed asset scanning tools and attack detection monitors in real-world ships with clients. 2) Founder & Chied Scientist at [ILLUSIONIQ](https://www.illusioniq.com/), delivering a cutting edge deception platform for CNI security that anticipate and neutralise emerging threats. <!-- We raised investments to grow team size to 9 members for the product development and maintenance. Apart from the successful client side deployments, we also secured an InnovateUK funding to further advance the deception technology into offshore energy systems.-->
* Collaborative projects with Synoptix, where research on cyber attack detection has been translated into deployable capabilities for operational systems. These efforts demonstrate how fundamental research can evolve into practical tools adopted by industry, strengthening national resilience while creating economic value. Our work helped Synoptix to build a seven-member team in cyber security which is an example of job creation.
* I actively engage with policy and standards discussions, including work on EV charging infrastructure security together with REA [(Renewable Energy Association)](https://www.r-e-a.net/resources/rea-launches-cybersecurity-report-launch/), ensuring research insights inform regulatory and strategic decision-making.
*  Operationalize the world’s  unique  cyber  security  testbeds  at  the  iTrust,  supported  by MINDEF  and  NRF  Singapore.  Testbeds include [water treatment](https://itrust.sutd.edu.sg/itrust-labs-home/itrust-labs_swat/), [water distribution](https://itrust.sutd.edu.sg/itrust-labs-home/itrust-labs_wadi/) and [smart grid](https://itrust.sutd.edu.sg/itrust-labs-home/itrust-labs_epic/).
* I was involved in designining innovative  curriculum  for  generating  cyber  security  leaders  through  university education. An example of this course [‘51.508’](https://istd.sutd.edu.sg/courses/mssd/secure-cyber-physical-systems/) at SUTD designed for masters student of Security by Design where I co-developed the content  and lab  experiments to  train security  professionals.
* I  have designed  and organized  workshops for  government  agencies  such  as  [public  utility  board](https://www.pub.gov.sg/)  in Singapore on  CPS security to train them under smart nation initiative.
* To serve the broader research community, I have produced the first [dataset](https://itrust.sutd.edu.sg/itrust-labs_datasets/)  for  CPS  security  from  an  operational  real-time  CPS  which  is  downloaded  and  used  by  more  than  8000 researchers from more than 100 countries across the globe.
* Patents: [Distributed attack detection in ICS](https://patents.google.com/patent/US20200311283A1/en), [Method of detecting cyber attacks](https://patents.google.com/patent/US20200162482A1/en) and [Defense system and method against cyber-physical attacks](https://patents.google.com/patent/US20190253440A1/en).
* Co-Organised and participated in world unique [security exercises](https://itrust.sutd.edu.sg/ciss-2019/) in industrial systems called CISS(Critical Infrastructure Security Showdown). So far event is organised in [2016](https://itrust.sutd.edu.sg/scy-phy-systems-week/2016/s3/), [2017](https://itrust.sutd.edu.sg/scy-phy-systems-week/2017-2/s317-event/), [2019](https://itrust.sutd.edu.sg/ciss-2019/), [2020](https://itrust.sutd.edu.sg/ciss-2020-ol/).  
* [Crossed Swords 2020](https://ccdcoe.org/news/2020/exercise-crossed-swords-2020-reached-new-levels-of-multinational-and-interdisciplinary-cooperation/): [iTrust@SUTD](https://itrust.sutd.edu.sg/news-events/news/crossed-swords-2020/) was invited to the 6th iteration of the annual cyber exercise Crossed Swords in Riga, Latvia which brought together more than 120 technical experts, Cyber Commands’ members, Special Forces operators and military police. -->*}

Collaborations:
======

  I have  collaborated  with  world’s  leading  scientists  from  the following universities:
  
  * MIT
  * CMU
  * UIUC
  * Georgia Tech
  * TU Darmstadt
  * TU Delft
  * KAUST
  * Imperial
  * Bath
  * Newcastle
  * Bristol
  * SUTD
  * Peking
  * Zhejiang
