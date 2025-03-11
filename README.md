# My Travel Map App

This personal web application allows me to track and visualize the states I’ve visited, along with highlighted memories and photos for each location. Built with Streamlit, the app features an interactive map where clicking on a state displays custom details about my experiences there.

### Features
- Interactive Map:
Display a US map with state boundaries and clickable markers or regions.

- Memories & Media:
View custom memories, photos, and details for each visited state.

- Local Data Storage:
Store all travel data locally (using JSON, CSV, or SQLite) for personal use without requiring an external database.

- Customizable Interface:
Leverage Streamlit’s easy-to-use components to create a unique and flexible interface.

### 📦 Tech Stack
- **Python**
Core programming language for app logic and data management.
- **Streamlit**
For building and deploying the web app quickly.
- **Mapping Libraries**
Use libraries like Folium (with [streamlit-folium](https://github.com/randyzwitch/streamlit-folium)) or Plotly for interactive maps.

### Installation
1. Clone the Repository

2. Create a Virtual Environment (Optional but Recommended):
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install Dependencies:
```
pip install -r requirements.txt
```

### Usage
1. Prepare Your Data:
Organize your travel data in your preferred format (JSON, CSV, or SQLite). Update the data file path in the app as needed.

2. Run the App:
```
streamlit run app.py
```

3. Interact with the Map:
Click on states or markers to view your memories and associated information.


### Customization
- Map Appearance:
Customize the map style and markers by modifying the mapping library settings in app.py.

- Data Management:
Update your local database file to add or edit travel memories. The app is designed for ease of use with local file storage.

- Additional Features:
Consider integrating new features such as filtering states by visit date, or adding a photo gallery for each location.

### Future Enhancements
- Integrate a richer media display for photos and videos.
- Enhance the UI with additional Streamlit components.
- Explore options for backup or synchronization if you decide to publish the app later.

### License
This project is for personal use. Feel free to modify and adapt it as you see fit.