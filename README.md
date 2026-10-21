# Employee Performance Management System

A Java Servlet + JDBC + H2 web application for monitoring employee performance in real time.

## Features
- Admin login
- Employee directory
- Employee performance score, productivity, quality, attendance and goal completion
- Interactive monthly performance line chart
- Department performance bar chart
- Live dashboard refresh every 3 seconds
- Add employees and update performance without restarting the server
- H2 in-memory demo data

## Run
```powershell
mvn clean package
mvn jetty:run
```
Open `http://localhost:8080`.

Default admin:
- Email: `tiwaripankaj06202@gmail.com`
- Password: `Pankaj@Vote2026!`

Environment variables `ADMIN_EMAIL`, `ADMIN_PASSWORD`, or `ADMIN_PASSWORD_HASH` can override the defaults.
