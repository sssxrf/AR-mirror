# AR mirror

## Background

The patients with lower-limbs sensor loss usually have a hard time during the rehabilitation. They have no idea about where and what their feet are while walking. Thus, they always lower their head and focus their eyes on their feet, which exerts negative influence on their recover. So, I thought up a method using Hololens2 (Augmented Reality glasses) to enable the patient to see their feet's posture without looking down. 

The core part of the method is to measure the information of feet's posture and transmit to Hololens2. Firstly, I used pressure sensors to detect the Limb-posture on feet and one-chip computer STM32 to store and analyze the pressure information. Then, BLE(Bluetooth Low Energy) is applied to wireless transmit the pressure information to the Hololens2(The Augmented Reality Glass). In the Hololens2 part I designed an UI for users to connect with the BLE both in a way to press AR buttons and speak out key words to control. In order to refine the view in Hololens2, I scanned the feet model of mine and imported it into Unity to show the limb-posture in an intuitive way.

![image](https://drive.google.com/uc?export=view&id=1_ZwhAznTtV2oCE32r05C87x6GmeJ3jqQ)

## Results

As a result, the users can tell which part of their feet has landed on the ground. The followings are some pictures about the project. (you can find more pictures and videos in the 'video and images' file in Google Drive)

<img src="https://drive.google.com/uc?export=view&id=1np7QmME5ep7iC7qgc0FEyv7aIV72a235" alt="image" style="zoom:25%;" />





![image](https://drive.google.com/uc?export=view&id=1gIiM1DIMHvFm0_XDO4-QcxaQR2lBQIZa)

![image](https://drive.google.com/uc?export=view&id=1z-cu4aDi2pZ7n64M9ZJk8WC9_FmT5ui4)

