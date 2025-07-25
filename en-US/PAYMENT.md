# Overview
This page explains how we handle payments, how we calculate the pricing, and more.

# Vendors
We currently have [Midtrans](https://midtrans.com) as our primary payment vendor, and [PayPal (PayPal Holdings, Inc.)](https://paypal.com) as our alternative.

# Fees
We are committed to being fully transparent about these costs.

To ensure the platform remains operational, each transaction includes fees.

We have platform and payment fees. You can see more information about these fees down sections below.

Also, regarding the payment of fees, we offer two options: you may either pass the fees on to your consumers or choose to cover them yourself. The decision is entirely up to you.

## Platform Fees
We have a fixed percentage of fee for our services, applies to every transactions, which is:
- Local payments occurs **4%** of a platform fee.
- International/cross-border payments occurs **6%** of a platform fee.

If you are an Indonesian resident, **we strongly recommend** that you continue using local payment methods, as otherwise it may violate [Article 21 and 33 of Law Number 7 of 2011 on Currency (Pasal 21 dan 33 terkait Undang-Undang Nomor 7 tahun 2011 tentang Mata Uang)](https://peraturan.bpk.go.id/Details/39182).

Our platform fees are automatically deducted at the time of payment processing. This means the amount shown in your balance is already your net payout amount—no additional platform fees will be deducted during withdrawal. You will only need to factor in payment gateway fees for your final calculation.

Updated since June 1st, 2024.

## Payment Fees (Situational)
Payment fees depend on our payment vendors.

- For local payment vendors, please visit [Midtrans pricing page](https://midtrans.com/pricing) for more details.
- For international payment vendors (mainly [PayPal](https://paypal.com)), we use fixed percentage and a flat fee instead of relying on [PayPal Consumer Fees](https://paypal.com/webapps/mpp/paypal-fees) to prevent complications between us (as a platform) and our users.
  - The fee is **5%** + **0.50 $**.
  - Updated since April 1st, 2024.

### Google Pay
If available, [Google Pay](https://support.google.com/googleplay/answer/6224192?hl=en) relies on bank or card provider fees, so it's best to consult them if you have any concerns.

## Out of Scopes
We do not charge you fees other than mentioned above. Such as refund, withdrawal, etc.

## Conditions
We given our verified users full control over how they choose to handle these fees. And, some of users can choose to pass these fees to their customers.

# Foreign Exchange Rate
To ensure fairness, we use [Wise (formerly TransferWise)](https://wise.com) as our foreign exchange rate provider. The rates are updated every hour.

**Anthro.id** is not affiliated, endorsed, or sponsored by Wise.

# Internationalized Price (formerly Dollarized Price)
We given our users full control over how they going to price the item for users/residents outside Indonesia.

It is also depend on their own decision whether to use internationalized price (fixed price, defined by users) or converted price (let the system convert the original price from IDR to USD using the latest **Foreign Exchange Rate**).

If the user decides to use internationalized pricing, then only the fees (that are passed on to attendees/customers) will be converted.

# Rounding Decision
Any item pricing amount (including fees) will be rounded to the nearest 0.05 or 1/20th for convenience.
- For example:
  - The item is **$7.47**, our system will round the price to **$7.50**.
  - The fee is **$0.52**, our system will round the price to **$0.55**.

There is no rounding needed if the price of an item is fixed or no fraction unit. Such as, **$5.00** will always be **$5.00**.

This rounding system only applies to users who pay using our selected international payment vendors.

# Payouts
## Fees
Please note that additional fees may be deducted by payment vendors during the payout process. These fees are set by the payment providers and are beyond our control.

For example:
- When withdrawing local funds to your local digital wallet, payment providers charge the following fees:
  - Gopay: IDR 2,500.
  - Bank Transfer: IDR 5,000.
- When withdrawing international funds to your PayPal account:
  - Indonesian residents pay no additional fees.
  - International users are charged PayPal's standard fees, and currency conversion fees may apply.

You can read more information about our payment providers pricing here:
- [Midtrans: Pricing](https://midtrans.com/pricing)
- [PayPal: Send Money Online](https://www.paypal.com/us/digital-wallet/send-receive-money/send-money#accordion-content4)
- [PayPal: Consumer Fees](https://www.paypal.com/us/digital-wallet/paypal-consumer-fees)

## Options
These options are only available if your account supports multiple payment methods.

For now, we only offer separated payout.

**Separated payout** is a method where you withdraw funds to different accounts based on payment source.
- For example, your local currency funds will be withdrawn to your local digital wallet,
  and your international currency funds will be withdrawn to your international digital wallet (PayPal).

## End-to-End Timing
### Event Organizers
You can submit your payout 7 days after the event ended. This waiting period allows attendees time to submit complaints if they have any.

Your payout will be paused if there are one or more complaints.

## Payment Vendors Timing
Both payment gateways take longer—usually to 3 up to 5 business days, though this may vary due to weekends, national holidays, or bank processing schedules.

You can read more information about their timing here:
- [Midtrans Fund Withdrawal](https://midtrans.com/contact-us/fund-withdrawal-1/cara-melakukan-pencairan-dana)
- [Midtrans: Manual Payout (Developer-side)](https://docs.midtrans.com/docs/how-can-i-have-my-money-in-my-account-payout#manual-payout)
- [PayPal: Where's my withdrawal?](https://www.paypal.com/us/cshelp/article/where%E2%80%99s-my-withdrawal-help456)

# Fraud Prevention
## Billing Address
If you are using cards or PayPal as a payment method, it is mandatory to fill the billing address. This step is quite common to reduce fraud.

We collect this information to forward it to and be processed by our payment vendors. As stated in our [privacy policy](/legal/consumer/privacy), we do not collect any data beyond what is mentioned above, unless you have given us permission to do so.

You can read more information about the [Importance of Billing Address](https://www.deskera.com/blog/billing-address/#why-is-it-important-to-update-the-billing-address) here.

We do not endorse the products or services listed above.

## reCAPTCHA Enterprise
Any page that contains payment features are automatically protected by [Google reCAPTCHA Enterprise](https://cloud.google.com/recaptcha/) to prevent fraud.

## Request Check
During purchase, we also collect your IP address to check if the request is legitimate.