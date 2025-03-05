**Hand Gesture Recognition** is nothing but a logical evolution from touchscreens. Snap your fingers and make your coffee maker brew you a fresh cup. Wave a hand near your smart TV and switch on today’s weather forecast. Apart from this fun and entertainment purposes, It aids individuals with disabilities by offering an alternative means of communication and control. It is also used in Medical care to reduce physical touch. As for automation - BMW’s gesture control system allows drivers to adjust volume, answer calls, or navigate using gestures. And Apple Vision pro is one of the examples that shows hand gesture recognition’s contribution in Virtual and Augmented Reality.


# Sign-language-translator
The goal of this project is to design and implement a real-time sign language  translator that can recognize and translate sign language gestures into spoken language or  text. The system will use Raspberry Pi 4B, sensors, and machine learning  algorithms for gesture recognition. 

Run the source code for model file on Jupyter Notebook. Make sure to choose the correct version of tensorflow - 2.4 and python - 3.6.13 as my Raspberry Pi 4B only supported 3.6 as it's latest version. You can update your code accordingly. 

Once the gesture_model.h5 or gesture_model.keras file is generated, run the real_time_detection file and your video streaming will begin. 

## Any Questions? Email Me:

Feel free to reach out if you have any questions or need help with this project!

📧 [payushi208@gmail.com](mailto:payushi208@gmail.com)


## About

This project uses machine learning to translate sign language gestures into spoken language or text. It leverages TensorFlow for gesture recognition and integrates it with a Raspberry Pi for real-time processing.

<details><summary>Key components:</summary>
  
</br>

- **Raspberry Pi 4B**
- **Machine Learning Algorithms**
- **OpenCV for Gesture Detection**
- **Text-to-Speech for Output**
  
</br>

</details>


## **Proposed System**


![image](https://github.com/user-attachments/assets/d8441cbf-7199-4dd5-ae09-3da331e9ad2b)




Dataset - https://drive.google.com/file/d/1jF45Ud5cWhGuLeakHtMagQ6usAVOZfUv/view?usp=sharing




## **Results**

<details><summary> <b>Static results </b> </summary>
  
![image](https://github.com/user-attachments/assets/e19e2c11-8cc9-464c-9fd8-dec71732999d)

</details>

<details><summary> <b>Dynamic results </b> </summary>

https://drive.google.com/file/d/1aMYgu5gCkE6UTovd3-dhHy7xNF6gSWG3/view?usp=sharing

</details>

_To check whether or not only the ROI is being preprocessed_


![image](https://github.com/user-attachments/assets/ea8f30a3-cf5f-495e-8148-a8fe73ce2246)



## **Tests**
For the testing phase, a 40-second video clip was recorded, where the user performed each of the seven hand gestures for 5 seconds, totaling 35 seconds, with a 5-second buffer for human error. To evaluate the models, confidence trends and predicted gestures over time were analyzed.

<details><summary> <b>Test 1: Confidence Trend over time </b> </summary>

![image](https://github.com/user-attachments/assets/f7ac5aef-dea2-4e08-af14-e5f6f722fc90)

</details>
<details><summary> <b>Test 2: Predicted Gestures over time </b> </summary>

![image](https://github.com/user-attachments/assets/97b0cefe-c8ab-4c07-b9e4-a694bbe7b489)

</details>

# References
[1]	Y. L. Chong, C. P. Lee, K. M. Lim and J. Y. Lim, "Hand Gesture Recognition with Deep Convolutional Neural Networks: A Comparative Study," 2023 IEEE 11th Conference on Systems, Process & Control (ICSPC), Malacca, Malaysia, 2023, pp. 60-65, doi: 10.1109/ICSPC59664.2023.10419918. 

[2]	M. A. A. Razak, F. Y. A. Rahman, R. Mohamad, S. Shahbuddin, Y. W. M. Yusof and S. I. Suliman, "Hand Gesture Recognition based on Convolution Neural Network (CNN) and Support Vector Machine (SVM)," 2023 IEEE 14th Control and System Graduate Research Colloquium (ICSGRC), Shah Alam, Malaysia, 2023, pp. 123-126, doi: 10.1109/ICSGRC57744.2023.10215427.

[3]	D. S. Breland, A. Dayal, A. Jha, P. K. Yalavarthy, O. J. Pandey and L. R. Cenkeramaddi, "Robust Hand Gestures Recognition Using a Deep CNN and Thermal Images," in IEEE Sensors Journal, vol. 21, no. 23, pp. 26602-26614, 1 Dec.1, 2021, doi: 10.1109/JSEN.2021.3119977.

[4]       https://arxiv.org/abs/2207.12866 

[5]       Singh, M., & Gupta, N. K., “Hand gesture recognition system using Raspberry Pi, OpenCV and IoT” in International Research Journal of Engineering and Technology (IRJET), 11(6), 687–692. DOI: https://www.irjet.net/archives/V11/i6/IRJET-V11I6104.pdf

[6]	https://www.raspberrypi.com/news/sign-language-translation-glasses/ 

[7]	Dataset - https://www.kaggle.com/datasets/grassknoted/asl-alphabet

[8]	K. Bousbai and M. Merah, "A Comparative Study of Hand Gestures Recognition Based on MobileNetV2 and ConvNet Models," 2019 6th International Conference on Image and Signal Processing and their Applications (ISPA), Mostaganem, Algeria, 2019, pp. 1-6, doi: 10.1109/ISPA48434.2019.8966918. 

[9]	Gargi, S., Saanika, G., Yugnanda, P., Jolly, P., & Gargi, M, “Novel system based on amalgamation of embedded systems and edge AI for hand gesture recognition: An edge AI solution for hand gesture recognition,” in Proceedings of the 2024 Sixteenth International Conference on Contemporary Computing (IC3-2024) (pp. 432–439). Association for Computing Machinery. https://doi.org/10.1145/3675888.3676089

[10]     T. M P, M. R. Bharamagoudra, S. Z. Noorain and S. Maria SP, "Hand Gesture Detection using Transfer Learning with Deep Neural Networks," 2023 IEEE 8th International Conference for Convergence in Technology (I2CT), Lonavla, India, 2023, pp. 1-5, doi: 10.1109/I2CT57861.2023.10126207.

[11]     American Sign Language | Commission on the Deaf and Hard of Hearing (CDHH)

[12]     Gulzar, Y. (2023). Fruit Image Classification Model Based on MobileNetV2 with Deep Transfer Learning Technique. Sustainability, 15(3), 1906. https://doi.org/10.3390/su15031906 

[13]     M. Al-Hammadi, G. Muhammad, W. Abdul, M. Alsulaiman, M. A. Bencherif and M. A. Mekhtiche, "Hand gesture recognition for sign language using 3DCNN", IEEE Access, vol. 8, pp. 79491-79509, 2020.

[14]    H. Cheng, L. Yang and Z. Liu, "Survey on 3D hand gesture recognition", IEEE transactions on circuits and systems for video technology, vol. 26, no. 9, pp. 1659-1673, 2015.

