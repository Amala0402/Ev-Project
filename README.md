# ⚡ EV Charging Station Locator

An interactive **Electric Vehicle (EV) Charging Station Locator** designed to help EV users find nearby charging stations quickly and conveniently.

The application provides a simple web interface where users can explore EV-related information, view nearby charging locations through **Google Maps**, learn about the project's features, and access login and profile sections.

The main goal of the project is to make EV charging more accessible by helping users locate charging stations and plan their charging journey with a clean and responsive interface.

---

# 🚀 Features

* ⚡ Electric Vehicle charging station locator
* 📍 Google Maps integration for locating charging stations
* 🗺️ Interactive map-based station discovery
* 🚗 EV-focused services and information
* 🧭 Route planning support through map navigation
* 📹 Project demonstration video
* 🔐 Login page
* 👤 User profile page
* 💬 Contact/feedback section
* 🏠 Home page with project information
* 📱 Responsive design
* 🎨 Clean and user-friendly interface
* 💻 Navigation between different sections of the website

The repository specifically includes Google Maps integration, responsive navigation, a video section, contact functionality, and EV-oriented features.

---

# 🛠️ Technologies Used

| Technology                         | Purpose                                  |
| ---------------------------------- | ---------------------------------------- |
| **HTML5**                          | Structure of the web pages               |
| **CSS3**                           | Styling and responsive design            |
| **Google Maps**                    | Displaying EV charging station locations |
| **Flexbox**                        | Responsive page layouts                  |
| **CSS Grid**                       | Organizing page content                  |
| **JavaScript / Web functionality** | Supporting interactive web behaviour     |

The repository identifies HTML5 and CSS3 as the primary frontend technologies and Google Maps Embed as the mapping API/component.

---

# 📂 Project Structure

```text
Ev-Project/
│
├── ele.html
│   └── Main EV charging station page
│
├── ele.css
│   └── Styling for the EV page
│
├── login.html
│   └── User login page
│
├── login.css
│   └── Login page styling
│
├── profile.html
│   └── User profile page
│
├── profile.css
│   └── Profile page styling
│
├── electric.png
│   └── EV-related visual asset
│
├── img1.jpeg
├── img2.jpeg
├── img3.jpeg
├── img4.jpeg
│   └── Project images
│
├── ele_video.mp4
│   └── Project demonstration video
│
└── README.md
    └── Project documentation
```

These files are present in the current GitHub repository.

---

# 🔄 System Workflow

```text
                    ┌──────────────────────┐
                    │      User Opens      │
                    │      EV Website      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      Home Page       │
                    │   Project Overview   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Explore EV Services  │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │  Google Maps / EV    │
                    │ Charging Stations     │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Find Nearby Station  │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Plan Route / Journey │
                    └──────────────────────┘
```

---

# 🏠 Home Page

The home page provides the main entry point to the application.

It introduces the EV charging station concept and provides navigation to different sections of the website.

The navigation includes sections such as:

```text
Home
About
Services
Login
Profile
```

This gives users a simple way to move between the different parts of the application.

---

# 📍 EV Charging Station Locator

The main functionality of the project is helping EV users locate charging stations.

The application integrates **Google Maps** to display charging-related locations and provide a visual way for users to explore nearby stations.

```text
User
  ↓
Open Charging Station Locator
  ↓
View Google Maps
  ↓
Identify Nearby Charging Stations
  ↓
Select Suitable Location
  ↓
Plan Journey
```

The repository describes the map as a way to display nearby EV charging stations in real time.

---

# 🗺️ Google Maps Integration

Google Maps is used as the mapping component of the application.

It provides a familiar geographical interface for users and makes it easier to understand where charging stations are located.

### Main Benefits

* 📍 Location-based station discovery
* 🗺️ Visual map representation
* 🚗 Easier journey planning
* 🧭 Navigation support
* ⚡ Convenient EV charging location discovery

The project's README identifies **Google Maps Embed** as the API/mapping component.

---

# 🚘 EV Services

The project presents several EV-oriented features intended to make electric mobility more convenient.

These include:

* Charging station availability information
* Route planning
* EV usage-related information
* Charging station discovery

The current repository presents these as part of the project's smart EV feature set.

---

# 📹 Project Demonstration

The repository includes a dedicated project video:

```text
ele_video.mp4
```

The video provides a visual demonstration of the project and its functionality.

This can help users understand the application without having to run the project first.

---

# 🔐 Login

The project includes a separate login page.

```text
User
  ↓
Login Page
  ↓
Enter User Information
  ↓
Access Application
```

The login interface is supported by:

```text
login.html
login.css
```

These files are included in the repository.

---

# 👤 User Profile

The project also provides a dedicated profile page for the user.

The profile section is implemented using:

```text
profile.html
profile.css
```

This separates profile-related content from the main EV charging interface and provides a foundation for user-specific functionality.

---

# 💬 Contact & Feedback

The application includes a contact section that allows users to submit queries or feedback.

