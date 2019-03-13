### Transformer

1. Multihead attention:
- Attention: 这里是把query和key做矩阵乘法，scaled，然后再和value做加权，得到一个Tq * d_k的矩阵，每一行是对应query的attention
