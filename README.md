# dataset
dataset of CNN and U-net for earthquake classification and phase picking
This is the preprocessed dataset for the paper:

1.赵明,陈石,Dave.A.Yuen,2019,基于深度学习卷积神经网络的地震波形自动分类与识别,地球物理学报，62(1),待刊

2.赵明，陈石，房立华，David A Yuen. 2019. 基于U形全卷积神经网络的震相识别与到时拾取方法研究. 地球物理学报，待刊.

or english cite:

1.Zhao M,Chen S,Dave Yuen. 2019. Waveform classification and seismic recognition by convolution neural network. Chinese J. Geophys. (in Chinese),62(1),in press.

2.Zhao M, Chen S, Fang Lihua, David A Yuen.  2019. Earthquake phase arrival auto-picking based on   U-shaped convolutional neural network. Chinese J. Geophys. (in Chinese), in press.

The dataset includes:

1.stlist.txt : list the stations where the data from.

2.wenchuan_aftershocks_picks_2008_6_to_9.csv : UTC timestamps for over 25000 P and S picks of the wenchuan aftershocks （Highly credible）,you can use it to build positive samples for CNN dataset,or U-net dataset. Paper 1 and 2 will give you some instruction on how to do that.For CNN dataset you can also refer to https://github.com/mingzhaochina/ConvNetQuake.

3.wenchuan_bold_catalog.csv:this is used to build negative samples (noises) of CNN.You need to avoid these timestamps in a range,let's say,[-60s,+60s] in the continious data. 

We cannot provide any high frequency continuous waveform data.These data belongs to CEA and CEA has the final say on how to use the data.

Besides, it is too large (more than 70GB)

If anyone has question,comments,advices,please leave a message.We remain open to cooperation and discussion.

