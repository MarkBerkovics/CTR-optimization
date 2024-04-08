# CTR-optimization

In this project I'm helping a company that is not happy with the performance of their recent marketing initiatives. They have been running marketing initiatives on various websites, YouTube, Facebook, Instagram, and other platforms, but these initiatives have not been successful.\
My job is to analyze the data, understand the problem and provide solutions for increasing click through rates (CTR). 

After running some exploratory data analysys I've found that:
🔎 After 40 days of running adds CTR decreases dramatically. Campaigns shoud be turned off after a maximum of 40 days.\
🔎 Adds with photos of the dimentions 300X250 pixels get significantly higher CTR.\
🔎 The add agency with the id 353 had significantly better CTR, it is advised to work with that agency.\
🔎 Media costs of up to 200 USD yealded better CTR than more expensive ones.\
🔎 Campaings that ran on weekdays out performed ones that ran on weekends.\

An XGBregressor was trained on the data to give better predictions for future campaigns.\
The fine tuned model reachen a RMSE of 1.6
