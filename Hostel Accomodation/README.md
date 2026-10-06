# Hostel Management

Hostel Accommodation and Student Services Management System, a DBMS course project prototype.

Pure HTML, CSS and JavaScript. No build step. Data lives in memory and resets on refresh.

## Run locally
Open `index.html` in a browser.

## Publish on GitHub Pages
1. Create a repository and upload `index.html`, `style.css`, `script.js` and `README.md` to the root.
2. Settings > Pages > Source: Deploy from a branch > `main` / root > Save.
3. Your site goes live at `https://<username>.github.io/<repo>/`.

## Tables
STUDENT, HOSTEL, ROOM, ALLOCATION, PAYMENT, COMPLAINT, SERVICE (Hostel 1:N Room, Student 1:N Allocation/Payment/Complaint, Room 1:N Allocation, Hostel 1:N Service).