This can be useful for:

* Reporting issues
* Asking questions
* Providing suggestions
* Sharing feedback about the application

The contact form is listed as one of the project's features.

---

# 📱 Responsive Design

The project is designed to work across different screen sizes.

CSS **Flexbox** and **Grid** are used to organize page layouts and support responsive presentation.

```text
Desktop
   │
   ├── Navigation
   ├── Main Content
   └── Map / Services
          ↓
Tablet
          ↓
Mobile
```

The repository specifically describes the design as responsive for mobile, tablet, and desktop devices.

---

# 🎨 User Interface

The interface focuses on keeping EV-related information easy to understand.

The project includes:

* Navigation bar
* EV information sections
* Map section
* Service information
* Video section
* Login interface
* Profile interface
* Contact section
* Responsive layouts

The repository also contains multiple image assets used within the website.

---

# 🧩 Application Architecture

The project follows a simple frontend architecture:

```text
                     EV CHARGING
                     APPLICATION
                          │
            ┌─────────────┼─────────────┐
            ▼             ▼             ▼
         HTML           CSS       Google Maps
            │             │             │
            ▼             ▼             ▼
        Structure      Styling       Location
            │             │             │
            └─────────────┼─────────────┘
                          ▼
                    User Interface
                          │
             ┌────────────┼────────────┐
             ▼            ▼            ▼
          Home         Services       Login
             │                         │
             ▼                         ▼
          Map                       Profile
```

---

# ⚡ User Journey

A typical user interaction can be represented as:

```text
Open Website
     ↓
Explore EV Information
     ↓
Open Charging Station Locator
     ↓
View Map
     ↓
Find Nearby Charging Station
     ↓
Choose Suitable Station
     ↓
Plan Route
```

The objective is to reduce the difficulty of finding charging infrastructure and make EV travel more convenient.

---

# 🌱 Problem Statement

One of the challenges for EV users is knowing **where nearby charging stations are located**, especially when planning a journey.

The project addresses this problem by providing a web-based interface that brings EV charging station discovery and map-based location information together.

```text
Problem
   ↓
Difficulty finding charging stations
   ↓
Need for location information
   ↓
Need for easier route planning
   ↓
EV Charging Station Locator
```

---

# 💡 Project Objectives

The main objectives of the project are:

1. To help EV users locate nearby charging stations.
2. To provide map-based charging station information.
3. To make EV journey planning more convenient.
4. To provide a simple and responsive web interface.
5. To organize EV-related services in one application.
6. To improve the overall accessibility of EV charging information.

---

# 🎯 Project Highlights

* ⚡ Developed an interactive **EV Charging Station Locator**
* 📍 Integrated Google Maps for location-based station discovery
* 🗺️ Provided a map-oriented approach to finding charging stations
* 🚗 Included EV service and route-planning concepts
* 🔐 Added login and profile pages
* 💬 Included a contact and feedback section
* 📹 Added a project demonstration video
* 📱 Designed a responsive interface
* 🎨 Used CSS Flexbox and Grid for layout management
* 🖥️ Built the application using standard web technologies

---

# 🔮 Future Improvements

The project can be extended with several advanced features:

* 🔹 Real-time charging station availability
* 🔹 Charging station search based on current GPS location
* 🔹 Station filtering by charger type
* 🔹 Station filtering by charging speed
* 🔹 Distance calculation from user's location
* 🔹 Estimated travel time
* 🔹 Live navigation integration
* 🔹 Charging station ratings and reviews
* 🔹 User booking functionality
* 🔹 Charging cost estimation
* 🔹 User charging history
* 🔹 Database integration
* 🔹 Secure authentication system
* 🔹 Admin dashboard for managing stations
* 🔹 Real-time station status updates

These improvements could transform the current frontend project into a complete EV charging management platform.

---

# ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Amala0402/Ev-Project.git
```

### 2. Open the Project Folder

```bash
cd Ev-Project
```

### 3. Run the Website

Since the current project is built with HTML and CSS, the main pages can be opened directly in a web browser.

Open:

```text
ele.html
```

You can also use **VS Code Live Server** or another local development server for easier testing.

---

# 🧰 Technology Stack

```text
                 EV CHARGING STATION LOCATOR
                              │
                              ▼
                        HTML5 + CSS3
                              │
               ┌──────────────┼──────────────┐
               ▼              ▼              ▼
           Structure       Responsive       Styling
                              │
                              ▼
                       Google Maps
                              │
                              ▼
                  Charging Station Map
                              │
                              ▼
                         EV Users
```

---

# 📌 Project Summary

The **EV Charging Station Locator** is a frontend web application designed to make electric vehicle charging more accessible.

By combining a responsive web interface with **Google Maps**, the project provides users with a simple way to explore nearby charging stations and understand EV-related services.

The project demonstrates the use of **HTML5, CSS3, responsive layouts, Google Maps integration, multimedia content, navigation, login and profile interfaces** to create a practical web solution for electric mobility.
