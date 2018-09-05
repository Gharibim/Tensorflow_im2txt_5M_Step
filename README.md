# Tensorflow_im2txt_5M_Step

[Click to Download from Dropbox](https://www.dropbox.com/s/87dm6ly33845p72/im2txt_5M.zip?dl=0)</br>

Original Repo: [Tensorflow_im2txt](https://github.com/tensorflow/models/tree/master/research/im2txt)</br>

This model has been trained 5000000 steps using Tensorflow 1.9

If you get any error related to:</br>
`Key lstm/basic_lstm_cell/bias not found in checkpoint`</br>
Make sure you have Tensorflow 1.9 or later (I have not tried it on earlier versions)</br> 

If you get any error related to the word_counts then make sure they look like:</br>
`a 969108`</br>
`</S> 586368`</br>
`<S> 586368`</br>
not:</br>
`b'a' 969108`</br>
`b'</S>' 586368`</br>
`b'<S>' 586368`</br>
