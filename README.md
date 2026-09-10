# Movie Theater Ticket Kiosk
This repository is a practice run through common software tools,buikt around a small system i.e a self check out Kiosk for movie tickets. Users can browse showtimes, seats and checkout. once they check out and pay the kiosk confirms it and no seat is assigned to two people at once.
# Purchase Ticket Containing : Primary Actor
Precondition: The customer has selected a movie, showtime,and an available seat.
Main Steps:
Customer taps to confirm the seat they picked.
Kiosk shows the price for that seat.
Customer decides to go ahead and pay.
Kiosk passes the seat and showtime info along to the Ticket Service.
Ticket Service double-checks that the seat hasn't been grabbed by someone else in the meantime.
Kiosk forwards the payment info to the Payment Service.
Payment Service runs the charge and sends back a confirmation.
Ticket Service locks in the seat as sold and generates the ticket.

