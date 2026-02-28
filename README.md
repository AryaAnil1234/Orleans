<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

LIVE BUS ROUTER FOR THRISSUR 🎯

## Basic Details

### Team Name: [Name]

### Team Members
- Member 1: GOURI C.S - Vidya academy of science and technology
- Member 2: ARYANANDA ANILKUMAR - Vidya academy of science and technology

### Hosted Project Link
https://aryaanil1234.github.io/Orleans/
### Project Description

A **mobile-friendly web application** for Thrissur city buses that allows users to **search buses between any two stops**. It features **autocomplete for source and destination**, displays **bus numbers, boarding and ending points, and arrival times**, and can **track the current status of specific buses** to detect delays in real-time.


### The Problem statement
Commuters in Thrissur often face difficulty in finding available buses between specific locations and estimating their arrival times. Manual searches or asking around are time-consuming and inefficient. There is a need for a digital solution that provides real-time bus route information, including bus numbers, stops, timings, and live status, to help passengers plan their journeys efficiently.

### The Solution
The project provides a web-based bus route application for Thrissur city that allows users to select source and destination with autocomplete suggestions. It displays all buses operating on that route along with their boarding point, ending point, and expected arrival times. Additionally, it includes a live status feature to detect delays and show the current location of selected buses, making commuting faster, convenient, and reliable.
---

## Technical Details


### Technologies/Components Used
For Software:
Languages used: JavaScript, HTML, CSS
Frameworks used: None (vanilla JS front-end; can be extended with React if needed)
Libraries used: None (pure JS; fetch() for JSON handling)
Tools used: VS Code, Git, Browser (Chrome/Firefox/Edge for testing

---

**Features**
Feature 1: Autocomplete for Stops – Source and destination fields suggest bus stops dynamically as the user types, making selection faster and error-free.
Feature 2: Route Search – Displays all buses traveling from the selected source to the selected destination.
Feature 3: Bus Timings Table – Shows each bus’s number, boarding point, ending point, and expected arrival times at the selected stops.
Feature 4: Live Bus Status & Delay Detection – Tracks specific buses (like Bus 113) in real-time based on current time, showing the bus’s location and detecting delays.


Here’s a complete Implementation section tailored for your Thrissur Bus Route Web Project, ready to include in your documentation:

**Implementation**
**For Software:**
Installation
# 1. Clone the project repository
git clone <repository-url>
cd thrissur-bus-route

# 2. Place the JSON file (places.json) in the project folder
# Ensure index.html, style.css, and script.js are in the same directory or correct paths

# 3. Open index.html directly in your browser
# OR run a local server (recommended for fetch requests):
python -m http.server 8000
# Open http://localhost:8000 in your browser
Run
# If using direct browser:
# Open index.html in any browser (Chrome, Firefox, Edge)

# If using local server:
# python -m http.server 8000
# Visit http://localhost:8000
For Hardware:
Note: This project is entirely software-based; no hardware components are required.
Components Required: none
Circuit Setup:not applicable

**Project Documentation**
The project consists of:
HTML Front-End – Contains input fields for source and destination, autocomplete dropdowns, and buttons for searching routes and checking bus status.
CSS Styling – Responsive and mobile-friendly layout for usability on different devices.
**JavaScript Logic** – Handles:
Loading JSON data (bus stops and buses with timings)
Autocomplete feature for selecting stops
Filtering buses for a selected route
Displaying results in a table format
Live bus status detection based on current time and delays
**JSON Data**– Stores all bus stop names and bus details, including:
Bus number:
Boarding point:
Ending point:
Stops along the route:
Timings at each stop

User Flow:
User enters source and destination
Autocomplete helps select valid stops
Clicking Search displays all buses traveling the route
Clicking Check Live Status shows real-time location and delay of selected buses (e.g., Bus 113)
### For Software:

#### Screenshots (Add at least 3)

![Screenshot1]()#### Screenshots (Add at least 3)

![Screenshot1](This screenshot shows the search interface with source and destination input fields. The autocomplete dropdown displays suggestions for bus stops as the user types)
*Add caption explaining what this shows*

![Screenshot2](This screenshot displays the route search results in a table format. It lists all buses operating between the selected source and destination, showing the bus number, boarding point, ending point, and arrival times at the selected stops.)
*Add caption explaining what this shows*

![Screenshot3](This screenshot shows the live status feature for Bus 113. It displays the bus’s current location, whether it is at a stop, between stops, or delayed, based on real-time calculations.)

#### Diagrams

**System Architecture:**

The system architecture illustrates the components and data flow of the application:

User Interface (HTML/CSS/JS) – Provides the input fields, search button, results table, and live status display.
JSON Data – Stores all bus stop names and bus details including stops and timings.
JavaScript Logic – Handles autocomplete, route search filtering, table generation, and live bus status calculation.
Data Flow – User inputs → JS processes JSON → UI displays filtered results and bus status.


**Application Workflow:**

The application workflow shows the step-by-step process:
The user enters source and destination → autocomplete helps select valid stops.
Clicking Search → JS filters buses that pass from source → destination.
Search results are displayed in a table with bus details.
Clicking Check Live Status → the system calculates the current bus location based on timing and detects any delays.

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
