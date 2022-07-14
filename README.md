# Eletronic House AB Testing

# 1. Context

Electronic House is an e-commerce company that sells computer products for homes and offices. Customers can buy mice, monitors, keyboards computers, laptops, HDMI cables, headsets, webcam cameras, among others, through an online site and receive the products in the comfort of their homes.

The UX design team has been working on a new sales page, with the the goal of increasing the conversion rate of a product from the store, a keyboard
bluetooth. The product manager said that the conversion rate of the current page is 13% on average in the last year.

The product manager's goal is to increase the conversion rate by 2%, i.e. the new sales page, developed by the UX team, would be a success if its conversion rate was 15%.
The bluetooth keyboard has a sale price of R$4,500.00 cash or in 12% installments without interest on the credit card.

Before replacing the old sales page with the new one, the product manager would like to test the effectiveness of the new page on a smaller group of customers, in order to take less risk of a drop in conversion, should the new page show a worse conversion than the current page.

# 2. Business Problem

You have been hired as a freelancer by Electronic House to help the Designers team of the new website, to validate its effectiveness in a safer way, with more confidence and rigidity in the analysis.

The deliverables of your work are as follows:

* Is the conversion of the new page really better than the conversion of the page?

* What is the potential number of sales that the new page can bring?

* What is the total revenue in selling the bluetooth keyboard through the new page?

# 3. Data Available

Data is available in: https://www.kaggle.com/datasets/zhangluyuan/ab-testing

Each row in the database represents a client and the columns have the information if the client is in a control or treatment group and if he/she converted (bought the keyboard).

The data brings the following informations:

* user_id: unique identifier for customer
* timestamp: datetime when the user accessed the page
* group: control or treatment group
* landing_page: tells if the customer landed in the old or the new designed page
* converted: 0 if did not buy the keyboard, 1 if did