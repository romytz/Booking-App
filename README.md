# Booking App in Go 🚌

A simple, interactive command-line booking application built in Go.  
Developed as part of a self-study project.

---

## Project Overview 📊

This project demonstrates fundamental concepts of the Go programming language in a practical context. The goal was to simulate a booking system where users can reserve tickets for an event and see real-time booking updates — while applying Go’s concurrency features.

### Key Objectives:
- Collect user input (name, email, number of tickets)
- Validate input for correctness
- Track and confirm bookings
- Demonstrate Go’s concurrency model using Goroutines

---

## Project Structure 📁
```bash
booking-app/
├── main.go        # Core application logic
└── helper.go      # Helper functions (e.g., input validation)
```

---

## Installation & Setup 🛠️

### Prerequisites
- Go installed on your system  
  👉 [Download Go](https://go.dev/doc/install)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/booking-app.git
   cd booking-app
   ```

2. **Run the App**:
   ```bash
   go run main.go
   ```

## Example Output 🖥️
```bash
Welcome to the Booking App!
We have 50 tickets available.

Enter your first name: John
Enter your last name: Doe
Enter your email address: John@example.com
How many tickets would you like to book? 2

Thank you John! You have successfully booked 2 tickets.
```

## Features ⚙️

- 📥 **Input Handling**: Interactive prompts to gather user information  
- ✅ **Validation**: Ensures email format and ticket limits are respected  
- 🔄 **Concurrency**: Uses Goroutines to simulate asynchronous confirmation emails  
- 🔢 **Slices**: Stores booking data efficiently  
- 🧠 **Logic**: Loops, conditionals, and string manipulation in action

## Contributors 👥

- **Romy Tzafrir** - [GitHub Profile](https://github.com/romytz)

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
