# Description
This is a very simple application, where users can order one or more pizzas from a menu. It was built as a practice project for the following technologies:
- React
- Redux, Redux-Thunk and Redux-Toolkit
- React-Router
- Tailwind CSS

## Requirements
- The app requires **no user accounts** and no login: users just input their name before using the app.
- The pizza menu can change, so it should be **loaded from an API** (already provided).
- Users can add multiple pizzas to a **cart** before ordering.
- Ordering requires just the **user's name, phone number and address**.
- **GPS location** should also be provided, to make it easier to deliver the pizza.
- Users's should be able to **mark their order as _priority_** for an additional 20% fee.
- Orders are made by **sending a POST request** with the order data (user data + selected pizzas) to the API.
- Payments are made on delivery, so **no payment processing** is required.
- Each order will get a **unique ID** that should be displayed, so the **user can later look up their order** based on the ID.
- Users should be able to mark their order as _priority_, **even after it has been placed**.

## How to run
This project is not hosted anywhere, but you can run it locally. You will need to have Node.js installed.

1. Clone the repository
2. Run the following commands in the project's root directory:
    > npm install && npm run dev
3. Open http://localhost:5173 in your browser

## Takeaways
- Altough **Redux** may look like sorcery at first, it's actually quite simple to use. The **Redux-Toolkit** makes it even easier.
- **React-Router** can be used also for state management with _loaders_ and _actions_. Feels a bit hacky tbh, but it works.
- I should really have learned **Tailwind CSS** before. It allows for rapid development and easy customization, and it's a joy to use (I now hate Bootstrap even more).
