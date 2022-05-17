<br>

## <div align="center">Supply Chain Competition</div>

<details open>
<summary>Introduction</summary>

The purpose of this project is to forecast transportation cost using multiple data gathered from different resources.

</details>

<details open>
<summary>Step</summary>
The whole project include the following steps

- Data Preparation:

  (1)  Data Cleaning. The original data set combined both  Report 2 & Report 3 contains 10078  samples. After deleting in null-value  sample, abnormal-value sample and  removing samples with possible noise  interrupting models, 5979 samples were  remained including 80+ predictors. The  cleaned data set still cover almost all the  information in important dimension like  Actual Freight Cost, Miles, Gross Weight etc. Credibility of the cleaned data set is  ensured.

  (2)  Derived & Additional Variables. To fit the model more accurately, we  include some derived and additional variables including Season,  Route Highway Density,  Weekly Diesel Price.

- Feature Engineering: 

  In this project, random forest feature filtering is applied. From the Random-Forest model with 100  decision trees in it, 15 possible predictors  were chosen, leading by Miles, Diesel  Price, Route Highway Density, Gross  Weight, Season, Year. These feature  covers more than 95% of contribution of  importance.

  ![image-20220516213139091](C:\Users\LiGoudan\AppData\Roaming\Typora\typora-user-images\image-20220516213139091.png)

- Descriptive Analysis:

  

</details>

<details open>
<summary>Result</summary>

<details open>
<summary>Descriptive Analysis</summary>

- The whole report:
  [Prediction on Soybean Variety Yield an application.pdf](https://github.com/LeeGorden/Prediction-on-Soybean-Variety-Yield-and-apply-to-Soybean-Variety-Selection/files/8703041/Prediction.on.Soybean.Variety.Yield.an.application.pdf)

- ![image](https://user-images.githubusercontent.com/72702872/168672066-dcd3c8eb-11b0-4ffb-b2de-0cbfe7f7399f.png)

- ![image](https://user-images.githubusercontent.com/72702872/168672253-9e58dcfc-2e40-4415-9a68-ff3a174ddc67.png)

- ![image](https://user-images.githubusercontent.com/72702872/168672386-20f37ec9-3daf-4e64-b317-0fccc52e0cec.png)

- ![image](https://user-images.githubusercontent.com/72702872/168672921-57764f2f-31e7-474b-9ee8-20ad34f6ad2e.png)
  
- Cluster result(K-means) of different types of Soybean based on latitude and longitude: 
  ![image](https://user-images.githubusercontent.com/72702872/168672980-3ece86ec-761a-49f6-bcfe-8af77c856a3e.png)
  
- ![image](https://user-images.githubusercontent.com/72702872/168673502-9d7cf5b0-4e66-4099-8c38-857e5d288ae1.png)

</details>

<details open>
<summary>Predictive Analysis</summary>

- Performance of different models:
  ![image](https://user-images.githubusercontent.com/72702872/168673748-9a288c0c-3a9f-47ee-8188-a4ccbde63a0c.png)
  

</details>

<details open>
<summary>Prescriptive Analysis</summary>

Now, we have the best model to predict each kind of Soybean's yield based on different weather condition. Based on the model, the next step is to utilize prescriptive analysis to find out the best combination of Soybeans to achieve best yield for future years.

Since the weather condition of future is not determined, we can estimate weather condition distribution of temperature, precipitation and radiation to find out the best combination with highest Yield / σ (In this case, we treat each kind of Soybean as a stock, the purpose is to optimize the combo with the goal to maximize Shap ratio = Expected Return / σ).

- Based on weather condition history, the distribution of temperature, precipitation and radiation are as follow: 
  ![image](https://user-images.githubusercontent.com/72702872/168674274-1ab7154d-677d-4c99-ae1c-a399f6802f2e.png)

- According to the distribution of weather condition above, corresponding yield of chosen star Soybeans are as follows:
  ![image](https://user-images.githubusercontent.com/72702872/168675234-6b3c3ab0-5a73-4d2a-a536-8e6077051e2c.png)

- The **Markowitz** bullet curve is as follow:
  
  ![image](https://user-images.githubusercontent.com/72702872/168677923-9745e923-4188-4600-bb10-96eb922d64af.png)
  
  The best combination appears at the tangent of the curve.
  

</details>

<details open>
<summary>Reference</summary>

[1]. Hunger and Food Shortages, Kelly Kean Sharp

[2]. Washington University in St Louis 500S Guidline

[3]. INFLUENCE OF CROPPING SYSTEM INTENSITY ON YIELD AND YIELD 
COMPONENTS OF NEW SOYBEAN GENOTYPES[J], Ana POSPIŠIL, Milan 
POSPIŠIL, Svjetlana MATOTAN, Dario JAREŠ, Bogdan KORIĆ, Cereal 
Research Communications, Vol. 37, Supplement: Proceedings of the VIII. AlpsAdria Scientific Workshop, 27 April–2 May 2009, Neum, Bosnia-Herzegovina 
(March 2009), pp. 41-44

[4]. Trophic cascades in agricultural landscapes: indirect effects of landscape 
composition on crop yield[J]. Heidi Liere, Tania N. Kim, Benjamin P. Werling, 
Timothy D. Meehan, Douglas A. Landis, Claudio Gratton Ecological 
Applications, Vol. 25, No. 3 (April 2015), pp. 652-661

[5]. Cultural Strategies for Managing Weeds and Soil Moisture in Cover Crop 
Based No-Till Soybean Production[J].M. Scott Wells, S. Chris Reberg-Horton, 
Steven B. Mirsky, Weed Science, Vol. 62, No. 3 (July-September 2014), pp. 
501-511

[6]. On the Markowitz mean–variance analysis of self-financing portfolios[R];
Bai Zhidong, Liu, Huixia, Wong, Wing-Keung; KLAS, Math & Stat, Northeast 
Normal University and DSAP & RMI, National University of Singapore, 
Singapore | Department of Statistics, National University of Singapore, 
Singapore | Department of Economics, Hong Kong Baptist University, Hong 
Kong

</details>

</details>

## <div align="center">Contact</div>

email: likehao1006@gmail.com

LinkedIn: https://www.linkedin.com/in/kehao-li-06a9a2235/

ResearchGate: https://www.researchgate.net/profile/Gorden-Li

<br>
