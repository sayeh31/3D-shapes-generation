# AB-GAN: Adabeleif Generative Adversarial Networks for Generating 3D Shapes from Natural Language Texts 
### Introducton

in this repo you can find a code for train and evaluate AB-GAN.
AB-GAN is a modified version of [DM-GAN ](https://arxiv.org/abs/1904.01310) by substituting the Adam optimizer with the AdaBeleif optimizer which is traiend using ShapeNet datset for generating 3D chairs and tabels based on natural language discription.

### Data

Download pre-process ShapeNet dataset and extract it to `data/shapenet`

### Training


- `python main.py --cfg cfg/shapenet.yml --gpu 0`
### Validation

- `python main.py --cfg cfg/eval_shapenet.yml --gpu 0`

### Performance

the following fig shows some 3D shapes which are generate using  AB-GAN model with diffrent value for lambda2 hyperparameter. 

![alt text](https://github.com/sayeh31/3D-shapes-generation/blob/main/AB-GAN.png)


