---?image=https://source.unsplash.com/Oaqk7qqNh_c
<!-- Welcome stack
_       __     __                                  __             __  
| |     / /__  / /________  ____ ___  ___     _____/ /_____ ______/ /__
| | /| / / _ \/ / ___/ __ \/ __ `__ \/ _ \   / ___/ __/ __ `/ ___/ //_/
| |/ |/ /  __/ / /__/ /_/ / / / / / /  __/  (__  ) /_/ /_/ / /__/ ,<   
|__/|__/\___/_/\___/\____/_/ /_/ /_/\___/  /____/\__/\__,_/\___/_/|_|  

-->
### Latent Factor Analysis
#### aka Matrix Factorization
+++?image=https://source.unsplash.com/Oaqk7qqNh_c
### Overview
@snap[west]
@ul
* Matrix Factorization
* SVD
* SGD
* surprise
* Our Implementation
@ulend
@snapend
+++?image=https://source.unsplash.com/Oaqk7qqNh_c
### Results Comparsion
Recommendations for user `276847` using...

@div[left-50 fragment]
surpise-svd:
![svdpp results](latent_factor_analysis/pitch_assets/svdpp_recommend.png)
@divend

@div[right-50 fragment]
surprise-svd++:
![fake our model results](latent_factor_analysis/pitch_assets/svd_recommend.png)
@divend

---?image=https://source.unsplash.com/iar-afB0QQw
<!-- Matrix Factorization


    __  ___      __       _         ______           __             _             __  _           
   /  |/  /___ _/ /______(_)  __   / ____/___ ______/ /_____  _____(_)___  ____ _/ /_(_)___  ____
  / /|_/ / __ `/ __/ ___/ / |/_/  / /_  / __ `/ ___/ __/ __ \/ ___/ /_  / / __ `/ __/ / __ \/ __ \
 / /  / / /_/ / /_/ /  / />  <   / __/ / /_/ / /__/ /_/ /_/ / /  / / / /_/ /_/ / /_/ / /_/ / / / /
/_/  /_/\__,_/\__/_/  /_/_/|_|  /_/    \__,_/\___/\__/\____/_/  /_/ /___/\__,_/\__/_/\____/_/ /_/



-->
### Matrix Factorization
+++
#### Matrix Factorization
![mat factorization image](https://cdn-images-1.medium.com/max/1075/1*2i-GJO7JX0Yz6498jUvhEg.png)

+++
### Singular Vector Decomposition

@div[top-20 fragment]
![SVD formula](https://hadrienj.github.io/assets/images/2.8/singular-value-decomposition.png)
@divend

@div[bottom-80 fragment]
![SVD Img](https://research.fb.com/wp-content/uploads/2016/11/post00049_image0001.png)
@divend

---?image=https://source.unsplash.com/jG1z5o7NCq4/
<!-- SGD stack


   _____ __________
  / ___// ____/ __ \
  \__ \/ / __/ / / /
 ___/ / /_/ / /_/ /
/____/\____/_____/  


-->
### Stochastic Gradient Descent

![img of SGD](https://cdn-images-1.medium.com/max/800/1*Sa5kGcZIVNTLjrI8P-YsSQ.gif)
+++
---
<!-- Surprise Stack


                               _         
   _______  ___________  _____(_)_______
  / ___/ / / / ___/ __ \/ ___/ / ___/ _ \
 (__  ) /_/ / /  / /_/ / /  / (__  )  __/
/____/\__,_/_/  / .___/_/  /_/____/\___/
               /_/                       

-->
@snap[north]
### surprise
@snapend
<br />
![image of surprise library](http://surpriselib.com/logo_white.svg)
+++
### SVD vs SVD++
@div[top-50 fragment]
![svd rmse](latent_factor_analysis/pitch_assets/svd_rmse.png)
@divend
@div[bottom-50 fragment]
![svdpp rmse](latent_factor_analysis/pitch_assets/svdpp_rmse.png)
@divend
---
<!-- Our Implementation Stack


   ____                ____                __                          __        __  _           
  / __ \__  _______   /  _/___ ___  ____  / /__  ____ ___  ___  ____  / /_____ _/ /_(_)___  ____
 / / / / / / / ___/   / // __ `__ \/ __ \/ / _ \/ __ `__ \/ _ \/ __ \/ __/ __ `/ __/ / __ \/ __ \
/ /_/ / /_/ / /     _/ // / / / / / /_/ / /  __/ / / / / /  __/ / / / /_/ /_/ / /_/ / /_/ / / / /
\____/\__,_/_/     /___/_/ /_/ /_/ .___/_/\___/_/ /_/ /_/\___/_/ /_/\__/\__,_/\__/_/\____/_/ /_/
                                /_/                                                              

-->
### Our implementation
+++
