# Deep-Learning
**深度学习**
# part Ⅰ ANN
[*人工神经网络*](https://github.com/huangzy97/Deep-Learning/blob/master/ANN.py)  
ANN(Artificial Neural Network),人工神经网络学习过程：  
* STEP 1.  随机初始化权重(Weights),使他们接近于0，但是不等于0。 
  
* STEP 2.  将第一个观察数据(训练数据)传输给输入层(input layer),每个训练数据的自变量特征(feature)占据一个输入神经元(input neuron)。  
  
* STEP 3.  正向传播:神经网络从左到右,所有的神经元被激活。每个神经元得到的来自上一层神经元的输入都和对应突触(synapse)上的权重相关。正向传播的激活过程直到输出层(output layer)得到输出结果为止。     
  
* STEP 4.  比较神经网络输出结果(预测值)和实际观察结果，并计算损失函数的值(误差)。   
  
* STEP 5.  反向传播:神经网络从右到左，误差被反向传播。依据损失函数(误差)相对于权重的梯度(gradient),对每个权重进行更新,以达到最小化损失函数的目标。学习速率(learning rate和梯度共同决定更新的速度。  
  
* STEP 6.  对于**每一个**新的观察数据,重复STEP 1到STEP 5(强化学习reinforcement learning) ,或者:对于**每一组**新的观察数据，重复STEP1到STEP5(批量学习batchlearning)。注意:此时的损失函数的值是这一组中所有观察数据产生误差的**和**。
  
* STEP 7.  当整个训练集都被输入神经网络后,我们称之为**一期**(epoch)训练。我们可以进行更多**期**的训练,继续优化权重,以达到最小化总损失函数的日的。
  
# part Ⅱ CNN
*卷积神经网络*  
[*1 keras*](https://github.com/huangzy97/Deep-Learning/blob/master/CNN_keras.py)  
[*2 TensorFlow*](https://github.com/huangzy97/Deep-Learning/blob/master/CNN_tensorflow.py)  
*CNN数据拟合过程：*  
![image](https://github.com/huangzy97/lib/blob/master/picture.gif)
# part Ⅲ NLP
[*自然语言处理*](https://github.com/huangzy97/Deep-Learning/blob/master/NLP.py)  
# part Ⅳ 图像识别  
分别采用了[DNN](https://github.com/huangzy97/Deep-Learning/blob/master/mnist_keras_DNN) 和[CNN](https://github.com/huangzy97/Deep-Learning/blob/master/mnist_keras_cnn) 对手写数字图片做了训练。两种训练结果的得分相近，CNN在测试数据集的score为0.9901，DNN在测试数据集的score为0.9818，但是其预测结果相差很大，结果如下：  
![原图](https://github.com/huangzy97/lib/blob/master/3.png)   
![DNN预测结果](https://github.com/huangzy97/lib/blob/master/DNN%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C.png)![CNN预测结果](https://github.com/huangzy97/lib/blob/master/CNN%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C.png)   
