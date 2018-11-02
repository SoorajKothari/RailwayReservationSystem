# Railway Reservation System
An implementation of Railway Reservation System of both user and administrator view based on concepts of oops

## Motivation:
Pakistan Railway Management System

## How to Compile:

#### Pre-requisites
- An OS supporting c++ language
- Any c++ compiler


#### Terminal Command
```terminal
g++ project project.cpp
```

## Testing:
The program needs two files named Morning.txt and Night.txt in the same directory as itself. These file holds data of total seats and seats left in morning train and night train repectively.

#### Pessenger Can:
- Sign in
- Create account
- watch timings
- Book tickets
- Pay for tickets
- Select Desired seat
- Cancel ticket
- Signoff

#### Administrator Can:
- View record
- Refill seats
- Book seat
- Cancel seat
- View accounts

#### Possible Output:
- Seat Successfully booked
- Seat already booked
- Wait untill your desired seat gets empty
- Your ticket has been cancelled

#### Program Description:
- User ones login can watch for his desire train
- if user wants to then can book ticket
- user can select seat
- select seat will be checked in night.txt or morning.txt (Depending on users booking) and on desired seat in morning.txt and night.txt there is 0/1
- 0 means already booked
- 1 means user can book this seat
- finally user will have to pay his ticket price through various methods
- user can print ticket
- logout