# BtBank: A Web Platform for Streamlining _Bacillus thuringiensis_ Protein Prospecting

<p align="justify">
Bacillus thuringiensis is a bacteria that produces pesticidal proteins essential for biological pest control. The development of Bt-based products relies on the discovery of new strains, toxins and specific targets. For this reason, we have developed a web platform designed to assist in managing data and analyses for Bt strains and pesticidal protein prospecting programs.
</p>

<p align="justify">
The workflow of prospecting programs involves several stages, from sample collection to toxin identification. The process starts with collection of samples, Bt strain isolation and storage. Then, the strains are grown in culture and the proteins are extracted and purified for the analyses of protein profiles either on vegetative and sporulative phase, along with characterization of the crystal produced during the sporulation phase. Bioassays are performed to determine the toxicity of the proteins against specific targets. Finally, the strains are sequenced and the toxins are identified.
</p>

<p align="justify">
The software was developed in Python, the micro web framework Flask was used for backend development, and the frontend was built using mainly HTML and some of JavaScript. The Platform storage is managed by a PostgreSQL database. These components are containerized using Docker, which allows the software to be easily deployed in different environments.
</p>

<p align="justify">
BtBank addresses the need for a centralized platform that integrates multiple stages of the prospecting process, from sample collection to toxin identification. The platform provides a range of functionalities, including user management with role-based access control, data registration for samples, isolates, protein profiles, bioassays, sequencing data, toxins, and targets. Furthermore, BtBank features a comprehensive logging system to track user actions, ensuring data integrity and accountability.
</p>

<p align="justify">
Future developments aim to enhance the platform by implementing a knowledge base process, automated pipelines, and an interactive map of sample collection regions. In summary, BtBank is a valuable tool for researchers in Bacillus thuringiensis in pesticidal protein prospecting.
</p>
