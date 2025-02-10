## 🍓  Customize Your Smoothie 🍍

This Streamlit app allows users to create and customize their own smoothies by selecting up to five ingredients from a predefined list. Once the selection is made, the order is stored in a Snowflake database.

🚀 **Features**:

Interactive UI: Users can enter their smoothie name and select up to five ingredients.
Snowflake Integration: Retrieves available fruit options from smoothies.public.fruit_options and stores orders in smoothies.public.orders.
Live Order Processing: Orders are submitted and saved in real-time using Snowflake SQL queries.

🛠️ **Setup Instructions**:

Prerequisites

1. Python 3.7

2. Streamlit

3. Snowflake Snowpark or Python

🏗️ **How It Works**:

The app retrieves available fruits from Snowflake (smoothies.public.fruit_options).
Users enter their smoothie name and select ingredients.
The selection is stored in smoothies.public.orders.
A confirmation message appears when the order is successfully placed.

📝 **Notes**:

Ensure that you have an active Snowflake session before running the app.
Modify the Snowflake table names if your schema is different.

🤝 **Contributing**:

Pull requests are welcome! Feel free to open an issue for feature requests or bugs.

📜 **License**:

This project is licensed under the MIT License.
