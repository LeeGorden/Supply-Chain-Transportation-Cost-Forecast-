<br>

## <div align="center">Supply Chain Competition</div>

<details open>
<summary>Introduction</summary>

The purpose of this project is to forecast transportation cost using multiple data gathered from different resources.

</details>

<details open>
<summary>Step</summary>
The whole project include the following steps

<details open>
<summary>Data Preprocess</summary>
  
- Data Preparation:

  (1)  Data Cleaning. The original data set combined both  Report 2 & Report 3 contains 10078  samples. After deleting in null-value  sample, abnormal-value sample and  removing samples with possible noise  interrupting models, 5979 samples were  remained including 80+ predictors. The  cleaned data set still cover almost all the  information in important dimension like  Actual Freight Cost, Miles, Gross Weight etc. Credibility of the cleaned data set is  ensured.

  (2)  Derived & Additional Variables. To fit the model more accurately, we  include some derived and additional variables including Season,  Route Highway Density,  Weekly Diesel Price.

- Feature Engineering: 

  In this project, random forest feature filtering is applied. From the Random-Forest model with 100  decision trees in it, 15 possible predictors  were chosen, leading by Miles, Diesel  Price, Route Highway Density, Gross  Weight, Season, Year. These feature  covers more than 95% of contribution of  importance.

  ![image](https://user-images.githubusercontent.com/72702872/168720627-1ab8212f-3ceb-4159-a1f8-27474dfce33d.png)

</details>  

<details open>
<summary>Descriptive Analysis</summary>

- Feature Distribution:
  
  ![image](https://user-images.githubusercontent.com/72702872/168721380-ab392343-6c9f-4fcc-9644-bcb298e47c80.png)
  
  ![image](https://user-images.githubusercontent.com/72702872/168721423-0e073eba-c6b4-4feb-966a-6dc03bb2b4df.png)

  ![image](https://user-images.githubusercontent.com/72702872/168721461-07fb7a16-fbfa-4e4e-97a4-06d6bf54ec4f.png)

- Correlation:
  
  ![image](https://user-images.githubusercontent.com/72702872/168721533-a0534e12-955b-4615-b564-7aa3139106e5.png)

</details>   

<details open>
<summary>Model Training</summary>
  
- In this case, LASSO and Random Forest is used.

- For hyper tuning, grid-search is applied.

</details>

<details open>
<summary>Result</summary>

<details open>
<summary>Model Performance</summary>

- MAPE is used to calculate relative miss of predicted value compared to true value: 
  
  ![image](https://user-images.githubusercontent.com/72702872/168723465-14784f89-051f-452f-b5fb-7a0498f09e57.png)

  ![image](https://user-images.githubusercontent.com/72702872/168722154-738f520b-0e67-4031-808c-0d384164009a.png)

  ![image](https://user-images.githubusercontent.com/72702872/168722327-35e1a814-75dc-4b1e-9333-d56c216f723f.png)

- Final model is decided based on grid-search, considering accuracy and time consumed for each training: 
  
  ![image](https://user-images.githubusercontent.com/72702872/168723556-90aff976-d478-4165-ae64-7c01b75b7d6f.png)

</details>

<details open>
<summary>Reference</summary>

[1] World Meteorological Organization (WMO). 2009. Weather and Climate Change 
Implications for Surface Transportation in the USA. Available at https://public.wmo.int/ 
as of 2009.
  
[2] United States Department of Transportation. 2020. Transportation Statistics Annual 
Report 2020 Available at https://fdd.bts.gov/freight-data-dictionary/ as of 2020
  
[3] U.S. Energy information Administration. 2020. Available at https://www.eia.gov/ as of 
2020
  
[4] Quora Answer Board. 2020 Available at https://www.quora.com/How-many-milescan-the-average-semi-truck-pull-a-full-load-without-refueling as of 201

</details>

</details>

## <div align="center">Contact</div>

email: likehao1006@gmail.com

LinkedIn: https://www.linkedin.com/in/kehao-li-06a9a2235/

ResearchGate: https://www.researchgate.net/profile/Gorden-Li

<br>

