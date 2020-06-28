## 项目介绍
小组成员基于数据集tnews_public，分别采用了fasttext，textrcnn，dpcnn，textrnn等多种模型来实现文本分类，并与所给的textcnn模型进行对比。
以上是textrnn部分.

## 环境
python 3.7 
sklearn 0.21.2 
tensorboardX 2.0 
torch 1.1.0
torchvision 0.3.0  

## 训练并测试：
python train.py --config cnn.ini
python test.py --config cnn.ini
python run.py --model textRnn

## 参数
textrnn模型都在models目录下，超参定义和模型定义在textrnn.py。
textcnn参数在cnn.ini中,模型定义在model.py中.

## 参考文献
[1]Zhang Y, Wallace B. A sensitivity analysis of (and practitioners’ guide to) convolutional neural networks
for sentence classification[J]. arXiv preprint arXiv:1510.03820, 2015.&emsp;
[2]Kim Y. Convolutional neural networks for sentence classification[J]. arXiv preprint arXiv:1408.5882, 2014.
Liu P, Qiu X, Huang X. Recurrent neural network for text classification with multi-task learning[J]. arXiv
preprint arXiv:1605.05101, 2016.&emsp;
[3]Lai S, Xu L, Liu K, et al. Recurrent convolutional neural networks for text classification[C]//Twenty-ninth
AAAI conference on artificial intelligence. 2015.&emsp;
[4]Johnson R, Zhang T. Deep pyramid convolutional neural networks for text categorization[C]//Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics(Volume 1: Long Papers). 2017: 562-570.&emsp;
