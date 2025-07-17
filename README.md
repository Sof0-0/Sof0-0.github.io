I am a fully-funded first year Master of Science & Engineering (MSE) student at [Princeton University's Computer Science Department](https://www.cs.princeton.edu/), advised by [Professor Elad Hazan](https://www.ehazan.com). 

I received a Bachelor of Science (BSc) degree (_Summa Cum Laude_) with Honors in Computer Science and Cybersecurity from the Tulane University, New Orleans. Upon my graduation I was inducted into the Phi Betta Kappa and Chi Alpha Sigma Honors Societies. 

My research experience spans machine learning, artificial intelligence, computer architecture, computer systems (focusing on OS and file systems), LLMs, and cybersecurity policy.  My current research interests are in **Spectral Control Theory**, **Online Learning and Optimization**, **Post-transformer Architectures**, **Algorithmic Decision-Making**, **AI and Education**, **Probability, Statistics and Machine Learning**, and **Data Science**.

<div style="text-align: center;">
<a href="mailto:sonikd2e3@gmail.com">Email</a> | <a href="assets/files/Resume_Full.pdf">CV</a> | <a href="https://www.linkedin.com/in/sofiia-druchyna-cs/">LinkedIn</a> | <a href="https://www.researchgate.net/profile/Sofiia-Druchyna">ResearchGate</a>
<p></p>
</div>

--------------
## Projects

**Efficient Spectral Control of Partially Observed Linear Dynamical Systems** (In Proceedings) 
[[arXiv]](https://arxiv.org/pdf/2505.20943) \
*Anand Brahmbhatt\*, Gon Buzaglo\*, Sofiia Druchyna\*, Elad Hazan* \
![ML/AI Badge](https://img.shields.io/badge/ML/AI-yellow) ![Control Theory Badge](https://img.shields.io/badge/Control%20Theory-darkblue) ![Online Learning](https://img.shields.io/badge/Online%20Learning-darkgreen)
- Proposed a new method for controlling linear dynamical systems under partial observation and adversarial disturbances. Our new algorithm, Double Spectral Control (DSC), matches the best known regret guarantees while exponentially improving runtime complexity over previous approaches in its dependence on the system's stability margin.
  
**A New Approach to Controlling Linear Dynamical Systems** (In Proceedings) 
[[arXiv]](https://www.arxiv.org/abs/2504.03952) \
*Anand Brahmbhatt\*, Gon Buzaglo\*, Sofiia Druchyna\*, Elad Hazan* \
![ML/AI Badge](https://img.shields.io/badge/ML/AI-yellow) ![Control Theory Badge](https://img.shields.io/badge/Control%20Theory-darkblue) ![Online Learning](https://img.shields.io/badge/Online%20Learning-darkgreen)
- Proposed a new method for controlling linear dynamical systems under adversarial disturbances and cost functions. Our algorithm achieves a running time that scales polylogarithmically with the inverse of the stability margin, improving upon prior methods with polynomial dependence maintaining the same regret guarantees.

**SpectraLDS: Distilling Spectral Filters into Constant-Time Recurrent Models** (In Proceedings)
[[arXiv]](https://arxiv.org/abs/2505.17868) \
*Devan Shah, Shlomo Fortgang, Sofiia Druchyna, Elad Hazan* \
![ML/AI Badge](https://img.shields.io/badge/ML/AI-yellow) ![Control Theory Badge](https://img.shields.io/badge/Control%20Theory-darkblue) ![LLMs Badge](https://img.shields.io/badge/LLM-darkpink) 
- Introduced the first method, SpectraLDS architecture, for system identification of a symmetric linear dynamical system with provable robustness guarantees and with performance independent of the effective memory of the system or state dimension of the underlying system.

**Language Models as Teaching Assistant Companions: Evidence from Experiments in a Proof-Based Course** (In Proceedings) \
*Romina Mahinpei\*, Sofiia Druchyna\** \
![ML/AI Badge](https://img.shields.io/badge/ML/AI-yellow) ![HCI Badge](https://img.shields.io/badge/HCI-silver)
![Computer Science Education](https://img.shields.io/badge/Computer%20Science%20Education-red) ![LLMs Badge](https://img.shields.io/badge/LLM-darkpink) 
- Introduced a mixed-methods framework for assessing the real-world impact of data-driven tools, focusing on how human decision-makers use algorithmic recommendations in high-stakes settings. Applied to the RCT of algorithm-assisted advising, we combined quantitative causal-effects analyses, conditional independence testing, and qualitative reviews to explore equity impacts and the role of advisor discretion in enhancing student outcomes beyond algorithmic insights.

**CHANE: A Human-Centered Framework for Integrating Interactive Theorem Provers into Proof Education** (In Proceedings) \
*Romina Mahinpei\*, Sofiia Druchyna\*, Xinran Bi\** \
![ML/AI Badge](https://img.shields.io/badge/ML/AI-yellow) ![HCI Badge](https://img.shields.io/badge/HCI-silver)
![Computer Science Education](https://img.shields.io/badge/Computer%20Science%20Education-red)
- Poster presented at iRAISE Workshop as a part of AAAI 2025 Conference in Philadelphia, PA.
- Explored the integration of interactive theorem provers (ITPs) into undergraduate proof-based Computer Science (CS) courses at Princeton University, emphasizing the importance of addressing stakeholder challenges and needs (CHANE) before implementing AI solutions. We highlight both the potential and limitations of ITPs, advocating for a human-centered approach to responsibly integrate AI tools into education, which can serve as a model for diverse educational contexts.

**Honors Thesis: "Enhancing Teaching Methods of File Systems from the Educational Perspective"** 
[[Paper]](https://library.search.tulane.edu/permalink/01TUL_INST/1jgl1pd/alma9945574993306326) \
![File Systems Badge](https://img.shields.io/badge/File%20Systems-green) ![Computer Science Education](https://img.shields.io/badge/Computer%20Science%20Education-red)
- Developed an innovative teaching approach that introduces undergraduate students to the concepts of file systems through hands-on experience. WaveFS is a new lab assignment for the Computer Systems and Networking class at Tulane University, focusing on creating a simple Unix-like file system using the File System in Userspace (FUSE) interface. The lab assignment involves implementing basic file system operations to read and write data, as well as manage directories and files.

**Predictive Models for Cyber Threat Trends Analysis** [[Code]](https://github.com/Sof0-0/CyberAttacks.github.io) [[Paper]](https://sof0-0.github.io/CyberAttacks.github.io/)\
![Data Science Badge](https://img.shields.io/badge/Data%20Science-blue) ![Cybersecurity Badge](https://img.shields.io/badge/Cybersecurity-purple) ![ML/AI Badge](https://img.shields.io/badge/ML/AI-yellow)
- Provided insights into cyber threat actors' behavior and motives using machine learning methods, particularly KNN classifiers as well as identified common cyberattack trends using advanced data science techniques. The findings can be used for predictive analysis of future cyber threats and to enhance global threat intelligence.

**MIPS R4000 Simulator for an 8-Stage Pipeline** [[Code]](https://github.com/Sof0-0/MIPS-R4000) \
![Computer Architecture Badge](https://img.shields.io/badge/Computer%20Architecture-pink) 
- Built a MIPS R4000 simulator (from the MIPS64 family) for an eight-stage pipeline. The processor uses deeper pipeline than the simple 5-stage design. This deeper pipeline allows it to achieve higher clock rates by decomposing the five-stage integer pipeline into 8 stages. Since the cache access stages are usually on the critical path, the extra pipeline stages come from decomposing the memory access stages to achieve more balanced pipeline stages.

**RISC-V Disassembler** [[Code]](https://github.com/Sof0-0/RISC-V-Disassembler) \
![Computer Architecture Badge](https://img.shields.io/badge/Computer%20Architecture-pink) 
- Built a disassembler that takes in a binary file (or a text file) as input and displays the equivalent RISC-V assembly instructions along with the binary code.


\* Authors contributed equally to this work.

--------------
## Publications

1. Craig P. Orgeron, William Rials, and Sofiia Druchyna. January 2025. _The AI-Driven State: How Government-as-a-Service Is Transforming Public Service._ International Journal of Electronic Government Research (IJEGR), 21(1), 1–24. [IGI Global Scientific Publishing](https://www.igi-global.com/article/the-ai-driven-state/381327).
   
--------------
## Professional Experience
**Software Development Engineer Intern**, _Amazon_ (Summer 2025) 
- AGI High Performance Computing Team.

**Program Analyst Intern (AppSec)**, _BeyondTrust_ (Spring 2024) 
- Improving the SAST operations for code scanning by analyzing the existing coverage gaps and researching alternative solutions to create effective operational processes and introduce more robust scanning methods. 
    
**IT Department Assistant**, _Tulane University_ (2022-2024) 
- Organizing and Executing Cybersecurity Competition Events.
- Managing Information Technology Departmental Operations.

--------------
## Teaching
I have had the privilege of contributing to the instruction of the following courses:

- **COS 324 Introduction to ML**, Princeton University (Assistant Instructor) (Spring 2025)
- **COS 316 Computer Systems Design**, Princeton University (Assistant Instructor) (Fall 2024)
- **CMPS 2300 Computer Systems and Networking**, Tulane University (Assistant Instructor) (2023-2024)
- **CPMPS 1600 Introduction to Computer Science II**, Tulane University (Teaching Assistant) (Spring 2023)



