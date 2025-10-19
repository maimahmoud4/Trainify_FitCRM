# Trainify — Simple Client Manager (Frontend Demo)

**Trainify** is a frontend-only POC (proof-of-concept) web app for managing fitness clients.  
This project was built to satisfy the CSCE 4502 assignment requirements: a responsive HTML/CSS frontend with three pages (Home, Add Client, Client List).

- **Live Demo:** [https://resilient-kitsune-e3911c.netlify.app](https://resilient-kitsune-e3911c.netlify.app)  
- **UI/UX Design (Figma):** [https://www.figma.com/design/WF5zBuADGyC6LCQiNFjOr5/Trainify?node-id=0-1&t=q46DopiFMz8nSPug-1](https://www.figma.com/design/WF5zBuADGyC6LCQiNFjOr5/Trainify?node-id=0-1&t=q46DopiFMz8nSPug-1)


## Project Structure
```
trainify/
├── index.html # Home (Welcome) page
├── add-client.html # New Client Form page
├── client-list.html # Client List page (with search & sample data)
├── css/
│ └── styles.css # Main stylesheet (using Poppins font)
├── assets/
│ └── icons/ # Optional: store external icons here
└── README.md # Project documentation
```

## Features
- **Home page** with hero and feature cards.
- **Add Client page** with form fields: Full Name, Age, Gender, Email, Phone, Fitness Goal, Membership Start Date.
- **Client List page** with 10 sample clients, search/filter by name, and placeholder Edit/Delete actions.
- Responsive layout using **CSS Grid** and **Flexbox**.
- Uses **Poppins** font from Google Fonts to match Figma style.
- No backend — Add/Edit/Delete are placeholders as required by the assignment.

## How to Run Locally
1. Clone or download this repository.  
2. Open the project folder (`trainify/`).  
3. Double-click `index.html` to open it in your browser.  
   - *(Optional)* Use a local HTTP server such as **Live Server** in VS Code for smoother navigation.  
4. Use the top navigation bar to move between pages.

- **Developed by:** Mai Mahmoud  
- **Course:** CSCE 4502 — Frontend Web Assignment  
- **Institution:** The American University in Cairo (AUC)



