# poinz - Data Task


## Instructions

1. If you have questions, do not hesitate to contact david.stenz@poinz.ch
2. Submit your result to david.stenz@poinz.ch


## Data analysis

### Task

Customers of poinz can purchase deals in the poinz app and on the poinz webshop. A deal is an offer by a partner brand to a reduced price (e.g. 50% for a menu for 2 persons). To increase the deal revenue, poinz wants to segment their customers and individually target the segments with a special deal offer.

### Assumption

- The deals only differ in utility for the customer in its:
    - Price
    - Discount
- The deal offer will get a special placemenet and will therefore be perceived as special (even though the price and discount might not be)


### Requirements

- Create 3 customer segments based on historic data
- You can use the datasets `deal_purchases.csv` and `deal_events.csv` (not both need to be used)
- Suggest and justify a deal offer for each segment
    - Not all segments need to receive an offer
    - The offer can either differ in the level of the discount or the price of the deal
- Python programming language should be used
- Feel free to use any python package that helps to solve the task


### Data

**Purchase history (`deal_purchases.csv`):**
- purchase_date: Timestamp of the purchase
- deal_id: Unique identifier of a deal
- price: Original price
- discounted_price: Price the user needs to pay
- user_id: Unique identifier of a user

**Event data (`deal_events.csv`):**
- date_time: Timestamp of the event
- event_name:
    - deal_impression: The user has seen the deal in a list of deals
    - view_item: The user has clicked on a specific deal to see more details
- deal_id: Unique identifier of a deal
- price: Original price
- discounted_price: Price the user needs to pay
- deal_type: Not important
- user_id: Unique identifier of a user



### Evaluation

- The complexity of the used method doesn't matter (no need to use advanced methods including ML)
- Code structure
- Analytical reasoning

