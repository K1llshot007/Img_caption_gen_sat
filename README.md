# Img_caption_gen_sat
Image Caption Generator based on the paper Show Attend and Tell with changes done to LSTM and Feature Extractor in TensorFlow

# Dataset used :

Flickr30k Dataset : https://drive.google.com/file/d/1FNVlyMc4xRePZZMuCm1fFCDJZAyXr1CL/view?usp=sharing

Google-news-vectors-negative-300 : https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/view?usp=sharing&resourcekey=0-wjGZdNAUop6WykTtMip30g

# Library Used :

Tensorflow

# Training:

Trained for 20 epochs, 1500 batch size in each epoch

# Changes Done:

Changed the feature extractor from InceptionV3 to Xception

Changed the orignal LSTM, to one where the cell state is set to 0 after every pass through


# Bleu scores

0.2890064862060426 - Xception - Original LSTM - Decoder 2

0.2621547947179256 - Xception - Changed LSTM - Decoder 3

0.28369470634644833 - InceptionV3 - Original LSTM - Decoder 5


# Important Links

Google drive link for our saved data : https://drive.google.com/drive/folders/1nqEDl1WHxc_02RvnhYl5kcyU8Y3SLWW9?usp=drive_link

Google Colab Link for our code : https://colab.research.google.com/drive/1L65WBAqzTFwX22OCEW4C8fYRkbEv9n1s?usp=sharing

A very recent paper to demonstrate what BLEU scores look like : https://journalofbigdata.springeropen.com/articles/10.1186/s40537-022-00571-w

The paper our work is based on : https://arxiv.org/pdf/1502.03044

The code repository that we are using for our code : https://github.com/vinayaksharmagh/IMcap/tree/master


