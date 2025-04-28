# JD-training

Con base en el robot bípedo JD, cuyas características cinemáticas son mostradas en la siguiente figura, ha sido implementado un problema de Aprendizaje Por Refuerzo Profundo para el aprendizaje de la marcha bípeda.

![jd_training](https://github.com/user-attachments/assets/f9da318b-fae0-4787-a2c3-5fce6df53bcb)

El robot fue entrenado en el entorno de simulación multi-cuerpo Pybullet, utilizando el algoritmo Twin Delayed Deep Deterministic Policy Gradient (TD3), con un total de 300 000 epiodios de entrenamiento, el el siguente video se aprecian seis diferentes episodios de entrenamiento:

https://github.com/user-attachments/assets/28b50db1-60c3-4f69-9958-dad59a17cbc0

La curva de entrenamiento su muestra a continuación:

![jd_training_2](https://github.com/user-attachments/assets/f9eb43d8-5ede-4e95-9440-adbf99ef601d)

Después de 8 horas de entrenamiento en una computadora Nvidia Jetson Nano, el algoritmo de aprendizaje TD3 fue capaz de aprender a desplazarse en el entorno virtual, como se observa en el siguiente video:

https://github.com/user-attachments/assets/515b9b6d-971b-49f0-b375-2abaea9df73a






