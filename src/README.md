SwadSeva is a responsive food delivery platform built using **React** and **TypeScript**. It features restaurant data based on geolocation, user-friendly search and sorting, real-time cart updates, and much more! 

This project integrates **Swiggy's live API** to fetch restaurant data and provides a smooth, optimized experience for users.


## 📂 Features

- **Geolocation-Based Restaurant Data**: Uses Swiggy's live API to display nearby restaurants.
- **CORS Handling**: Overcame previous CORS issues with an efficient CORS proxy.
- **Shimmer UI**: Improves user experience by displaying a loading animation while fetching restaurant data.
- **Dynamic Search**: Search restaurants by name.
- **Sorting Functionality**: Sort restaurants by ratings or distance.
- **Add to Cart**: Automatically calculates total amount and items in the cart.
- **Cart Animation**: The floating cart bounces when an item is added.
- **Order History**: Displays order history (frontend only for now).
- **Performance Optimization**: Improved performance using the `useCallback` hook.
- **Pure Veg Label**: Higher-Order Components (HOCs) used to label pure-veg restaurants.
- **Responsive Design**: Fully responsive and works smoothly across all devices.