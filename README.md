## Steps 
- getting the link from Amazon website and locating elements: product name and price
- Fetching the element using selenium syntax  [See documentation](https://selenium-python.readthedocs.io/locating-elements.html)
- Checking if the price meets the budget
- Sending an e-mail alert using smtplib 

# Amazon Price Tracker using Python, Selenium, and AWS EC2  

This project is an **automated Amazon Price Tracker** built with **Python and Selenium**.  
It continuously monitors product listings, records price changes, and sends **email alerts** when a desired price threshold is reached.  

---

## How It Works  
1. **Scraping** – Fetches product details (name and price) from Amazon using Selenium  
2. **Monitoring** – Continuously checks if the price is below the defined threshold  
3. **Notifications** – Sends an email alert when the condition is satisfied  
4. **Automation** – Scheduled with cron on AWS EC2 to run daily without manual intervention  

---

## Summary  
The tracker provides an end-to-end solution for monitoring Amazon product prices,  
automating alerts, and maintaining availability through cloud deployment.  



