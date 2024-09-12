# Simple Ticketing System Frontend

This repository contains the frontend application for the **Simple Ticketing System**, built using **React**. It interacts with the backend API to manage and display ticketing data.

## Features

- **Ticket Dashboard**: View all tickets with status and priority.
- **Create Tickets**: Users can submit new tickets via a form.
- **Update Tickets**: Modify ticket details (status, priority, etc.).
- **User Management**: Manage user accounts and ticket assignments.

## Technologies Used

- **React**: Frontend library for building user interfaces.
- **Axios**: For making API requests to the backend.
- **Tailwind CSS**: For responsive and modern UI design.
- **React Router**: For navigation and routing.

## Prerequisites

Before running the project, make sure you have the following installed:

- **Node.js** (v14 or later)
- **npm** or **yarn** for package management

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/UcheTheo/SimpleTicketAPIReact.git
   cd SimpleTicketAPIReact
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file with the following:
   ```
   REACT_APP_API_URL=http://localhost:5000/api
   ```

4. **Run the application**:
   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.

## API Integration

The frontend interacts with the **SimpleTicketAPI** backend. Ensure the backend is running before using the frontend. Modify the API URL in the `.env` file if necessary.

### Example Endpoints Used

- **GET** `/api/tickets`: Fetch all tickets.
- **POST** `/api/tickets`: Create a new ticket.
- **PUT** `/api/tickets/{id}`: Update a ticket.
- **DELETE** `/api/tickets/{id}`: Delete a ticket.

## Project Structure

```bash
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Application pages (Home, TicketList, etc.)
│   ├── services/         # API service (Axios calls)
│   ├── App.js            # Main App component
│   ├── index.js          # Entry point
├── public/               # Static files
├── package.json          # Project dependencies
└── README.md             # Project documentation
```

## Contribution

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

## License