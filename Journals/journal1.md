# [ux-portfolio-Tiggzzz](../README.md)
# Using Remaining Balance
When it gets closer to the end of the month, my [SNAP/EBT](https://www.fns.usda.gov/snap/ebt) funds begin to run low or even reach zero. As a college student it's my priority save as much money as I can, so often I want to use all my SNAP funds. A common technological interaction I run into is when I try to make a purchase with a greater total than my remaining SNAP funds. In this situation I would like to use all of my remaining SNAP funds and subsequently cover the remaining transaction total with some other payment method. However instead the transaction is overall declined.

The transaction shown bellow is an exmaple of an unaproved transaction with a sale amount of $6.87 and a SNAP balance of $4.34.
![alt text](../assets/SNAP_Declined.jpg)

The interaction shown above consisted of me inserting my EBT card into a card terminal, inputing my pin, seeing declined on the screen, and reciveing the receipt shown above. After my transaction was declined, I removed my EBT card and asked the clerk if she could use my remaining balance. She then created a sale matching my remaining SNAP balance and asked me to reinsert my EBT card and input my pin. After this sale was approved, she created another transaction with the differnece that wasn't covered, and that's where I paid with my debit card. This overall experience consisted of 3 seperate transactions.

![alt text](../assets/EBT_Card.png)
![alt text](../assets/Card_Terminal.jpg)

I beleve that this interaction could be improved if instead of outright displaying declined it coudld dynamically display one of two posible messages. The first being "Declined" if there trully are no fundsand the second being "Insufficient Funds" if available but funds are present 
