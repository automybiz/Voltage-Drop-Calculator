# ⚡ Voltage Drop Calculator

A clean, modern, and high-performance Voltage Drop Calculator for electrical setups. This tool helps you calculate voltage drop across multiple cord segments and determine if your electrical load is safe for a given outlet.

## ✨ Features

- **Multi-Segment Support**: Combine different lengths and gauges (AWG) of extension cords to see the cumulative impact.
- **Dynamic Load Calculation**: Add multiple electrical products to see the total current draw and remaining capacity.
- **Total Voltage Drop**: Calculates the absolute voltage loss for the entire load across your specific cord combination.
- **Safety Indicators**: Color-coded safety results based on standard electrical guidelines (Excellent, Safe, Warning, Overload).
- **Split Settings Panel**: Easily manage your visible products and cord combos in a side-by-side organized view.
- **Persistent Storage**: Saves your custom products and cord combinations locally in your browser.

## 🚀 How to Use

1. **Set Global Settings**: Enter your source voltage (e.g., 120V) and the amperage of your outlet (15A or 20A).
2. **Manage Products**: Add your electrical devices (Air Conditioners, Power Tools, etc.) with their Amp or Watt ratings.
3. **Manage Cords**: Create cord combinations by adding segments with specific lengths and gauges.
4. **View Results**: Check the table to see the Voltage Drop %, Safety Result, and Total Load for every combination of your visible items.

## 🛠️ Technical Details

- **Language**: HTML5, CSS3, JavaScript (ES6+)
- **Calculations**: Uses standard AWG resistance values (Copper at 75°C approx) and the formula:  
  `Vdrop = (2 * L * R * I) / 1000`
- **Zero Dependencies**: Pure vanilla web technology. No frameworks or external libraries required.

## 🌐 Deployment

This project is optimized for [GitHub Pages](https://pages.github.com/).

---
*Created for efficient electrical planning and safety.*
