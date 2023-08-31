# GPT-From-Scratch
A cutting-edge Generative Pretrained Transformer (GPT) project from scratch, inspired by the groundbreaking research outlined in the widely acclaimed paper "Attention is All You Need" and the latest advancements in the field, including OpenAI's GPT-2 and GPT-3, to create a highly effective and efficient transformer model.

## AIM
The aim of this project is to create a highly effective and efficient transformer model inspired by nanoGPT by Andrej Karpathy, which is a 2.7B parameter transformer model that can be trained on a single GPU. Our model will have ~0.2 million parameters constrained by computational power. The model will be trained on the [tinyshakespeare](https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt) dataset. The model will be trained to generate text, and will be evaluated on the basis of its ability to generate text that is coherent and relevant to the tinyshakespeare.

#### NOTE: This project is developed to showcase my ability to build a generative AI system from scratch using the transformer model.


## Generated Text
```

GLOUCHARD:
We'll man, that's in my wilt owFor his purieny's thunless
Hence'ed say time all own a bottly and in of this men;
The have labht I winling thou knock opprayal no both.

NORTHAM:
For, go!' fair:
What's and and perclain boirs, at it liught'st death.

BRUS:
And your the eith: rantwear, I am fearsulia!

Second Marcius of Rating mod, that long,
Beath from I let in Hearth
Nor
To peation Kich me thou lovest I them--

GLOUCESTES:
Do, I'll Henry, weay pray.

VARCHARD:
And not cout the you that thughful Richard's oachuss,
Tune, againgsted this suith, qune
Were Englain'st thide
they, holy no,
I'll missiled! for have not wear.

ESTA:
No in? I tell,
No, firsters to hear, and to 'And prause outs, basop,
Let we he earth in alout no Scound exemon a in horts inge
This daumanty, been we but clour with
fliehthar way belown you, how tempy the child,
She but hearsel, you dreherect their shalH:
Whence hold voy his poio, there Virition.

PAULINA:
O! this friends upon the god turn's who
man
by mocked sform; she news ore
this interion?
Is not rup of moste
well if more thou to
not ling look mide
Frut to or day tormy me himsons,
Thyday srow yor's someo twere, with a that specty farmses.

QUEEN MENCENTIUS:
That, numble this have milure, and pleave sopemio,
Here lades the vier, specionds:
Bect these welp there
Thou wear Ring Hemer numb grawer, so 'tim mine and sup the it.
Faiout the move go.

MENENIUS:
Go be's brow never fold ne'er
I cheects;
Who detil you instrily him
Is not king this run fless the were's befored,
we kill podd's of sait a for eyers.
O my humble: Herefold to with myself werpoing.

HASTINSS:
Nething it to not man:
Why, outh your quard the that on these I lam and glived,
And it: all my friend the heaven,
Dunf of allam, Herewnipphant bejeation of nconforeing than appian indrice:
Then men is watetural ''With bringleding
Prinnow in no contann and say, thine would,
Nay soure o's chidfes mach'd of lun of him,
Resture to will untry strains prisButy-brincte. But no for I,
Will
```


## Running the Code
### Prerequisites
- Python
- PyTorch
- NumPy

### Training
To train the model, run the following command:
```
python engine.py --train
```

### Generating Text
To generate text using the model, run the following command:
```
python engine.py --generate
```


## Accomplishments
- [x] Prepare required data for training and validation of the model
- [x] Figured out how to implement and use attention using practice_work.py
- [x] Implemented head and multihead neural network
- [x] Implemented feedforward, and block neural network
- [x] Implemented attention using bigram neural network
- [x] Trained bigram neural network on tinyshakespeare dataset
- [x] Successfully generated realistic text using bigram transformer neural network

## Future Work
- [ ] Implement attention using trigram neural network
- [ ] Train n-gram (where n > 2) neural network on a larger dataset (e.g. Wikipedia)
- [ ] Create a model with a larger number of parameters (e.g. 1B)
- [ ] Train the model on a larger dataset (e.g. Wikipedia)
- [ ] Implement a more efficient and effective method of training the model (e.g. distributed training)
- [ ] Create an interactive model that can be used to generate text on demand
- [ ] Create a web app with responsive UI for the model to generate text on demand

## Conclusion
The Bigram transformer model can generate coherent and relevant text in the style of Shakespeare's writing. Though the results are not perfect, they are impressive, considering the limited computation time and hardware used to train the model. It's worth noting that our generative model has only 0.209729 million parameters, significantly fewer than the 175 billion parameters used by the best ChatGPT-3 model. 

This project was developed to demonstrate my understanding of the transformer model and showcase my ability to build a generative AI system from the ground up.