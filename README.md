we propose a novel HSI classification algorithm by combining the adaptive improved graph convolutional networks (AIGCNs) and the CNNs, named AIGCN-CNN. 
First, for the AIGCNs, we propose the AIGCN model to improve the conventional GCN model and provide its theoretical benefits. With the proposed AIGCN model, two AIGCN subnetworks from spatial and spectral domains are constructed to extract spatial-spectral information from the superpixels of the HSI. 
The superpixels are obtained by using the segment anything model (SAM) and can effectively capture the homogeneous information among the pixels of the HSI and reduce the computational burden. 
Second, the CNNs are formed by using two simple $1$-D and $2$-D kernels, separated from the $3$-D convolutional kernel, to extract the heterogeneous information of the pixels and to reduce the computational burden. 

