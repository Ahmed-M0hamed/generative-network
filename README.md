# generative networks 

generative networks trying to model the input distribution and this can be done through two main 
components 1- generator 2- discriminator 

- first we train the discriminator 
we give the generator noise as input and we get fake data as output and we cocatenate this fake data which will be labeled (0) with real data labeled (1) and pass them through the discriminator to train him to detect if it is real or not  
- after that we train the advirseal network and we freeze the discriminator parameters while doing that 

## gans networks 
there a lot of proposed models and we will discuss some of them 

- DCGAN  => ([notebook](https://github.com/Ahmed-M0hamed/generative-network/DCGAN.ipynb))
- CGAN   => ([notebook](https://github.com/Ahmed-M0hamed/generative-network/CDGAN.ipynb))
- ACGAN  => ([notebook](https://github.com/Ahmed-M0hamed/generative-network/ACGAN.ipynb))

### this repo is inspired by Advanced deep learning with tensorflow2 and keras book with some changes i commit trying to make it easier or to represent my own understanding 





