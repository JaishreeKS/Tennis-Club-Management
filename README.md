Tennis-Club-Management
A simple Tennis Club Management program written in C that calculates the total amount that needs to be paid by the customers based on their membership status and the number of hours they have booked the court. It calculates the final due amount by providing various discounts to different tier members.

#Membership Levels and their discount percentages

GOLD - 30% Discount
SILVER - 20% Discount
PLATINUM - 5% Discount
#Hourly Cost
1000 per hour

#Discount Calculation formula

discount_amount=30*(1000*hours_spent)/100;  //similarly --> 5, 20 for silver and platinum
discount_price=((1000*hours_spent)-discount_amount);
