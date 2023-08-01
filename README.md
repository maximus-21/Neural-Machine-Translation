# Neural-Machine-Translation
This repo serves as building of machine translation model using se2seq model in Pytorch.<br>

`Translation`: German to English<br>
`Dataset`: Multi30k containing English and German captions for images from Flickr<br>
`Tokenization`: sentencepiece<br>
`Prediction`: Greedy

## Baseline Model
LSTM based se2seq model<br>

`Encoder`: Bidirectional LSTM with each direction having 2 layers <br>
`Decoder`: 2 layer LSTM<br>
`Accuracy`: 50.50%<br>
`Bleu Score`: 18.76<br>

*Baseline model sample predictions:*

![Screenshot from 2023-08-01 15-46-25](https://github.com/maximus-21/Neural-Machine-Translation/assets/98597396/b54f54e4-127a-45b1-917e-17ee5801d448)

## Seq-to-Seq model with attention
*[Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)*<br>

`Encoder`: Bidirectional LSTM with each direction having 2 layers <br>
`Decoder`: 2 layer LSTM with attention mechanism<br>
`Accuracy`: 67.70%<br>
`Bleu Score`: 38.45<br>

*Attention model sample predictions:*

![Screenshot from 2023-08-01 15-50-31](https://github.com/maximus-21/Neural-Machine-Translation/assets/98597396/ca68ee49-ec14-48b1-812a-663885616fd3)

