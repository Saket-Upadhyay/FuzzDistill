![](docs/bannerdistill.png)

# FuzzDistill: Intelligent Fuzzing Target Selection using Compile-Time Analysis and Machine Learning

## Abstract

Fuzz testing is a fundamental technique employed to identify vulnerabilities within software systems. However, the
process can be protracted and resource-intensive, especially when confronted with extensive codebases. In this work, I
present FuzzDistill, an approach that harnesses compile-time data and machine learning to refine fuzzing targets. By
analyzing compile-time information, such as function call graphs' features, loop information, and memory operations,
FuzzDistill identifies high-priority areas of the codebase that are more probable to contain vulnerabilities. I
demonstrate the efficacy of my approach through experiments conducted on real-world software.

## Modules

| Module                                                           | Description                              | GitHub                                                                                  |
|------------------------------------------------------------------|------------------------------------------|-----------------------------------------------------------------------------------------|
| **FuzzDistillCC**                                                | Compiler back-end for feature extraction | [github/Saket-Upadhyay/FuzzDistillCC](https://github.com/Saket-Upadhyay/FuzzDistillCC)  |
| **FuzzDistillML**                                                | Model training component                 | [github/Saket-Upadhyay/FuzzDistillML](https://github.com/Saket-Upadhyay/FuzzDistillML) |
| **FuzzDistillWeb** | Prediction front-end                     | [github/Saket-Upadhyay/FuzzDistillWeb](https://github.com/Saket-Upadhyay/FuzzDistillWeb)                                    |

## Paper

| What         | Where                                                                      |
|--------------|----------------------------------------------------------------------------|
| PDF          | TBD                                                                        |
| arXiv        | TBD                                                                        |
| Presentation | [Presentation.pdf](docs/Upadhyay_Saket_Fuzzpiler_project_presentation.pdf) |

---

### Acknowledgement

This project was facilitated by the opportunities provided in the graduate class ``CS 6501: Software Security Testing'',
led by Dr. Jack Davidson, Dr. Jason Hiser, and Dr. Anh Nguyen-Tuong at the University of Virginia.
I would like to express my sincere gratitude to all the instructors for creating an environment that fostered
exploration and innovation, enabling me to delve into the intersection of fuzz testing and machine learning. The
guidance and support received throughout the course were instrumental in shaping this project.

---

> _Not peer-reviewed; I mean, my peers did review it though, so idk :D_