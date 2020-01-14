Read `online_bl.csv` from  `data_input` folder to answer **question 1-3**. You may find it helpful to use `parse_dates=[__]` while calling the `read_csv()` function. The data are all items listed for sale on the popular e-commerce website bukalapak.com within a specific set of categories. 


Perform  necessary data preparation steps and use the exploratory data analysis techniques you've acquired to answer the questions.

1. How many unique sub categories are there in `online_bl` dataset? Do we have more "detergent" listings or "sugar" listings within our data?
    - [ ] 2, with more "detergent" than "sugar"
    - [ ] 2, with "detergent" and "sugar" having equal listings
    - [ ] 3, with more "sugar" than detergent
    - [ ] None of above is correct
    
2. In which scale do we have our **detergent** stock the most?
    - [ ] 1 kg
    - [ ] 1.8 kg
    - [ ] 5 kg
    - [ ] 800 gr

3. Which month has the **lowest average price** (`mean` on `price_original`) for detergent products (1.8kg and 800gr respectively) listed for sale on Bukalapak? Are they the same month?
    - [ ] Both 1.8 kg and 800 gr detergents lowest price were in August
    - [ ] Both 1.8 kg and 800 gr detergents lowest price were in October
    - [ ] 1.8 kg detergents: Lowest in August, 800 gr: Lowest in October
    - [ ] 1.8 kg detergents: Lowest in August, 800 gr: Lowest in July    
        
Read `techcrunch.csv` from `data_input` folder to aswer **question 4-6**, a dataset that stores fundraising rounds and amounts from startup companies of different categories around the US.

4. Using `techcrunch.csv`, which `category` raised the most amount in funding (`raisedAmt`) on average (use the `median`)?
    - [ ] `mobile`
    - [ ] `cleantech`
    - [ ] `biotech`
    - [ ] `consulting`

 
5. In which period does Friendster gain their highest raised amount of funding?
    - [ ] 2008-08
    - [ ] 2002-12
    - [ ] 2006-08
    - [ ] 2012-01

6.  Among all companies in San Francisco, which of the following are **not** among the top 5 most funded ( has highest **total** `raisedAmt`) companies? 
    - [ ] `OpenTable`
    - [ ] `Friendster`
    - [ ] `Facebook`
    - [ ] `Snapfish`
  