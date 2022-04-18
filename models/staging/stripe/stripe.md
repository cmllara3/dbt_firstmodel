{% docs payment_method %}
	
One of the following values: 

| status        | definition                                    |
|---------------|-----------------------------------------------|
| credit_card   | Visa or Mastercard credit card                |
| coupon        | Discounts cupons give by the company          |
| bank_transfer | The money was deposit in company bank account |
| gift_card     | Customer gift cards                           |

{% enddocs %}

{% docs payment_status %}
	
One of the following values: 

| status  | definition               |
|---------|--------------------------|
| success | Payment was accepted     |
| fail    | Payment was not accepted |

{% enddocs %}