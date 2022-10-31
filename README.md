# AB-GAN: Adabeleif Generative Adversarial Networks for Generating 3D Shapes from Natural Language Texts 
introducton

in this repo you can find a code for train and evaluate AB-GAN.
AB-GAN is a modified version of DM-GAN represented in[] by substituting the Adam optimizer with the AdaBeleif optimizer which is traiend using ShapeNet datset for generating 3D chairs and tabels based on natural language discription.

data

Download pre-process ShapeNet dataset and extract it to data/shapenet

training

python main.py --cfg cfg/shapenet.yml --gpu 0

validation

python main.py --cfg cfg/eval_shapenet.yml --gpu 0

Performance

the following fig shows some 3D shapes which are generate using state-of-art gan models compare to our AB-GAN model. 


License
