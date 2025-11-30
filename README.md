# Memphis Poverty Fact Sheet (MPFS)

This repository hosts the source code and data for the **Memphis Poverty Fact Sheet website**.

The Memphis Poverty Fact Sheet is an annual report produced to provide the public, non-profits, and policy makers with up-to-date data regarding poverty in Memphis and the surrounding area.

## 📖 About the Project

The Memphis Poverty Fact Sheet is a collaborative effort produced annually by:
*   **Dr. Elena Delavega** (School of Social Work at the University of Memphis)
*   **Dr. Gregory M. Blumenthal** (GMBS Consulting)

The project visualizes and presents data derived from the **American Community Survey (ACS)** to highlight economic trends, poverty rates, and demographic disparities in the region.

## 📂 Repository Structure

The project is a static website consisting of HTML, JavaScript, and data files.

*   **`index.html`**: The main entry point for the website.
*   **`pages/`**: Additional HTML pages for specific reports or sections.
*   **`data/`**: Contains the datasets (likely CSV or JSON) used to populate charts and tables.
*   **`js/`**: JavaScript files handling site logic and data visualization.
*   **`maps/`**: Geographical data and map assets used for spatial visualizations of poverty data.
*   **`img/`**: Static images and assets.

## 🚀 Getting Started

Since this is a static website, you can run it locally without a complex backend setup.

### Prerequisites
*   A modern web browser (Chrome, Firefox, Edge, Safari).
*   (Optional) A simple local server like Python's `http.server` or VS Code's "Live Server" extension is recommended to avoid cross-origin (CORS) errors when loading local data files.

### Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/GregMBS/mpfs.git
    cd mpfs
    ```

2.  **Run locally:**
    *   **Option A (Direct Open):** Locate `index.html` in the folder and double-click to open it in your browser. *Note: Some interactive charts may not load correctly due to browser security restrictions on local files.*
    *   **Option B (Python 3):**
        ```bash
        python -m http.server
        ```
        Then open your browser to `http://localhost:8000`.

## 🛠 Technologies Used
*   **HTML5/CSS3**: Page structure and styling.
*   **JavaScript**: Data processing and interactivity.
*   **Data Sources**: US Census Bureau / American Community Survey.

## ✍️ Credits & Authors

*   **Dr. Elena Delavega** - *University of Memphis, School of Social Work*
*   **Dr. Gregory M. Blumenthal** - *GMBS Consulting*

## 📄 License

*Refer to the repository owner for specific licensing or copyright information regarding the usage of this data and code.*
