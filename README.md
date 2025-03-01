# Personal Introduction

I am a PhD student at **Harbin Institute of Technology (Shenzhen)**, enrolled in September 2023. My email is 23B954005@stu.hit.edu.cn, and my Google Scholar profile can be found at [https://scholar.google.com.hk/citations?user=d9qEdQIAAAAJ&hl=zh-CN](https://scholar.google.com.hk/citations?user=d9qEdQIAAAAJ&hl=zh-CN). If you are interested in the following areas of my research, please feel free to contact me if you are interested in collaborating or sharing insights on these topics.

My doctoral research focuses on **Structural Health Monitoring (SHM)**, a rapidly growing interdisciplinary field that integrates concepts from mechanics, aerospace engineering, civil engineering, control systems, and signal processing. The primary objective of SHM is to assess and continuously monitor the structural performance and state changes of engineering systems, with the main research subjects being mechanical systems, spacecraft, and transportation infrastructure. The primary goal is similar to health monitoring in medical devices, with the key difference being the subject of study.

Currently, my research is concentrated in the following key areas:

- **Data-driven linear/nonlinear system identification**: I am exploring methods for identifying the dynamics of structures using data, including both linear and nonlinear systems. This work aims to enhance the accuracy and reliability of system models by using available observational data.

- **Model order reduction**: This involves developing techniques to simplify complex system models without significantly compromising accuracy, allowing for more efficient simulations and real-time applications.

- **Online system state estimation**: My research also addresses the challenge of continuously estimating the state of a system in real-time using sensor data, which is crucial for proactive maintenance and performance evaluation.

- **Modal identification**: I focus on identifying the modal parameters of structures, such as natural frequencies and mode shapes, which are essential for understanding their dynamic behavior and health status.

The theoretical foundation of my work is based on the **Koopman operator** and **optimal estimation** techniques, rooted in applied mathematics and statistical signal processing. One focuses on solving nonlinear problems, while the other addresses robustness against noise. While these theories offer elegant mathematical frameworks, translating them into practical applications can be challenging due to the fact that real-world observation data is often discrete and typically lacks accurate prior physical information. To bridge the gap between theory and practice, I employ **convex optimization methods** to develop efficient algorithms that can be applied to real-world problems in SHM.

---

## Key Research Directions and Technical Approaches

### 1. **System Identification Based on Stochastic Subspace Methods**
This approach originally stems from control theory, primarily relying on the orthogonality between the signal subspace and the noise subspace to eliminate noise and achieve high-precision system identification. By assuming the noise is white noise and that the system state vector and noise exhibit ergodic properties, this method guarantees convergence to the state-space equation estimate with completely removed noise when the monitoring data is infinite.

I apply this method to data-driven modeling of monitored structures, and it can also have broad applications in high-precision system modeling and signal processing. This approach enables the extraction of true system dynamics from noisy data, providing an effective solution for engineering problems that require precise identification and control.

### 2. **Nonlinear System Identification Based on Koopman Operator Theory**
This method relies on the Koopman operator theory, where the state vector of a dynamic system is mapped into a high-dimensional (and potentially infinite-dimensional) space, seeking a linear representation within that space. This approach is similar to Kernel methods, and I consider it an extension of classical linear state-space models. Since state-space equations can also be viewed as a method of mapping monitoring data into high-dimensional space, the entire process is linear, but the observation function of the Koopman operator can be arbitrary. Given its strong mathematical foundation, this method provides new ways to interpret the dynamic characteristics of systems and is well-suited for integration with control methods like Model Predictive Control (MPC).

I use it to solve some very complex system identification problems with highly nonlinear characteristics. It is highly effective in nonlinear system identification and is currently emerging as a popular and modern research topic. This method has proven highly effective for solving complex nonlinear systems that are difficult to address with traditional approaches. It provides a powerful tool for analyzing and controlling dynamic systems, with vast potential for real-world applications. Particularly in fields such as aerospace, robotics, and intelligent transportation, it holds great promise for advancing system identification and control strategies.

### 3. **Optimal Estimation**
In practice, monitoring data is often contaminated by noise. To evaluate the statistical performance of estimators derived from such data, it is essential to model the noise.
Optimal estimation is a mathematical technique used to estimate the system state, with the aim of achieving the most accurate estimation using available observation data, system models, and noise characteristics. The objective is to minimize the variance of the estimation error, typically achieved through methods like least squares and Kalman filtering. Optimal estimation is widely used in dynamic systems for real-time state tracking and has broad applications in fields such as control systems, signal processing, and communications.

In recent years, however, this approach may have lost its prominence, largely due to the powerful nonlinear modeling capabilities of deep neural networks and the increasing computational support from companies like NVIDIA. Research focus has increasingly shifted toward deep learning. In such cases, analyzing the statistical performance of estimators becomes challenging. Nevertheless, I continue to analyze it through optimal estimation theory because, for certain applications, the well-established mathematical foundation of optimal estimation provides a robust framework for understanding and enhancing estimation accuracy.

### 4. **Data-driven Model Order Reduction**  
Model order reduction is a popular research direction in fields such as computational fluid dynamics, especially in the context of high-dimensional fluid data generated from simulations. This technique effectively reduces computational load. However, for real-world sensor sampling systems, the ability to obtain high-dimensional data remains uncertain. Additionally, ensuring the generalization ability of data-driven reduction methods is still a major challenge, particularly under different boundary conditions and initial conditions.

In my research, I am focused on addressing how to apply data-driven reduction techniques in different physical environments and complex real-world conditions. This requires maintaining accuracy while adapting to various system settings. Therefore, a core issue in my research is developing effective data processing methods to reduce model complexity while ensuring the applicability and stability of the model.

### 5. **Online System State Estimation (Digital Twin)**  
Digital twin technology is one of the directions in my research that is closest to practical engineering applications. Structural health monitoring systems typically accumulate vast amounts of data, which contain important information about structural performance changes. Therefore, effectively extracting this potential structural performance information from the data is a key issue in my research. To achieve this, I primarily adopt **time-varying stochastic state-space models** rather than relying solely on deep learning. This approach helps better interpret the physical mechanisms behind the data, thereby improving the accuracy and reliability of the monitoring system.

Structures are continuously subjected to the combined effects of external environments and loads over time, which inevitably leads to a gradual decline in their performance. The advantage of digital twin technology lies in its ability to integrate **time-varying stochastic state-space models** with real-time data, updating the structural state in real-time through simulation and feedback from the data, while predicting the future behavior of the structure. This method can effectively support decision-making in structural health monitoring, ensuring the safety and reliability of structures in complex environments.

### 6. **Modal Identification (Koopman Modal Decomposition)**  
Modal identification is an important aspect of structural health monitoring. This method helps analyze and identify the dynamic behavior of structures under different load conditions. Through modal analysis, we can extract information such as the structure's natural frequencies, mode shapes, and damping characteristics, all of which are critical for assessing the health of the structure. In fact, this can be viewed as a special case of Koopman modal decomposition.

The Koopman modal decomposition method is particularly well-suited for modal identification of nonlinear systems because it can map nonlinear systems into a higher-dimensional space, where linear behavior is sought, thus simplifying the modal analysis process. This method provides valuable insights into structural health monitoring, especially when facing complex and dynamically changing load environments. It effectively helps identify structural changes and damage, providing reliable data support for structural safety assessment.


