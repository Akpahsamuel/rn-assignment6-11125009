

Project Name: React Native Shopping Cart App

Description:

This React Native application simulates a simple shopping experience where users can browse through a list of available products, add them to their cart, remove them from the cart, and view the selected items. Local storage is implemented to persist cart data across app sessions, enhancing user experience by remembering their choices.

Design Choices:

Component Structure: The app is structured using three primary components:
HomeScreen: Displays a list of available products with an "Add to Cart" button for each item.
CartScreen: Presents the list of selected items in the cart with "Remove from Cart" buttons for each entry.
Product: Reusable component encapsulating product information and the "Add to Cart" button.
Navigation: A navigation library (e.g., React Navigation) is recommended for easy navigation between the HomeScreen and CartScreen.
Local Storage: The react-native-async-storage library is used for storing and retrieving cart data in a key-value format.
Implementation of Data Storage:

The AsyncStorage API from react-native-async-storage is employed for local storage.
An appropriate key is chosen to store the cart data (e.g., 'cart_items').
Data is serialized (converted to a string) before storing it in AsyncStorage using JSON.stringify().
When retrieving data from AsyncStorage, it's deserialized (converted back to an object) using JSON.parse().
Screenshots of the app created










