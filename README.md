# Tikiti-Tamasha-Backend-Readme

Ticketi Tamasha  event ticketing system is an online platform that allows users to browse, purchase and manage tickets for various events such as concerts, conferences, sports games, festivals, and more. The system provides a centralized place for event organizers to sell tickets and for customers to purchase them, eliminating the need for physical ticket sales and paper tickets;

*User registration and account management: Users can create an account, edit their profile, and manage their ticket orders.

*Event listing and management: Event organizers can list and manage their events, including details such as date, time, venue, pricing, seating options, and availability of tickets.

*Ticket purchasing: Customers can browse and purchase tickets for events, choose their seats, and make payments through the platform. The system should support multiple payment options such as credit card, debit card, PayPal, and other popular payment gateways.

*Ticket delivery: After a successful purchase, customers receive electronic tickets via email or mobile app that they can use to gain entry to the event

## Setup

*Clone the repository 
```
$ git clone git@https://github.com/derrickmomanyi/Ticketi-Tamasha.git
```

*Install the necessary gems
```
bundle install
```
*Create the PostgreSQL database:
```
rails db:create 
```
*Migrate the database
```
rails db:migrate seed
```
On Development

## Usage

To run the Rails application,Start the server:
```
rails s
```

Then, navigate to http://localhost:4000 in your web browser to view the application.

## Configuration


This application is hosted on render cloud to view (https://tamasha.onrender.com)
The application also uses Amazon Web Service(AWS) for active storage of images

## Deployment

To deploy the application to a production server, view render logs 

## Contributing

If you would like to contribute to the project, please open a pull request with your changes
