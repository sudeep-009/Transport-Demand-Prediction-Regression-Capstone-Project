# Transport-Demand-Prediction-Regression-Capstone-Project
### Introduction: 
Modern societies experience a growing demand for passenger and freight movement. Accurate forecasting of the total passenger and freight demand and the competitive (or
substitutive) and complementary relationships among transport modes are necessary inputs in planning, designing, evaluating and regulating transport and supply chain systems. Transport investment, especially investment in highway, rail, airport and sea port infrastructure requires long-term financial commitments and the sunk costs can be very high if the investment projects fail to fulfill their design capacities. Therefore, accurate prediction of the long-term demand for using transport or some other public capital infrastructure often forms an important part of the overall project appraisal.

### Problem Statement: 
This challenge asks you to build a model that predicts the number of seats that Mobiticket can expect to sell for each ride, i.e. for a specific route on a specific date and time. There are 14 routes in this dataset. All of the routes end in Nairobi and originate in towns to the North-West of Nairobi towards Lake Victoria.

### Dataset Used:
Nairobi Transport Data.csv (zipped) is the dataset of tickets purchased from Mobiticket for the 14 routes from “up country” into Nairobi between 17 October 2017 and 20 April 2018. This dataset includes the variables: ride_id, seat_number, payment_method, payment_receipt, travel_date, travel_time, travel_from, travel_to, car_type, max_capacity.

### Variable Information:
#### ride_id:   unique ID of a vehicle on a specific route on a specific day and time.
#### seat_number: seat assigned to ticket.
#### payment_method: method used by customer to purchase ticket from Mobiticket (cash or Mpesa).
#### payment_receipt: unique id number for ticket purchased from Mobiticket.
#### travel_date: date of ride departure. (MM/DD/YYYY)
#### travel_time: scheduled departure time of ride. Rides generally depart on time. (hh:mm)
#### travel_from: town from which ride originated.
#### travel_to: destination of ride. All rides are to Nairobi.
#### car_type: vehicle type (shuttle or bus)
#### max_capacity: number of seats on the vehicle.

### Data Understanding:
1. Number of features present in the dataset is 10.
2. Number of records present in the dataset is 51645.
3. No null values were detected in the dataset.
4. Two type of payment method.
5. Only 149 days record is available.
6. There are 17 distinct origin.
7. There are 2 type of vehicle.
8. Only one destination Nairobi.
9. Bus is more in number.

