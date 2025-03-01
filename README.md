# Personal Introduction

I am a PhD student at **Harbin Institute of Technology (Shenzhen)**, enrolled in September 2023. My doctoral thesis is currently focused on **Structural Health Monitoring**. My research mainly focuses on the following areas:

- Data-driven linear/nonlinear system identification
- Model order reduction
- Online system state estimation
- Modal identification

The primary theoretical foundation of my work is the Koopman operator and optimal estimation (statistical signal processing). However, while the theory is elegant, it does not always translate smoothly into practical applications. Therefore, in practice, the algorithms I design rely heavily on convex optimization methods for implementation.

---

## Key Research Directions and Technical Approaches

### 1. **System Identification Based on Stochastic Subspace Methods**
This approach is based on classical techniques from the 1980s, primarily relying on the orthogonality between the signal subspace and the noise subspace to remove noise and achieve high-precision system identification. This method has broad applications in high-precision system modeling and signal processing.

### 2. **Nonlinear System Identification Based on Koopman Operator Theory**
This method relies on the **Koopman operator theory**, where the state vector of a dynamic system is mapped into a high-dimensional (and potentially infinite-dimensional) space, seeking a linear representation within that space. This approach is similar to Kernel methods and is highly effective in nonlinear system identification, and it is currently emerging as a cutting-edge research topic.

### 3. **Optimal Estimation**
Although I am still delving into optimal estimation theory, its core idea is to estimate parameters from noisy signals to recover the signal accurately. The **Kalman filter** is a classic example of this approach. In practice, noise is typically assumed to be white noise, and its characteristics need to be estimated, a process that can sometimes be subjective. In recent years, deep learning has gradually replaced traditional methods in signal processing, but many challenges remain in this area that are worth exploring.

### 4. **Data-driven Model Order Reduction**
Model order reduction is a popular research direction in fields like computational fluid dynamics, especially in the context of high-dimensional fluid data generated from simulations. This technique effectively reduces computational load. However, for real-world sensor sampling systems, whether high-dimensional data can be obtained is still uncertain. Additionally, ensuring the generalization ability of data-driven reduction methods remains a major challenge, particularly under different boundary conditions and initial conditions.

### 5. **Online System State Estimation (Digital Twin)**
Digital twin technology is one of the directions of my research that is closest to practical engineering applications. Structural health monitoring systems typically accumulate vast amounts of data, which contain important information about the performance changes of the structure. Therefore, effectively extracting this potential structural performance information from the data is a key problem in my research. To achieve this, I primarily adopt physics-based models rather than relying solely on deep learning, which helps better interpret the physical mechanisms behind the data.

### 6. **Modal Identification (Koopman Modal Decomposition)**
Modal identification is an essential aspect of structural health monitoring, commonly referred to as **Koopman modal decomposition**. This method helps analyze and identify the dynamic behavior of structures under different load conditions.


## Research Goals and Applications

My research aims to apply the above technologies to **structural health monitoring**, enhancing the safety, maintainability, and lifespan of structures through innovative system identification, order reduction, modal identification, and real-time state estimation techniques.

