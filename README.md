# Equilibrium optimizer: A novel optimization algorithm
The Equilibrium Optimizer is a novel optimization algorithm that I developed and applied to the NSL-KDD dataset for fine-tuning the hyperparameters of a model. The NSL-KDD dataset is widely used for network intrusion detection and provides a challenging problem domain for optimization. With the Equilibrium Optimizer, I aimed to achieve the best possible performance by finding the optimal combination of hyperparameters for the model.

Through a series of experiments and iterations, I successfully leveraged the Equilibrium Optimizer to achieve an impressive accuracy rate of 96% on the NSL-KDD dataset. This achievement demonstrates the effectiveness of the algorithm in optimizing the hyperparameters and improving the performance of the model.

By utilizing the Equilibrium Optimizer, I was able to efficiently explore the hyperparameter space, finding the optimal configuration that maximized the model's accuracy. This not only showcases the power of the algorithm but also highlights its potential for use in other optimization tasks.

The success of the Equilibrium Optimizer in fine-tuning the hyperparameters and achieving a high accuracy rate on the NSL-KDD dataset underscores its potential as a valuable tool in various domains that require optimization. Its ability to efficiently search for the best parameter settings contributes to enhancing the performance of models and can lead to improved results in real-world applications.

<p align="center">
  <img src="https://raw.githubusercontent.com/afshinfaramarzi/Equilibrium-Optimizer/master/Image.PNG" width="50%"/>
</p>

EO’s performance was validated against 58 mathematical functions including unimodal, multimodal, hybrid and composition functions as well as 3 engineering benchmark problems and its performance was compared to three classes of optimization methods; GA and PSO as the most well-studied metaheuristics, GWO, GSA and SSA as recently developed algorithms and CMA-ES, SHADE and LSHADE-SPACMA as high performance optimizers. Comprehensive statistical analysis revealed that EO is able to significantly outperform PSO, GA, GWO, GSA, SSA and CMA-ES while its performance is statistically similar to SHADE and LSHADE-SPACMA.

The structure of EO is simple and easy to implement. This algorithm is computationally efficient and like PSO and GA its complexity is of polynomial order: O(tnd+tcn) where t,n,d and c represents iteration, number of particles, number of dimensions and cost of function evaluation, respectively.



Overall, the development and application of the Equilibrium Optimizer in fine-tuning the hyperparameters of the model on the NSL-KDD dataset resulted in a remarkable accuracy rate of 96%, demonstrating its effectiveness and potential as an optimization algorithm in the field of machine learning and data analysis.
### Paper Link 
### https://www.sciencedirect.com/science/article/abs/pii/S0950705119305295

