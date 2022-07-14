# Spiking-Neural-Network-Paper-List
Paper list for Spiking Neural Networks (SNN). Spiking neural networks (SNNs) are artificial neural networks that more closely mimic natural neural networks. In addition to neuronal and synaptic state, SNNs incorporate the concept of time into their operating model. The idea is that neurons in the SNN do not transmit information at each propagation cycle (as it happens with typical multi-layer perceptron networks), but rather transmit information only when a membrane potential – an intrinsic quality of the neuron related to its membrane electrical charge – reaches a specific value, called the threshold. When the membrane potential reaches the threshold, the neuron fires, and generates a signal that travels to other neurons which, in turn, increase or decrease their potentials in response to this signal. A neuron model that fires at the moment of threshold crossing is also called a spiking neuron model. [[wikipedia](https://en.wikipedia.org/wiki/Spiking_neural_network)]

![image](https://github.com/wangxiao5791509/Spiking-Neural-Network-Paper-List/blob/main/MLP-ANN-SNN.png)


## Year 2022 
* Chen, Yanqi, et al. "**State Transition of Dendritic Spines Improves Learning of Sparse Spiking Neural Networks**." International Conference on Machine Learning. PMLR, 2022. [[Paper](https://proceedings.mlr.press/v162/chen22ac/chen22ac.pdf)]


## Survey | Review Papers: 

1. Wang, Xiangwen, Xianghong Lin, and Xiaochao Dang. "Supervised learning in spiking neural networks: A review of algorithms and evaluations." Neural Networks 125 (2020): 258-280. [[Paper](https://drive.google.com/file/d/1_q5Yff4p0dr8FFLFYwSz2YG8ZoBnYh4N/view?usp=sharing)] 
2. Tavanaei A, Ghodrati M, Kheradpisheh S R, et al. Deep learning in spiking neural networks[J]. Neural Networks, 2019, 111: 47-63. [[Paper](https://arxiv.org/pdf/1804.08150.pdf)] 
3. Taherkhani A, Belatreche A, Li Y, et al. A review of learning in biologically plausible spiking neural networks[J]. Neural Networks, 2020, 122: 253-272. [[Paper](http://irep.ntu.ac.uk/id/eprint/38467/1/1213346_Taherkhani.pdf)] 
4. Bouvier M, Valentian A, Mesquida T, et al. Spiking neural networks hardware implementations and challenges: A survey[J]. ACM Journal on Emerging Technologies in Computing Systems (JETC), 2019, 15(2): 1-35. [[Paper](https://arxiv.org/ftp/arxiv/papers/2005/2005.01467.pdf)] 

## Learning Methods for SNN: 
1. Gradient descent for spiking neural networks[C]//Huh D, Sejnowski T J.  Proceedings of the 32nd International Conference on Neural Information Processing Systems. 2018: 1440-1450. [[Paper](https://dl.acm.org/doi/pdf/10.5555/3326943.3327075)]
2. Learning from Event Cameras with Sparse Spiking Convolutional Neural Networks[J]. Cordone L, Miramond B, Ferrante S. arXiv preprint arXiv:2104.12579, 2021. [[Paper](https://arxiv.org/pdf/2104.12579)] 
3. A review of the integrate-and-fire neuron model: I. Homogeneous synaptic input[J]. Burkitt A N. Biological cybernetics, 2006, 95(1): 1-19. [[Paper](https://www.academia.edu/download/40355613/A_Review_of_the_Integrate-and-fire_Neuro20151124-29087-tmxxka.pdf)] 
4. A framework for spiking neuron models: The spike response model[M]// Gerstner W.  Handbook of Biological Physics. North-Holland, 2001, 4: 469-516. [[Paper](https://infoscience.epfl.ch/record/97804/files/SRM.pdf)] 
5. Spiking neuron models: Single neurons, populations, plasticity[M]. Gerstner W, Kistler W M. Cambridge university press, 2002. [[Paper](https://books.google.com/books?hl=zh-CN&lr=&id=Rs4oc7HfxIUC&oi=fnd&pg=PR11&dq=Gerstner,+W.,+%26+Kistler,+W.+M.+(2002).+Spiking+neuron+models:+Single+neurons,+populations,+plasticity.+Cambridge+University+Press.&ots=2Sa0yUdNY4&sig=O7TZEAGrE690sorBqYXB68Pbcdc)] 
6. Online spatio-temporal pattern recognition with evolving spiking neural networks utilising address event representation, rank order, and temporal spike learning[C]//Dhoble K, Nuntalid N, Indiveri G, et al. The 2012 international joint conference on Neural networks (IJCNN). IEEE, 2012: 1-7. [[Paper](https://www.zora.uzh.ch/id/eprint/75309/1/Dhoble_et_al_Online_spatio-temporal_pattern_recognition.pdf)] 
7. Efficient event-driven simulation of large networks of spiking neurons and dynamical synapses[J]. Mattia M, Giudice P D.  Neural Computation, 2000, 12(10): 2305-2329. [[Paper](https://www.mitpressjournals.org/doi/pdfplus/10.1162/089976600300014953)] 
8. Event-driven simulation scheme for spiking neural networks using lookup tables to characterize neuronal dynamics[J]. Ros E, Carrillo R, Ortigosa E M, et al. Neural computation, 2006, 18(12): 2959-2993. [[Paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.323.8925&rep=rep1&type=pdf)] 
9. A novel time-event-driven algorithm for simulating spiking neural networks based on circular array[J]. Peng X, Wang Z, Han F, et al. Neurocomputing, 2018, 292: 121-129. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231218302601)] 
10. 


































