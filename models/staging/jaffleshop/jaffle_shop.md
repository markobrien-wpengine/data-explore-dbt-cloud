{% docs order_status %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| placed         | Order placed, not yet shipped                    |
| shipped        | Order has been shipped, not yet been delivered   |
| completed      | Order has been received by customers             |
| return pending | Customer indicated they want to return this item |
| returned       | Item has been returned                           |

{% enddocs %}

{% docs payment_status %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| success        | Payment has been successfully processed          |
| failed         | Payment was not processed successfully           |

{% enddocs %}

{% docs payment_methods %}
	
One of the following values: 

| status         | definition                                         |
|----------------|----------------------------------------------------|
| credit_card    | Customer paid using credit card                    |
| bank_transfer  | Customer paid using direct bank transfer           |
| coupon         | Coupon was used to complete payment                |
| gift_card      | Customer redeemed a gift card to complete purchase |

{% enddocs %}