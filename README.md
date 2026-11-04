# Personal Finance App
# The Castaways Team

A personal finance tracker built in C# that helps users manage their money in one place. Users can create an account, log in, and (as features are added) track income, expenses, and budgets.

## Our Team
| Name             | Role(s)                                  |
|------------------|------------------------------------------|
| River Anderson   | Developer / Product Owner / Scrum Master |
| Bulmaro Enriquez | Developer                                |
| Diego Macias     | Developer                                |
| Ian Puerma       | Developer                                |
| Jameson Thomas   | Developer                                |

## Features
- User registration (sign up) and login
- Persistent user storage in a local JSON file
- Transfer money between accounts
- Set goals for finance tracking

## Tech Stack
- **Language:** C#
- **Framework:** .NET *10*
- **Data storage:** JSON file via `System.Text.Json`
- **IDE:** Visual Studio 2026
  
## Getting Started

### Prerequisites
- .NET SDK *10*
- Visual Studio 2026

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/BEnriquez-code/TheCastaways_Personal_Finance_app.git
   ```
2. Build the project:
   ```bash
   dotnet build
   ```
3. Run the app:
   ```bash
   dotnet run
   ```

## Project Structure
Finance_Tracker/
├── Account.cs # Account object
├── Authentication.cs # Sign up and login logic
├── CIO.cs # Helper methods
├── Manager.cs # Manages account data
├── Transaction.cs # Handles transactions (withdraw/deposit)
├── User.cs # User object
├── UserData.cs # Handles user data in JSON
├── users.json # User data store (created at runtime)
└── Program.cs # Application entry point

## License
*(Class Project No License)*
