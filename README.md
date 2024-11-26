# BooleanAlgebra__DeepLearning
BOOLEAN ALGEBRA: FROM DIGITAL CIRCUITS TO DEEP LEARNING APPLICATIONS © 2024 by Filipa Trindade Coito is licensed under CC BY-SA 4.0

M.Sc Thesis in Biostatistic and Biometry: _Boolean Algebra: from Digital Circuits to Deep Learning Applications_


### **Abstract**
Boolean algebra plays a central role in digital logic, being essential for the design and optimization of circuits and computational systems. This work explores the principles of Boolean algebra and its traditional applications in digital circuits, as well as its innovative uses, such as in the field of deep learning. These applications enable the development of computationally efficient models and advance the state of the art in areas like embedded systems and low-power computing.
The dissertation delves deeply into Boolean algebra, examining its properties and laws, including the simplification of Boolean expressions. Concepts such as sum of products, product of sums, and the construction of Karnaugh maps are discussed, as they are fundamental in optimizing digital circuits. It then addresses the application of Boolean algebra in digital circuit design, focusing on combinational and sequential circuits. Practical examples, such as adders, encoders, and binary counters, are presented to illustrate how these Boolean operations underpin the construction of such circuits.
Finally, the work explores the relationship between Boolean algebra and neural networks, based on the study by Petersen et al. (2023), which proposes logic gates neural networks (LGNs). These networks are adapted to differentiable versions, enabling the use of gradient-based optimization methods. The study analyzes the performance of LGNs in image classification tasks, highlighting their advantages and challenges compared to traditional networks.

**Keywords:** Boolean Algebra, Neural Networks, Logical Functions, Deep Learning, Logic Gate Networks.






### **Chapter 8**
After exploring the traditional applications of Boolean algebra, this thesis turns its focus to the innovative crossing between Boolean algebra and the NNs.
Building on the presented concepts, chapter eight presents an innovative architecture known as LGNs, a type of NN inspired by Boolean principles. 
This approach, initially proposed by Petersen et al. (2023), integrates logic functions directly into the NN architecture. The main innovation is the adaptation of these networks into differentiable versions, which allows the use of gradient-based optimization algorithms. 
This chapter stands out from the rest, as it presents the practical experiment of this thesis by implementing a LGN to a selected dataset for an image classification exercise and analyze the results. In parallel an FFN will also be implemented to the same dataset and with approximately the same number of trainable parameters and subsequently analyzed.
Finally, this thesis proposes a hybrid approach that integrates theory and practice, combining the principles of Boolean algebra with the latest innovations in deep learning. It is believed that the integration of these areas can offer new perspectives for the development of more efficient NNs, with enhanced performance in terms of computational optimization and generalization capacity.
In conclusion, this research aims to underscore the critical role that Boolean algebra continues to play in the advancement of both hardware and software technologies. By examining its historical significance and contemporary applications, the thesis illustrates how the convergence of mathematical logic and technological innovation propels the development of more efficient, reliable, and advanced computational systems, paving the way for future breakthroughs in artificial intelligence and beyond.


### **Repository**
Here is made available the code for the pratical experiments presented on Chapter 8.




### **Bibliography**
The LGN model was implemented based on:
Petersen, F., Borgelt, C., Kuehne, H., & Deussen, O. (2023). Deep differentiable logic gate networks. Advances in Neural Information Processing Systems, 35, pp. 2006-2018. Available at: https://github.com/Felix-Petersen/difflogic
