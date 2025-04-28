# **India Land Procurement System**

## **Overview**
The India Land Procurement System is a Python-based application designed to analyze land prices across major cities in India. It provides users with insights into land classifications, pricing by zones, and geographical data visualization through interactive maps.

## **Features**
- **City Analysis**: Analyze land prices in predefined major Indian cities.
- **Property Classification**: Classifies properties into government, public, and private categories with respective price modifiers.
- **Zone Pricing**: Provides base prices for different zones such as Central Business District, Residential, Commercial, Industrial, Suburban, and Rural.
- **Geolocation**: Uses the Geopy library to fetch coordinates for cities and properties.
- **Interactive Mapping**: Generates interactive maps using Folium, displaying property locations and price analysis.

## **Installation**
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd india_land_system
   ```

2. **Install required packages**:
   ```bash
   pip install folium geopy
   ```

## **Usage**
1. **Run the application**:
   ```bash
   python india_land_system.py
   ```

2. **Follow the prompts** to enter the city name for analysis. The application will provide:
   - Average land price
   - Cheapest and most expensive properties
   - Price distribution by zone
   - An interactive map with property markers

## **Data Storage**
- The application uses a JSON file (`india_land_data.json`) to store land data. If the file does not exist, sample data will be generated automatically.

## **Map Visualization**
- The generated map will open in your default web browser, displaying:
  - Markers for properties categorized by type (Government, Public, Private)
  - Price analysis statistics in the bottom-left corner
  - A heatmap showing price distribution

## **Contributing**
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Contact**
For any inquiries or issues, please contact:
- **Email**: [hg0217@srmist.edu.in]
- **GitHub**: [github.com/Harsh-Gupta-web])

---

Feel free to modify the contact information and repository URL as needed!
