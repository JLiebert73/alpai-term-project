# Training MAML with RK-2&4 in Pytorch 🚀
**
Group Project by: Nisarg Bhavsar, Akash Kaushik, Vedic Dutta, Ashesh Xalxo


Meta-learning[^1][^2] has become a cornerstone for developing models that quickly adapt to new tasks with limited data. The Model-Agnostic Meta-Learning (MAML) [^3] framework is particularly notable for its ability to fine-tune models efficiently across diverse tasks. This report extends the traditional MAML framework by incorporating fourth-order Runge-Kutta (RK4) methods [^4], aiming to enhance optimization beyond the capabilities of second-order methods previously used. 

Our experiments replicated the original setup from recent studies [^5][^6] that applied second-order Runge-Kutta (RK2) methods to MAML. By integrating RK4, we observed a notable increase in one-shot classification accuracy, underscoring the potential of higher-order numerical methods in optimizing meta-learning processes. This work demonstrates the feasibility of RK4 in boosting MAML’s performance and sets the stage for further explorations into sophisticated numerical integration techniques within meta-learning.

**
