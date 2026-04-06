# 🌍 Global Logistics Route Planner

## 📖 Description
The **Global Logistics Route Planner** (also known as the Global Order Routing Engine) is a lightweight, frontend web application designed to determine the optimal shipping transport method and logistical path for packages. By evaluating the origin country, destination country, and order weight, the engine automatically calculates whether domestic courier, cross-border express, air freight, or ocean freight (LCL/FCL) is the most appropriate transport type.

## ✨ Features
* **🌍 Live Country Data Integration:** Fetches and populates a complete list of global countries and their corresponding regions in real-time using the REST Countries API.
* **⚖️ Weight Standardization:** Supports order weight inputs in both kilograms (kg) and pounds (lbs), automatically standardizing values for calculation.
* **🛤️ Dynamic Route Calculation:** Provides step-by-step logistical paths based on three core conditions:
  * Domestic Shipping (same country).
  * Trans-Continental / Regional (same region, e.g., within Europe).
  * Intercontinental (different regions).
* **🚢 Tiered Transport Types:** Intelligently categorizes transport methods by weight tiers (e.g., Small Parcel Air, Standard Air Freight, Ocean Freight LCL, and Ocean Freight FCL).
* **⚡ Dependency-Free:** Built entirely with Vanilla JavaScript, HTML, and CSS. No build tools or package managers required.

## 🛠️ Technologies Used
* **HTML5 / CSS3:** For the user interface and responsive card layout.
* **Vanilla JavaScript (ES6+):** For core routing logic and DOM manipulation.
* **Fetch API:** To retrieve external country data.

## 🚀 Installation
Because this project relies entirely on client-side technologies, no complex installation or build processes are necessary.

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/preferred-transit-method.git
   ```

2.  Navigate to the project directory:
    ```bash
    cd preferred-transit-method
    ```
3.  Open the `index.html` file directly in any modern web browser.

## 💻 Usage

1.  Wait for the application to load the global country database (indicated by the loading text disappearing).
2.  Select the **Country of Origin** from the first dropdown menu.
3.  Select the **Destination Country** from the second dropdown menu.
4.  Enter the **Order Weight** and select your preferred unit (`kg` or `lbs`).
5.  Click the **Determine Transport Route** button.
6.  View the recommended transport type, standardized weight, and step-by-step logistics path rendered below the form.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome\! Feel free to check the issues page if you want to contribute.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.
Copyright (c) 2026 Matthew Timothy Erwin Penner.
