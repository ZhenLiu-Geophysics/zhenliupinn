# zhenliupinn
## Physics-Informed Neural Network Platform for Next-Generation AVO Inversion
> 🚧 **Status:** This repository is under active development.  
> Core PINN / iPINN / iBPINN codes associated with accepted papers will be released in stages.


**zhenliupinn** is an open-source platform for pre-stack AVO inversion, building a comprehensive family of physics-informed neural network (PINN) solutions. This project aims to drive next-generation geophysical inversion and reservoir characterization by integrating physics, AI, and Bayesian uncertainty modeling.

## Key Architectures Included

- **CNN-PINN:** Classic convolutional PINN framework.
- **CNN-BiLSTM-PINN:** Sequence modeling enhanced PINN.
- **DC-PINN (Dual-Constraint PINN):** PINN incorporating both physical and numerical constraints (dual-constraint formulation).
- **iPINN:** PINN with learnable wavelet frequency (implicit PINN).
- **BPINN:** Bayesian PINN for uncertainty quantification.
- **iBPINN:** Frequency-adaptive Bayesian PINN. (https://doi.org/10.1109/TGRS.2025.3636416)
- **BPI-ViT:** Bayesian Physics-Informed Vision Transformer — the flagship model, enabling structure-level uncertainty quantification and attention-based interpretability (https://doi.org/10.21203/rs.3.rs-7097139/v3).
- **Future Extensions:**  
  Advanced PINN-based architectures, including uncertainty-aware inversion, structure-level modeling, and emerging quantum-informed extensions, are under active investigation.





---

## Related Publications

1. **Z. Liu, J. Zhang, Y. Chen, D. Feng and L. Qi**,  
   *“From Physics Constraints to Trustworthy Bayesian Reasoning: Synergies of PINN, iPINN, and iBPINN in Pre-stack AVO Inversion,”*  
   *IEEE Transactions on Geoscience and Remote Sensing*, vol. 63, pp. 1-24, 2025, Art no. 5926424, doi: 10.1109/TGRS.2025.3636416.
   🔗[https://ieeexplore.ieee.org/document/11265799]
   🔗[[TGRS,Q1,IF=8.6]From_Physics_Constraints_to_Trustworthy_Bayesian_Reasoning_Synergies_of_PINN_iPINN_and_iBPINN_in_Prestack_AVO_Inversion.pdf](https://github.com/user-attachments/files/24216507/22.TGRS.Q1.IF.8.6.From_Physics_Constraints_to_Trustworthy_Bayesian_Reasoning_Synergies_of_PINN_iPINN_and_iBPINN_in_Prestack_AVO_Inversion.pdf)
   
3. **Zhen Liu, Junhua Zhang, Yongrui Chen, Deyong Feng, Liang Qi**,  
   *“Application of CNN-BiLSTM-PINN Network Integrating Physical and Numerical Constraints in AVO LMR Inversion,”*  
   *Interpretation*, 2025.
4. **Zhen Liu, Junhua Zhang, Yongrui Chen
 et al.**  
   *“A Physics-aware Bayesian Vision Transformer for Seismic AVO Inversion: Towards an Embodied Structural Intelligence Framework with Structure-aware Uncertainty Modeling,”*  
   *17 October 2025, PREPRINT (Version 3) available at Research Square [https://doi.org/10.21203/rs.3.rs-7097139/v3]*  
   🔗[BPI-ViT_Prototype paper_v3_covered.pdf](https://github.com/user-attachments/files/24049023/BPI-ViT_Prototype.paper_v3_covered.pdf)  

**Listed papers #1&#2 have been officially accepted, and the corresponding code will be released in the near future.**

## 🧭 Development Roadmap (Planned)
> The roadmap reflects the current development plan and may evolve as research progresses.
- [ ] Release CNN-PINN baseline (AVO inversion)
- [ ] Release iPINN with learnable wavelet frequency
- [ ] Release Bayesian PINN (BPINN / iBPINN)
- [ ] Release BPI-ViT prototype (structure-aware uncertainty)
- [ ] Add examples and reproducibility scripts






## Contact & Collaboration
> Built with passion for physics-informed geophysical AI ❤️  

For academic collaboration, reproducibility inquiries, or research discussions related to PINN-based AVO inversion and trustworthy geophysical AI,  
please feel free to reach out via email:

- **zhenliu.erasmus@gmail.com  (primary)**  
- **lincoln110@foxmail.com  (secondary)**

Discussions and issues are also welcome through this repository.










## 📦 Dataset Source & Accessibility

The seismic dataset used throughout this repository is based on the **public Marmousi2 model** provided by the  
**Allied Geophysical Laboratories (AGL), University of Houston (UH).**

### 🔗 Official UH Data Source  
The original dataset can be downloaded from the University of Houston AGL website:  
👉 **http://www.agl.uh.edu/downloads/downloads.htm**

This dataset is openly distributed by UH for academic and research purposes.

---

### 🟦 Kaggle Mirror (Convenience Copy)

To ensure reproducibility and make it easier for users to access the dataset without dealing with download issues or format conversions,  
a **convenience mirror** of the dataset is available on Kaggle:

👉 **https://www.kaggle.com/datasets/allensmithgodlike/marmousi2-model-for-geophysics**

> **Note:**  
> This Kaggle dataset is a *non-official mirror*.  
> It is provided solely to support users of the zhenliupinn framework (PINN / iPINN / BPINN / iBPINN / BPI-ViT).  
> The University of Houston remains the original and authoritative source.


