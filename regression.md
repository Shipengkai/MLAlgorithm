# regression
    stock market forecast(发财了)
    self-driving car
    recommendation(bilibili, taobao)

# example application:
    estimating the combat power of a pokemon after evolution
    f(pokemon) = CP after evolution:
        input:
            x_cp
            x_s
            x_hp
            x_w
            x_h
        output:
            y
# step 1: Model
    linear model: y = b + ∑(w * x_cp)
        b:bias
        w:weight
# step 2: Goodness of Function
    Loss function L：
        L(f) = L(w, b) = Σ(真实值 - 预测值)²
# step 3： Gradient Descent
    手写