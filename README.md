
# The comparison of  the SBL-GAMP and EM-BG-GAMP 

This is a comparison about SBL-GAMP and EM-BG-GAMP for the speech signal.

<table style="border-collapse: collapse">
<tr>
<td>
<p>
The paper have proposed a computationally efficient sparse Bayesian learning (SBL) algorithm via the GAMP technique.
It has a lower computational complexity. More details can be found in
  
Fuwei Li, Jun Fang, Huiping Duan, Zhi Chen, Hongbin Li,'Computationally Efficient Sparse Bayesian Learning via
Generalized Approximate Message Passing' submitted to arXiv.  
https://ieeexplore.ieee.org/document/7790383
 
The EM-BG-GAMP, lies in constructing a hierarchical prior model (Gaussian model), and the EM is utilized to learn the hyper-parameters.
More details can be found in
 
X. Meng, S. Wu, L. Kuang, J. Lu et al., 'Approximate message passing with nearest neighbor sparsity pattern learning' submitted to arXiv.

https://arxiv.org/abs/1601.00543  
</p>
</td>
</tr>
</table>

## 1MN.fig

1MN.fig is the NMSE versus Measurement ratios: M/N=0.2 to M/N=0.9. 
Here, we used the frist ten frames of the speech, which is with a sampling rate at 8 KHz.
## 2SNR.fig 

2SNR.fig is the NMSE versus input SNRs (0-20dB), the M/N=0.9.
