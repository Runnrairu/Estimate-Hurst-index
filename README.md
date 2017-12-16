# ハースト指数の推定
## 非整数ブラウン運動とは
Hは開区間(0,1)上の実数とする。  
任意の時刻t,sに対して、次の平均・共分散関数を持つガウス過程を、ハースト指数Hを持つ非整数ブラウン運動という。
<img src="https://latex.codecogs.com/gif.latex?E[B_t^H]=0" />  
<img src="https://latex.codecogs.com/gif.latex?R(t,s):=E[B_t^HB_s^H]=\frac{1}{2}v^2_{2H}[t^{2H}+s^{2H}-|t-s|^{2H}]" />  
ただし、<img src="https://latex.codecogs.com/gif.latex?v^2_{2H}:=" />      
これはブラウン運動の性質である「独立増分性」を外した一般化となっている。H<1/2のときはこれまでの動きと負の相関を持ち、H>1/2の時は正の相関を持つ。H=1/2の時は通常のブラウン運動。

      
## 参考文献
[1]Francesca Biagini,Yaozhong Hu,Bernt Øksendal,Tusheng ZhangStochastic Calculus for Fractional Brownian Motion and Applications.(2008)  
[2]Inference on the Hurst Parameter and the Variance of Diffusions Driven by Fractional Brownian Motion.Corinne Berzin,Alain Latour,José R. León(2014)
