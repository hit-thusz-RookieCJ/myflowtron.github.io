## 语音变化程度控制对比实验

### 合成样例展示

| Model     |          Condition          | Audio                                                        | Mel-spectrogram                                              |
| :-------- | :-------------------------: | :----------------------------------------------------------- | ------------------------------------------------------------ |
| Flowtron  |       $\sigma = 0.0$        | <audio controls><source src="./data/experiment1/Audio/flowtron_0.0.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <img src="./data/experiment1/Mel-spectrogram/Flowtron_0.0.png" alt="flowtron_0.0" style="zoom: 25%;" /> |
| Flowtron  |       $\sigma = 0.5$        | <audio controls><source src="./data/experiment1/Audio/flowtron_0.5.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <img src="./data/experiment1/Mel-spectrogram/Flowtron_0.5.png" alt="flowtron_0.5" style="zoom: 25%;" /> |
| Flowtron  |       $\sigma = 1.0$        | <audio controls><source src="./data/experiment1/Audio/flowtron_1.0.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <img src="./data/experiment1/Mel-spectrogram/Flowtron_1.0.png" alt="flowtron_0.5" style="zoom: 25%;" /> |
| Tacotron2 | $p \in \{0.45,0.5,0.55 \} $ | <audio controls><source src="./data/experiment1/Audio/tacotron2.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <img src="./data/experiment1/Mel-spectrogram/Tacotron2.png" alt="flowtron_0.5" style="zoom: 25%;" /> |



### F0 Contours对比图

|               Condition                |                         F0 Contours                          |
| :------------------------------------: | :----------------------------------------------------------: |
|       Flowtron   $\sigma = 0.0$        | <img src="./data/experiment1/F0-Contours/Flowtron_0.0.png" alt="flowtron_0.0" style="zoom: 75%;" /> |
|       Flowtron   $\sigma = 0.5$        | <img src="./data/experiment1/F0-Contours/Flowtron_0.5.png" alt="flowtron_0.0" style="zoom: 75%;" /> |
|        Flowtron  $\sigma = 1.0$        | <img src="./data/experiment1/F0-Contours/Flowtron_1.0.png" alt="flowtron_0.0" style="zoom: 75%;" /> |
| Tacotron2  $p \in \{0.45,0.5,0.55 \} $ | <img src="./data/experiment1/F0-Contours/Tacotron2.png" alt="flowtron_0.0" style="zoom: 75%;" /> |





## 样本间插值实验

