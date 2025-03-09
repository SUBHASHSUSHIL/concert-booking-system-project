# Concert Booking System
![GitHub Repo Stars](https://img.shields.io/github/stars/SUBHASHSUSHIL/concert-booking-system-project?style=social)
![GitHub Forks](https://img.shields.io/github/forks/SUBHASHSUSHIL/concert-booking-system-project?style=social)

## Description
The **Concert Booking System** is a web-based application developed using **ASP.NET Core MVC**, **RESTful API**, and **MS SQL Server**. This system allows users to explore available concerts, book tickets, manage reservations, and view booking history.

## Features
- ✅ **User Authentication & Role Management**
- ✅ **Concert Listings & Details**
- ✅ **Real-time Seat Availability Tracking**
- ✅ **Online Ticket Booking & Confirmation**
- ✅ **Payment Integration (Stripe/Razorpay/etc.)**
- ✅ **Booking History & E-Ticket Generation**
- ✅ **Admin Dashboard for Event Management**

## Technology Stack
- **Backend**: ASP.NET Core MVC, Web API
- **Database**: MS SQL Server
- **Frontend**: Razor Views, Bootstrap
- **Authentication**: JWT & Identity Framework
- **Payments**: (Optional - Stripe, Razorpay, PayPal)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/SUBHASHSUSHIL/concert-booking-system-project.git
   ```
2. Configure your database in `appsettings.json`.
3. Apply migrations and seed data:
   ```sh
   dotnet ef database update
   ```
4. Run the project:
   ```sh
   dotnet run
   ```

## API Endpoints
| Method | Endpoint | Description |
|--------|-----------------|--------------------------------|
| GET | /api/concerts | Fetch all concerts |
| GET | /api/concerts/{id} | Get concert details by ID |
| POST | /api/bookings | Book a concert ticket |
| GET | /api/bookings/{userId} | Get user’s booking history |

## Contribution
Want to contribute? Follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-new-functionality`)
3. Add your code and commit (`git commit -m 'Added new booking feature'`)
4. Push to your branch (`git push origin feature-new-functionality`)
5. Create a Pull Request

## License
This repository is licensed under the **MIT License**.

## Contact
For any queries, reach out to: [Sushil Thakur](mailto:sushilthakur9792@gmail.com)
