# Eletronic House AB Testing

# 1. Context

Electronic House is an e-commerce company that sells computer products for homes and offices. Customers can buy mouse, monitors, keyboards, laptops, HDMI cables, headsets, webcam cameras, among others, through an online site and receive the products in the comfort of their homes.

The products are not only sold in Brazil, Eletronic House is present in several countries in Europe and North America.

The Director of Global Products asked the Head of Design to develop a new way to finalize the purchase with a credit card, without the need for the manually fill in all credit  card information and that would work in all countries.

After months of developing this device, the Backend Development team delivered a payment solution, in which 90% of the information on the information was filled in automatically.

The Head of Designer would like to measure the effectiveness of the new the credit card data on the sales page and report the results to the Global Product Director, to conclude whether the new payment method is really better than the old one.

The two pages were put online for a few months and the FrontEnd team developed an automation that assigns a label to each customer showing which sales page that particular customer was viewing.

All this data is stored in a database and can be accessed by the Electronic House team.

# 2. Business Problem

After a few months of experimentation, the Electronic House design team needs to evaluate the results of their experiment in order to conclude which was the most effective payment method.

However, the team lacks the necessary skills to evaluate the data and conclude the experiment. In this context, you have been hired as a Data Scientist to help the Designers team validate the effectiveness of the new means of with more confidence and rigidity in the analysis.

The deliverable of your paper is as follows:

1. What is the best form of payment: Manual or Automatic filling out of the credit card data form?

# 3. Data Available

Each row in the database represents a purchase of a customer and the columns have the information of the purchases in the store.

The data brings the following informations:

* uid: unique identifier for customer
* country: country of the customer
* gender: gender of the customer
* spent: total value spent on the store by the customer on that purchase
* purchases: total items purchased by the customer on the same purchase
* date: purchase date
* group: GRP A = Automatic filling; GRP B = Manual filling
* device: I = purchased on site; A = purchased on app

# 4. Business Assumptions

Probabilities of right conclusions were set at 95%, if the conclusion is that the new screen did not bring any effective changes, and a probability of 80%, if the conclusion is that the new screen did bring effective changes. 

This makes it necessary to have at least 3395 samples from each of the groups for the experiment to take place.

The values of in-store spending were compared between the groups, evaluating a possible improvement in this value for the treatment group.

* Null Hyphotesis: Group conversions are equal
* Alternative Hyphotesis: Group conversions are different

# 5. Conclusions

Using a T-Test for comparison of average spend between groups, a p-value of 0.849 was obtained, meaning that we failed to reject the null hypothesis (we assume the null hypothesis is true), i.e. the auto-fill feature did not bring about a significant difference in the company's average GMV. Therefore, the new page should be rethought, or the old page should be kept.