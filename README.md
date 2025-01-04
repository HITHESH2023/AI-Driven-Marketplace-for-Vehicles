# Vehicle Service Management System 🚗🔧

A **Vehicle Service Management System** designed to streamline the process of vehicle servicing and test ride bookings for luxury hyper sports cars and bikes. The project caters to busy professionals, providing a seamless experience for booking services, allocating mechanics, and managing test rides.

---

## Features 🌟
- **Customer Portal**:
  - Users can register and log in to book services for their vehicles.
  - Book test rides for luxury vehicles.
- **Admin Dashboard**:
  - Manage customer details and appointments.
  - Allocate mechanics for services.
  - Manage test ride bookings and inventory.
- **AI-Powered Recommendations**:
  - Suggests test cars to users based on their preferences.
- **Inventory Management**:
  - Tracks available cars for test rides and manages vehicle details.

---

## Tech Stack 🛠️
### Frontend:
- **React.js**: For building a responsive and interactive user interface.
- **HTML5**, **CSS3**, **JavaScript**: For additional styling and functionality.
- **TailwindCSS**: For modern and efficient styling.

### Backend:
- **Node.js**: For server-side logic.
- **Express.js**: To handle API requests and routing.
- **PostgreSQL**: As the relational database for storing user, service, and test ride data.

### AI Integration:
- AI model for recommending test vehicles based on user preferences.

---

## Installation & Setup 🚀
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/vehicle-service-management.git
   cd vehicle-service-management
   ```

2. **Install dependencies**:
   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd frontend
     npm install
     ```

3. **Setup the database**:
   - Ensure PostgreSQL is installed and running.
   - Create a database and run the provided SQL scripts in `database/schema.sql` to set up the schema.

4. **Environment variables**:
   - Create a `.env` file in the backend folder and add the following:
     ```
     PORT=5000
     DATABASE_URL=your_postgresql_connection_string
     ```

5. **Run the project**:
   - Backend:
     ```bash
     cd backend
     npm start
     ```
   - Frontend:
     ```bash
     cd frontend
     npm start
     ```

---

## Usage 💻
1. Visit the customer portal to register and log in.
2. Book vehicle services or test rides via the user-friendly interface.
3. Admins can log in to the admin dashboard to manage users, appointments, and test rides.

---

## Database Schema 📊
### Tables:
1. **Users**:
   - `id` (Primary Key)
   - `first_name`
   - `last_name`
   - `email`
   - `password`

2. **Test Rides**:
   - `id` (Primary Key)
   - `name`
   - `age`
   - `license_no`
   - `car`
   - `ride_date`

3. **Services**:
   - `id` (Primary Key)
   - `user_id` (Foreign Key)
   - `vehicle_details`
   - `problem_description`
   - `mechanic_id` (Foreign Key)

---

## Future Enhancements 🌟
- Integration with payment gateways for online payments.
- Real-time notifications for service updates.
- Advanced analytics for admin insights.
- Enhanced AI recommendations for test rides.

---

## Contributing 🤝
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

---

## License 📜
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements 🙏
- [PostgreSQL](https://www.postgresql.org/) for database management.
- [React.js](https://reactjs.org/) for building the frontend.
- [Node.js](https://nodejs.org/) and [Express.js](https://expressjs.com/) for backend development.

---

## Contact 📨
For any queries or suggestions, feel free to contact:
- **Your Name**: [your.email@example.com](mailto:your.email@example.com)
- [GitHub Profile](https://github.com/your-username)

---

Thank you for using the Vehicle Service Management System! 🚗✨

