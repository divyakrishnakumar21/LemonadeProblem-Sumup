# LemonadeProblem-Sumup

At a lemonade stand, each lemonade costs $5. Customers are standing in front of the stand in
an unorganized way and start to order.
In this stand, each customer can:
- buy one or more lemonades
- pay with a $5, $10, or $20 bill
You must process the customer requests by order of arrival and return the correct change to
each customer.
Note that you do not have any change in hand at first.
You are given an array of orders where each order contains the following information:
- bill
  _
  value: an integer, representing the value of the bill
- requested
  lemonades: an integer, representing the number of lemonades requested by
  the customer
- position
  in
  line: an integer, representing the position of the customer in the line
  If you can provide every customer with the correct change return an array with the received bills
  Otherwise, return null

Example 1
Input
[
{ "bill_value": 20, "position_in_line": 3, "requested_lemonades": 2 },
{ "bill_value": 5, "position_in_line": 1, "requested_lemonades": 1 },
{ "bill_value": 5, "position_in_line": 2, "requested_lemonades": 1 }
]
Output: [20]

Example 2
Input
[
{ "bill_value": 5, "position_in_line": 1, "requested_lemonades": 1 },
{ "bill_value": 5, "position_in_line": 2, "requested_lemonades": 1 }
]
Output: [5, 5]

Example 3
Input
[
{ "bill_value": 10, "position_in_line": 2, "requested_lemonades": 1 },
{ "bill_value": 10, "position_in_line": 3, "requested_lemonades": 1 },
{ "bill_value": 5, "position_in_line": 1, "requested_lemonades": 1 }
]
Output: null

The Solution class is an takes the bill value and position and the requested lemonades as input parameters
the output will be an array which returns the possible current change
