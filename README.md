# Manufacturer-analysis

This project aimed to analyze different features extracting from manufacturer profile. The goal of this project is to find the most influential features from manufacturer profile using machine learning models linear regression.

Y value includes 6 indicators: nr_viewer_buyer, nr_buyers_sent_message, nr_messages_received_from_buyers, nr_brand_watchlist, nr_brand_supplierlist, pv_countwatch follow and supplier follow.

nr_brand_watchlist: the number of followed manufacturer on brand watchlist
nr_brand_supplierlist: the number of followed manufacturer on supplierlist
nr_messages_received_from_buyers: the number of manufacturer received message coming from buyer
nr_buyers_sent_message: the number of buyer who sent the message to manufacturer
pv_countwatch: manufacturer pageview number
nr_viewer_buyer: number of distinct buyer who viewed manufacturer


- Analyzed over 65,000 data from Foursource website, created and cleaned multiple datasets from database by MySQL
- Implemented PCA and recursive feature elimination to decrease feature dimension
- Tested and validated R square score via linear regression
