# Study Notion

Study Notion is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application designed to facilitate the process of buying and adding courses for students and teachers respectively. It includes features such as user authentication, a dashboard, a shopping cart, and payment integration using Razorpay. The application is built using modern web development technologies including React, Redux, JavaScript, Node.js, Tailwind CSS, and various React packages like bcrypt, chart, and icons.

## Live Demo

A live hosted version of the application can be accessed at: [https://edtech-mern-app.vercel.app/](https://edtech-mern-app.vercel.app/)

## Key Features

- **Authentication and Authorization**: Users can create accounts, login, and access their personalized dashboard based on their role as a student or teacher.
- **Student Features**: Students can browse and purchase courses, manage their cart, and view their purchased courses.
- **Teacher Features**: Teachers can create and add new courses to the platform, manage their courses, and view student enrollment details.
- **Dashboard**: Users have access to a personalized dashboard with relevant information and actions based on their role.
- **Shopping Cart**: Students can add courses to their cart, update quantities, and proceed to checkout.
- **Payment Integration**: Integration with Razorpay allows secure payment processing for course purchases.
- **Database**: MongoDB is used as the database to store user information, course details, and transaction data.
- **Responsive Design**: The application is designed to be fully responsive, providing a seamless experience across devices.

## Tech Stack

The application uses the following technologies and tools:

- Frontend: React, Redux, JavaScript, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Payment Integration: Razorpay
- Other Libraries and Packages: Bcrypt, Chart, Icons

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. Clone the repository:

```shell
git clone https://github.com/dhruv-os-23/your-repository.git
```

2. Install dependencies:

```shell
cd your-repository
npm install
```

3. Set up environment variables:

Create a `.env` file in the root directory and add the following variables:

```plaintext
MONGO_URI=your_mongodb_connection_string
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

4. Start the development server:

```shell
npm start
```

5. Open your web browser and visit `http://localhost:3000` to access the application.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make the necessary changes and commit your code.
4. Push your changes to your forked repository.
5. Submit a pull request to the original repository.

## License

The project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or inquiries, please email us at [dhruv.lotia@gmail.com](mailto:dhruv.lotia@gmail.com).

---

Thank you for your interest in Study Notion! We hope you find the application useful. If you have any feedback or suggestions, please let us know.
