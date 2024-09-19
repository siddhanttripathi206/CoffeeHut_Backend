# Commerce Transactions

This file tracks all the key commerce transactions and processes involved in CoffeeHut. Below are the types of transactions managed:

## 1. Order Placement
- Process: Customers place an order, and it's processed based on payment completion.
- Payment Status: Pending/Completed/Failed
- Actions: Confirmation email sent upon successful payment, and order details are stored in the database.

## 2. Refund Processing
- Process: Customers can request refunds for incorrect or damaged products.
- Payment Status: Refund Initiated/Processed/Failed
- Actions: Upon successful validation of the request, the refund is processed within 3-5 business days.

## 3. Subscription Management
- Process: Customers who subscribe (monthly or quarterly) can manage their subscription plan.
- Payment Status: Active/Inactive/Canceled
- Actions: Auto-renewal payments are processed unless the subscription is canceled.

## 4. Loyalty Points Redemption (NEW)
- Process: Customers can redeem loyalty points from CoffeeHut Wallet during checkout.
- Payment Status: Points Deducted/Payment Completed
- Actions: Loyalty points are deducted from the wallet, and the discount is applied at checkout.
