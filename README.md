# Controlled Bias Generation GAN- VAE-MNIST
Application of Generative adversarial Networks on MNIST data. Introduced a Controlled data class Imbalance/Bias and Studied the Generated Images.

Developed an innovative approach for incorporating controlled bias into class representation by designing a custom
dataloader for generating images from the widely-used MNIST handwritten digits dataset
• Conducted research on the generation of images, comparing the properties of synthesized images between GANsand VAEs
by performing a high accuracy 98% CNN image classifier. Utilized PyTorch Deep learning framework for its flexibilty
• Observed a correlation between the proportion of class imbalance in the images and the resulting distribution of generated
images. Utilized metrics to quantify the extent of this relationship and improving the distribution of generated images

![image](https://user-images.githubusercontent.com/87997273/232247471-a92492da-cbcc-4853-9648-412808e4b9a9.png)

![image](https://user-images.githubusercontent.com/87997273/232247497-70427a3d-e772-417d-b812-442831821537.png)

<td>
    <p>while in case of Generative Adverserial Networks we have seen that class imbalance has drastic effects in generated images resulting more imbalance. <br />   
    The VAE dont change the class distribution of generated images and it is also proportinal noise given to model generator.<br /></p>
      
      

  </td>
  
  
  ![image](https://user-images.githubusercontent.com/87997273/232247731-3b4302b6-2ec4-47d2-9433-04b5ae49f5d4.png)


