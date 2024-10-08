# 📡 U.S. Licensed Amateur Radio Operator Interactive Census Map

![Untitled](https://github.com/user-attachments/assets/c2fee911-ffd6-4edc-b3cf-2871927636c0)

Welcome to the **Interactive U.S. Ham Radio Operators Census**! This project visualizes the distribution of licensed ham radio operators across the United States, providing insights into the vibrant amateur radio community. 📅 Last updated: **October 2024**.

## 🌟 Features

- **Interactive Map**: Explore the U.S. map and hover over each state to see the number of licensed operators.
- **Data Visualization**: View the total number of operators and the top 10 states with the most operators.
- **Detailed State Information**: Click on a state to reveal more information about operator classifications (Novice, Technician, General, Advanced, Extra).
- **Responsive Design**: The application is designed to work on both desktop and mobile devices.

## 📊 Data Source

The data is sourced from the **FCC** (Federal Communications Commission) and is updated regularly to reflect the most current statistics. 

- **Data Link**: [FCC ULS Data](http://wireless.fcc.gov/uls/index.htm?job=transaction&page=weekly)

## 🎨 Technologies Used

- **HTML**: Structure the webpage.
- **CSS**: Style the application and ensure responsiveness.
- **JavaScript**: Implement interactive features using:
  - [D3.js](https://d3js.org/) for data visualization.
  - [TopoJSON](https://github.com/topojson/topojson) for geographical data representation.
- **SVG**: Scalable vector graphics for map rendering.

## 🚀 Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/techcow2/usahamcensus.git
   cd usahamcensus
## 📂 Getting Started

### Open index.html
Simply open `index.html` in your web browser to view the interactive map.

### Interacting with the Map:
- Hover over states to view the number of licensed operators.
- Click on a state to see a breakdown of operator classifications.

## 📈 Data Breakdown

Here's a glimpse of the data categories included for each state:
- **Novice**: Entry-level operators
- **Technician**: Operators with basic technical skills
- **General**: Intermediate-level operators
- **Advanced**: Operators with more advanced knowledge
- **Extra**: The highest level of operator certification

## 🎯 Future Improvements
- **Add Filters**: Allow users to filter data by license class.
- **User Contributions**: Enable users to submit their data to keep the census updated.
- **Enhanced Visualizations**: Incorporate additional graphs and charts for better insights.

## 🙌 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

1. **Fork the Repository**
2. **Create a New Branch**: `git checkout -b feature/YourFeature`
3. **Commit Your Changes**: `git commit -m 'Add some feature'`
4. **Push to the Branch**: `git push origin feature/YourFeature`
5. **Open a Pull Request**

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
