# Microservices Final Project - Product Price Comparison

Three microservices deployed on IBM Cloud Code Engine (us-south):

| Service | Stack | Port |
|---|---|---|
| prodlist (Product Details) | Python | 5000 |
| dealerdetails (Dealer Pricing) | Node.js | 8080 |
| frontend (Dealer Evaluation) | HTML + Axios | 5001 |

Deployment URLs are in `urls.txt`. Source repositories:
- https://github.com/ibm-developer-skills-network/dealer_evaluation_backend
- https://github.com/ibm-developer-skills-network/dealer_evaluation_frontend

## Screenshots
1. `product_details_deploy.png` - Product Details deployed
2. `dealer_details_details.png` - Dealer Pricing deployed
3. `git_clone.png` - frontend cloned
4. `index_urlchanges.png` - API URLs set in `html/index.html`
5. `frontend_deploy.png` - frontend deployed
6. `homepage.png` - products in the dropdown
7. `product_dealer.png` - dealers for a product
8. `product_dealer_price.png` - price for a selected dealer
9. `product_all_dealers_prices.png` - prices from all dealers
