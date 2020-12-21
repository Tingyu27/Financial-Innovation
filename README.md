# Financial-Innovation
NTU 109-1 Financial Innovation
***
## HW1: collect at least two customized rule-based patterns with indices
* Use Hanging man, hammer, dark cloud cover, and piercing pattern as the detecting signals
[zip file](https://github.com/Tingyu27/Financial-Innovation/blob/master/HW1_R08723024_%E9%83%AD%E5%BA%AD%E5%A6%A4.rar)
[folder](https://github.com/Tingyu27/Financial-Innovation/tree/master/HW1_R08723024_%E9%83%AD%E5%BA%AD%E5%A6%A4)
## HW2: use LSTM and CNN model to classify MNIST dataset with at least 90%
* LSTM model accuracy is 0.9560
* CNN model accuracy is 0.9889
[zip file](https://github.com/Tingyu27/Financial-Innovation/blob/master/HW2_R08723024_%E9%83%AD%E5%BA%AD%E5%A6%A4.rar)
[folder](https://github.com/Tingyu27/Financial-Innovation/tree/master/HW2_R08723024_%E9%83%AD%E5%BA%AD%E5%A6%A4)
## HW3: use LSTM and CNN model to classify customized candlestick pattern (at least 3 classes)  
* Under LSTM model, 50 iterations does better than 10 iterations.
* Overall, the prediction accuracy of CNN is better than that of LSTM under 10 iterations.
[zip file](https://github.com/Tingyu27/Financial-Innovation/blob/master/HW3_R08723024_%E9%83%AD%E5%BA%AD%E5%A6%A4.rar)
[folder](https://github.com/Tingyu27/Financial-Innovation/tree/master/HW3_R08723024_%E9%83%AD%E5%BA%AD%E5%A6%A4)
***
## Week 1
[課程內容](https://docs.google.com/presentation/d/e/2PACX-1vTAQ0ns9cSIGCE4Ypfysfb0hEMVPQZmEzAgJWAyAzpU3xwQTzC5hwuVR2O4SXUHOIdjfWfe7qQTyINl/pub?start=false&loop=false&delayms=3000&slide=id.p)
***
## Week 2
演講一：壽險發展轉型及保險科技

[壽險經營管理實務研討_09.24演講心得](https://github.com/Tingyu27/Financial-Innovation/blob/master/%E9%87%91%E8%9E%8D%E5%89%B5%E6%96%B0%E5%BF%83%E5%BE%97%E4%B8%80.pdf)
***
## Week 5
演講二：客戶行為大數據分析及運用

[壽險經營管理實務研討_10.15演講心得](https://github.com/Tingyu27/Financial-Innovation/blob/master/%E5%A3%BD%E9%9A%AA%E7%B6%93%E7%87%9F%E7%AE%A1%E7%90%86%E5%AF%A6%E5%8B%99%E7%A0%94%E8%A8%8E_10.15%E6%BC%94%E8%AC%9B%E5%BF%83%E5%BE%97.pdf)
***
## Week 6
演講三：數位時代之銀行保險及企業保險

[壽險經營管理實務研討_10.22演講心得](https://github.com/Tingyu27/Financial-Innovation/blob/master/%E5%A3%BD%E9%9A%AA%E7%B6%93%E7%87%9F%E7%AE%A1%E7%90%86%E5%AF%A6%E5%8B%99%E7%A0%94%E8%A8%8E_10.22%E6%BC%94%E8%AC%9B%E5%BF%83%E5%BE%97.pdf)
***
## Week 7
### QuantLib-Python Object

[講義](https://docs.google.com/presentation/d/e/2PACX-1vRH1IQE4XEWN9frgTXbtE22KQBd8PsIp-WabfkGLMYEkchQ5X4BoUmzVtGeLOANUQNBA755vDlESPs1/pub?start=false&loop=false&delayms=3000&slide=id.g9d4832b8a0_0_56)

#### Bonds related Code
* set up a bond

  ql.MakeSchedule(effectiveDate, terminationDate, frequency)

  ql.FixedRateLeg(schedule, dayCount, nominals, fixedRate)  `build a sequence of fixed rate coupon`

  ql.Bond(settlementDays`[diff btw settlement day & trade day]`, calendar, issueDate, coupons)
* set up a zero-coupon bond

  ql.ZeroCouponBond(settlementDays, calendar, faceAmount, maturityDate)
* calculate Bond's YTM

  X.bondYield(cleanPrice, dayCounter, compounding, frequency)
* calculate Bond's full price

  X.dirtyPrice(yield, dayCount, compounding, frequency)
#### Quantlib plotting
* Neet to convert data from `tuple` to `list`
***
## Week 8
### Quantopian Tutorials
[講義](https://docs.google.com/presentation/d/e/2PACX-1vSsVHyOz-PNWlKyg8J1Ayyv6T2D_6UX-KiNWuls_mzlwnOsAIVcxGAj6YqXIMlOjS-6sLYenGEwxc19/pub?start=false&loop=false&delayms=3000&slide=id.g9d4832b8a0_0_56)

#### Algorithmic Trading
* The prediction accuracy of the stock price cannot guarantee profits.
* Add rule-based filter signal to define when to trade! 
* Example: Moving Average Strategy Code
#### Reinforcement Learning for Trading
* Reinforcement learning does not predict price behaviors in the learning process.
***
## Week 9
### Target Redemption Forward
[講義](https://docs.google.com/presentation/d/e/2PACX-1vQVcx7YvFAdAZadihCZiQAzAhiDJTwTkFwlqKeyZsXJ-wD9eBRz9APAbNhseJb20xtGxJ2GFqo0tnn0/pub?start=false&loop=false&delayms=3000&slide=id.g9d4832b8a0_0_56)

#### Target Redemption Forward Payoff
#### FinTech 創新主題
***
## Week 11
### HW & Final Project
[講義](https://docs.google.com/presentation/d/e/2PACX-1vTHPRCRwOuu_doq868LSMBzsriPAWGebXCWgQJ5crn-OUheIjmoTVUpWjIT2bHNCeGs_vtwcX2bEF7Z/pub?start=false&loop=false&delayms=3000&slide=id.g9d4832b8a0_0_56)
***

