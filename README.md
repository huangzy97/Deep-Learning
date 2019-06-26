# Deep-Learning
**深度学习**
# part Ⅰ ANN
[*人工神经网络*](https://github.com/huangzy97/Deep-Learning/blob/master/ANN.py)  
ANN(Artificial Neural Network),人工神经网络学习过程：  
step 1. 随机初始化权重(Weights),使他们接近于0，但是不等于0。  
step 2. 将第一个观察数据(训练数据)传输给输入层(input layer),每个训练数据的自变量特征(feature)占据一个输入神经元(input neuron)。    
step 3. 正向传播:神经网络从左到右,所有的神经元被激活。每个神经元得到的来自上一层神经元的输入都和对应突触(synapse)上的权重相关。正向传播的激活过程直到输出层(output layer)得到输出结果为止。     
step 4. 比较神经网络输出结果(预测值)和实际观察结果，并计算损失函数的值(误差)。    
step 5. 反向传播:神经网络从右到左，误差被反向传播。依据损失函数(误差)相对于权重的梯度(gradient),对每个权重进行更新,以达到最小化损失函数的目标。学习速率(learning rate和梯度共同决定更新的速度。
step 6. 对于**每一个**新的观察数据,重复STEP 1到STEP 5(强化学习reinforcement learning) ,或者:对于**每一组**新的观察数据，重复STEP1到STEP5(批量学习batchlearning)。注意:此时的损失函数的值是这一组中所有观察数据产生误差的**和**。
step 7. 当整个训练集都被输入神经网络后,我们称之为**一期**(epoch)训练。我们可以进行更多**期**的训练,继续优化权重,以达到最小化总损失函数的日的。  
# part Ⅱ CNN
*卷积神经网络*  
[*1 keras*](https://github.com/huangzy97/Deep-Learning/blob/master/CNN_keras.py)  
[*2 TensorFlow*](https://github.com/huangzy97/Deep-Learning/blob/master/CNN_tensorflow.py)  
*CNN数据拟合过程：*  
![image](https://github.com/huangzy97/lib/blob/master/picture.gif)
# part Ⅲ NLP
[*自然语言处理*](https://github.com/huangzy97/Deep-Learning/blob/master/NLP.py)  
