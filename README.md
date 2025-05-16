# Hotel Booking Demand

This dataset consists of booking data from a city hotel and a resort hotel. It includes many details about the bookings, including room specifications, the length of stay, the time between the booking and the stay, whether the booking was canceled, and how the booking was made. The data was gathered between July 2015 and August 2017.


## 📚 Data Dictionary

For binary variables: **1 = True**, **0 = False**

| Column | Description |
|--------|-------------|
| `is_canceled` | Whether the booking was canceled |
| `lead_time` | Days between booking and arrival |
| `arrival_date_week_number` | Week number of the arrival date |
| `arrival_date_day_of_month` | Day of the month for arrival |
| `arrival_date_month` | Month of the arrival |
| `stays_in_weekend_nights` | Number of weekend nights booked |
| `stays_in_week_nights` | Number of weekday nights booked |
| `adults`, `children`, `babies` | Count of adults, children, and babies in booking |
| `is_repeated_guest` | Whether the customer is a repeat guest |
| `previous_cancellations` | Number of prior cancellations by the customer |
| `previous_bookings_not_canceled` | Number of previous bookings not canceled |
| `required_car_parking_spaces` | Number of parking spaces requested |
| `total_of_special_requests` | Number of special requests made |
| `avg_daily_rate` | Average daily rate charged for stay |
| `booked_by_company` | Whether the booking was made by a company |
| `booked_by_agent` | Whether the booking was made by an agent |
| `hotel_City` | Booking for a City Hotel |
| `hotel_Resort` | Booking for a Resort Hotel |
| `meal_BB` | Bed & Breakfast meal booked |
| `meal_HB` | Half Board meal booked |
| `meal_FB` | Full Board meal booked |
| `meal_No_meal` | No meal package booked |
| `market_segment_*` | Market segment (e.g., Aviation, Corporate, Online TA, etc.) |
| `distribution_channel_*` | Booking channel (e.g., Direct, GDS, TA/TO, etc.) |
| `reserved_room_type_*` | Reserved room type (A–L) |
| `deposit_type_No_Deposit` | No deposit was made |
| `deposit_type_Non_Refund` | Deposit equal to total stay cost |
| `deposit_type_Refundable` | Refundable deposit under total stay cost |
| `customer_type_Contract` | Contract-based booking |
| `customer_type_Group` | Booking made as part of a group |
| `customer_type_Transient` | Independent booking not part of group/contract |
| `customer_type_Transient-Party` | Independent booking linked to other transient bookings |
