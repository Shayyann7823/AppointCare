# AppointCare 🏥

A console-based Hospital Appointment Management System built in C++. AppointCare lets patients register, log in, browse available doctors, check open time slots, and book appointments — complete with a simple payment flow and billing.

## Features

- **User Authentication** — Register and log in with email/password
- **Doctor Directory** — View available doctors along with their specialization and consultation fee
- **Slot Management** — Doctors have hourly appointment slots (8 AM – 9 PM); booked slots are automatically marked unavailable
- **Appointment Booking** — Book a slot with any available doctor
- **Payment Processing** — Choose between Bank Transfer or EasyPaisa at checkout
- **Billing** — Generates a bill with patient name, doctor, appointment time, fee, and payment method
- **Persistent Records** — Appointment/user data is written to `Project.txt`

## Tech Stack

- **Language:** C++
- **Libraries:** `iostream`, `fstream`, `vector`, `string`, `iomanip`, `regex`, `cstdlib`, `ctime`

## Project Structure

```
AppointCare/
└── HospitalManagement.cpp   # Main application source
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/AppointCare.git
   cd AppointCare
   ```
2. Compile the program:
   ```bash
   g++ HospitalManagement.cpp -o AppointCare
   ```
3. Run it:
   ```bash
   ./AppointCare
   ```

## Main Menu

```
1. Register
2. Login
3. Quit
```

Once logged in:

```
1. Display Available Doctors
2. Book Appointment
3. View Doctors Availability Slots
```

## Payment Options

```
1. Bank Transfer
2. EasyPaisa
```

## License

This project is open source and available under the [MIT License](LICENSE).
