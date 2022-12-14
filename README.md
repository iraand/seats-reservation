# Seats Reservation Servise

### Welcome to seat-reservation

Find the best available seats for 2-8 visitors among random reserved seats.


## Description
### Main Responsibilities

* Rendom input number of currently reserved seats from 20% to 100%.
* Default amount reserved seats is 20% of the total number of seats.
* Input the number of visitors for whom seachingseats (minimum 2, maximum 8).
* Seaching the best available alternative with better location for given number of visitors.
* Found seats are next to each other, in one row and in the same price category. 
* If available seats are not found for input number of visitors there is show message.
* Seaching seats are not next to each other is not implemented.
* Outcome is section, row, and seat numbers.
* Implemented simple GUI for testing https://iraand.github.io/seats-reservation/


### Acceptance criteria

* Seats Reservation Service should find number of available seats with better location that mean higher price.
* If two seats fall in the same price category, the order of section preference prevails:
    - the most popular section is the stalls,
    - then the centre of the gallery, followed by the left and right sides of the gallery
    - lastly, the boxes.
* If seats are in the same section and in the same price category, the one(s) in the row closer to the stage is (are) 
* If two or more seats are in the same row, the one(s) in the centre is (are) preferred.
* The expected outcome is an alternative that meets the requirements specifications of section, row, and seat numbers


### Running
1. Clone the repository and enter the 

```bash
$ git clone https://github.com/iraand/seats-reservation.git && cd seats-reservation 
```


### Getting up and running

To install the service use:

```
npm i
```

To start the service use:

```
npm start
```

Service designed with JavaScript and jQuery for GUI.

* seats.js - stub with data of seats;
* reserveSeats.js - to generate rendom reservation of seats 
* createSeats.js - to build seats for GUI from data
* findSeats.js  - seaching the best available alternative




