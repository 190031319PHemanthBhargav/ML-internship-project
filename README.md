# ML-internship-project
Internship project Suvidha Foundations
Machine learning Internship Project from Suvidha Foundations.
the project is on Video Summarization using attention based encoder-decoder
Video summarization is one of the promising techniques to address this challenge. Its goal is to produce a compact yet comprehensive summary to enable an efficient
browsing experience. An ideal video summarization is that can provide users the maximum information of the target video with the shortest time. It is also useful for many other practical
applications, such as video indexing, video retrieval,and event detection.
An Attentive encoder-decoder framework for Video Summarization, named AVS. It is a supervised-based video summarization framework, which mimics the way of selecting the keyshots of human. 
To the best of our knowledge, this attentive encoder-decoder framework has not previously proposed for implementing video summarization.
It investigates the attention-based LSTM mechanism in the AVS framework, and develops two approaches to generate the video summarization. One is based on additive
attention mechanism named A-AVS, the other is based on multiplicative attention mechanism, named M-AVS.
Extensive experiments are conducted on two popular video summarization datasets, including both the edited and raw video datasets. The results show the proposed M-AVS
and AAVS approaches consistently outperform the state-of-the-art ones by at least 0.8%, 3.1%on SumMe and TVSum datasets, respectively. 
These promising results verify the effectiveness of the proposed AVS framework.

# Model we used
The framework consists of two components: an encoder-decoder model and a keyshot selection model. The encoder-decoder part measures the importance of each frame. The key shots selection model helps us to convert frame-level importance scores into shot-level scores and generating summary accounting to the threshold budget which we specify.

More details of the model can be known by skimming through the code.

# generated output summary
To generate the summary of a video, run

 python gen_summary.py --h5_path --json_path --data_root --save_dir --bar

Research paper used for project:  https://www.researchgate.net/publication/319415984_Video_Summarization_With_Attention-Based_Encoder-Decoder_Networks

the github main contributor for project: https://github.com/yashkolli
