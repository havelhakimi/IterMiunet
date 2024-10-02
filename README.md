# IterMiUnet: A lightweight architecture for automatic blood vessel segmentation
Model Checkpoints to reproduce the results for the journal paper  "IterMiUnet: A lightweight architecture for automatic blood vessel segmentation" [arxiv](https://arxiv.org/abs/2208.01485) [journal](https://link.springer.com/article/10.1007/s11042-023-15433-7)
* Since this is an old work standalone keras 2.2.4 was used while training the models as opposed tf.keras which comes integrated with tensorflow now.
* The jupyter notebook inside Stare folder can be run using the older version of standalone keras
* We have shared the model checkpoints for the Stare dataset in `Stare/Models`, where 20 models were trained using leave-one-out validation. For example, `Stare/Models/Stareiternetim0001.keras` was trained using all 19 images except im0001 and will be tested on im0001 during prediction, and similarly for the other 19 models. 
## Citation
```bibtex
@article{kumar2023itermiunet,
  title={IterMiUnet: A lightweight architecture for automatic blood vessel segmentation},
  author={Kumar, Ashish and Agrawal, RK and Joseph, Leve},
  journal={Multimedia Tools and Applications},
  volume={82},
  number={28},
  pages={43207--43231},
  year={2023},
  publisher={Springer}
}
