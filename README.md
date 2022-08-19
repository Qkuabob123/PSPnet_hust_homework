# PSPnet_hust_homework
PSpnet网络实现Weizmann Horse数据集语义分割
# 使用环境
python3.9.7 pytorch1.11.0 pillow cv2
# 模型网盘地址
链接：https://pan.baidu.com/s/1e5phEKtUZa5-fH0SdlSq9g 
提取码：r98w
# 使用说明
代码中调用数据集使用的是绝对地址，运行前先要构建修改weizmann_horse_db中训练、测试文件的绝对地址。  
weizmann_horse_db文件中含有horse_test，horse_train,mask_test,mask_train 4个文件 训练集图片数为278，测试集图片数为49 比例为0.85：0.15  
results文件中含已训练网络的输出可视化结果  
MIOU_BIOU.ipynb文件构建计算MIOU等指标函数  
train.ipynb 文件用于训练网络和输出可视化结果  
importipynb.py文件用于各个ipynb文件的相互调用  
train文件运行后会生成pspnetepoch_100.pkl文件保存训练模型，还有hhpath文件保存botensorboard相关文件
# 部分预测可视化结果图

<img src=".\results\res1.png"  title="预测"/> 
<img src=".\results\res3.png"  title="预测"/>
<img src=".\results\res2.png"  title="预测"/>
