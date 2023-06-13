# Customer Loyalty

## Overview

The purpose of this demo application is to create a simple customer loyalty program enabling the issuance and redemption of loyalty points. In a real world application, this would act as the engine to track and maintain a customer's account.

Points can only be granted through the brand (aka issuer). After receiving points, a user can redeem them for an item or reward that would exist in the real world. It's important to note that the user must provide the exact amount of points required as points are not aggregated for a user. It's assumed that the aggregation for a user would be done on the client side through the CombinePoints choice.

## Workflows

1. brand/company creates a LoyaltyAccount proposal to a user
2. user exercises Accept choice on proposal account, including their user data such as name, email, etc.
3. brand/company grants points to user account (assumed this would be triggered via a purchase, interaction, etc.)
4. user redeems points for "real world" reward
