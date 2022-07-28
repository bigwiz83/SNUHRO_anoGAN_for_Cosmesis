# SNUHRO_anoGAN_for_Cosmesis

We used the generative adversarial network (GAN) model that can generate the anomaly score (AS) to assess cosmetic result in patients who received mastectomy and immediate reconstruction followed by radiation therapy (RT). The AS might be feasible in predicting cosmetic outcomes in RT-treated patients with breast reconstruction, which should be validated in the prospective study.

The GAN model in the current study is adopted from f-AnoGAN model (https://github.com/A03ki/f-AnoGAN)
Based on the publicly available source code, we made a notebook (Training and Inference.ipynb) that contained model training and inference anomaly score (AS).

The higher AS, the poorer cosmesis in breast cancer patients who received immediate reconstruction followed by radiation therapy.
The final model can be found at 'results' folder. 
To test the model, 2d chest front images from 3D-CT images (plan CT or breast/chest CT) are needed. 
Example files are found in 'Lightshot_*' folders.


Full manuscript and clinical implications are published in the npj Digital Medicine.
You have to cite the study if you would use the model or notebook.

