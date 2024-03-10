## Intro

### Model generatywny (ang. *generative*)
$$\Large{P_\theta(y,x):\theta \in \Theta}$$
### Model dyskryminujący (ang. *discriminative*)
$$\Large{P_\theta(y|x):\theta \in \Theta}$$

## Binary Cross Entropy
$$\Large{\hat{L}_w = -\frac{1}{N} \sum_{i=1}^{N} \left[y_i \log(\hat{y}_i) + (1 - y_i) \log(1 - \hat{y}_i)\right]}$$
