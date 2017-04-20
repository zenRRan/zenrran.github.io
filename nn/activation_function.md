#####1.sigmoid
函数：f(z) = 1 / (1 + exp( − z))
导数：f(z)' = f(z)(1 − f(z))
![sigmoid](../image/sigmoid.png)
#####2.tanh
函数：f(z) = tanh(z)
导数：f(z)' = 1 − (f(z))^2
![tanh](../image/tanh.png)
#####3.relu
f(x)=max(0,x)
![relu](../image/relu.png)
#####4.softmax
$f(\vec{x})_i ~=~ \frac{e^{x_i}}{\sum^K_{k=1} e^{x_k}}~~~$ for i,...,k