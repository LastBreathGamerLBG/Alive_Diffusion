![image](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/300162b4-e8ae-47bc-b6b9-3e57382ea7a1)# Alive_Diffusion😊😊
---
     Alive Diffusion is a Stable Diffusion via code made easy by LBG with detailed  and easy steps.
     Any one can use it without thinking or managing stuffs.
---

# Why Alive_Diffusion ?🤔🤔
---
     After the ban of stable diffusion ATOMATIC 1111 webui in colab and lots of problems in kaggle.
     I switch to stable diffusion via code not using webui, but this make my life hell because i was 
     depanded on the other usere for colab and kaggle notbooks which was complex and for even loading
     my fav model it become like a hell to edit code. so i made my own colab and kaggle notebooks 
     which can run super easly and model changing is so easy. 
---

# For whom is these notbooks?🧐🧐
---
     These notebooks are for those person who want full control over code. i have explain everything in these notbooks
     it will kick start the journy of learning how to code stable diffusion and to gernate inmges very quickly.
---

# Colab Notebook⬇️⬇️
---
---> Link:

     https://colab.research.google.com/drive/11wX7lisITp7xVKeRJH3MXyKSGrIZ1QnB?usp=sharing 
---
---> Download:
     
     https://github.com/LastBreathGamerLBG/Alive_Diffusion/blob/main/Alive_SD.ipynb
---

# Kaggle Notebook⬇️⬇️
---
---> Link:

     https://www.kaggle.com/code/drtbhyjuk/diffusion
---
---> Download:

     https://github.com/LastBreathGamerLBG/Alive_Diffusion/blob/main/Alive_Diffusion_Kaggle.ipynb
---

# How to use ?

![dependicies](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/80ad6067-460c-498a-b621-29effb2c90c9)
---
     First install all the dependicies for the running the stable diffusion it will take some time to setup.
---
**Note for Devlopers**
---
     How can i download all dependencies packages in Google Drive and import them from there in this way i have
     to not do whole setup again. i tried but not work with for me nedd help 🙏..
---

![text_to_img](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/175f41d1-a8a9-4140-a685-31e36f8df135)
---
     This code run the "Text To Image" pipeLine for text to image conversion, if you are on colab gpu run the code simply
     but if you are in cpu use remove "#" from the cpu code and put "#" before the gpu code to disable it. like shown below
---
![cpu](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/5dee3912-b170-42a7-a7f1-4b753fe62c62)
---
![pipe_cpu](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/8d8624f7-e877-4d65-b3bd-192819d40675)
     
     then in but "#" on xformers code because it only works with gpu (if it works with cpu also tell me also how to do that?)
     also in pipe change "cpu" from "cuda" as we are running on cpu like this:
---
***NOTE THESE EXTRA STEPS ARE FOR ONLY CPU FOR GPU USERS DIRECTLY RUN CELL***
---
![image](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/a1565a37-e341-462f-8aaf-7cee31f58bc4)

     After that you can enter your prompts. NOTE: here NSFW content is on so be aware of kaggle banning Adult content
---
![image](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/37e8b7d7-8631-4a26-a61e-8a8c5032493a)
     
     IN the gernate cell you can add more perametes to make your image more custom. you will find your gernated image 
     displayed in outupt and stored as prompt name in files.
---
# How to use custom Models?

![moel](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/8f3539cf-b8e7-4ba0-86ad-a07b14bf683a)

     By default code uses epiCRealism model which is good for gernating humans images but if you want you models 
     like from civit or hugging face just follow the steps:

![google](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/ffb94792-2033-4aee-9a52-f2dc1a3d9862)

     Search on google "model name" and "hugging face" tag at last. in this example i am using "dream shaper model hugging face"

![results](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/8eb5a6ec-e38c-4882-9f0e-b1faa61e1fbf)

     Go to the offical model hugging face website.

![copy](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/25cec143-5088-409c-b495-3d3b00bcaeb1)

     Copy the model link from there using a copy button. you will find that at top of website

![paste](https://github.com/LastBreathGamerLBG/Alive_Diffusion/assets/160850941/68c70dad-7489-4b30-b96d-77cf313a1339)

     And replace the copyed model id to model_id in the code. make sure to put " " as string




