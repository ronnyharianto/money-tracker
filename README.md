# MoneyTracker

![Development Status](https://img.shields.io/badge/status-in%20development-orange)

**MoneyTracker** is a personal finance application to track income, expenses, and transfers between your accounts. It provides a clear view of your financial activities, with the ability to generate detailed reports.

## Features

- Record income, expenses, and transfers
- Specify accounts (bank, cash, etc.) and categories (income/expenses)
- Add notes and amounts to transactions
- Monthly reports and more for insights into your finances

## Technology Stack

- [Next.js](https://nextjs.org/) - React framework for server-side rendering and static site generation
- PostgreSQL or any preferred database

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine
- [PostgreSQL](https://www.postgresql.org/) (or any database) for data storage

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/ronnyharianto/moneytracker.git
   ```

2. Navigate to the project directory:
   ```
   cd moneytracker
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Duplicate the **.env.example** file and rename it to **.env**:
   ```
   cp .env.example .env
   ```
5. Edit the **.env** file with your own configurations:
   ```
   DATABASE_URL=your_database_url
   NEXT_PUBLIC_API_URL=your_api_url
   ```

### Running the App

1. Start the development server::

   ```
   npm run dev
   ```

2. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
