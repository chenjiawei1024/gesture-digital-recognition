# gesture-digital-recognition
一个基于mediapipe实现手势数字识别机器学习项目
### create_train_set.py
使用mediapipe和调取摄像头获取每帧生成坐标集的过程(np.array)
### train.py
根据坐标集生成训练集,并使用tensorflow添加3+3层构成神经网络。（使用RNN的lstm单元优化方法）
### main.py
开启摄像头，测试

## 运行顺序 create_train_set -- train -- main
1. 导入并安装依赖项。 
2. 使用mediapipe的特征点检测
3. 提取特征点坐标值 
4. 设置收集的文件夹。 
5. 收集和测试的关键点值 
6. 预处理数据，创建标签和特性。 
7. 建立和训练LSTM中立网络 
8. 作出预测 
9. 保存权重
10. 使用混淆矩阵和准确度进行评估 
11. 实时测试。

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=chenjiawei1024&count_private=true)
