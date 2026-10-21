# Employee Performance Management System — Project Overview

## Objective
Build a live web-based performance management system that helps an administrator monitor employees, track performance metrics and visualize progress through interactive charts.

## Main modules
- Admin authentication
- Employee management
- Performance tracking
- Individual employee progress charts
- Overall monthly performance trend
- Department performance comparison
- Live KPI dashboard

## Performance metrics
- Overall performance score
- Productivity
- Quality
- Attendance
- Goal completion

## Live behaviour
The browser refreshes dashboard data every 3 seconds. New employees and performance updates are written to the H2 database and become visible in the KPI cards, tables and charts without restarting Jetty.

## Technology
Java 25, Jakarta Servlet 5, JDBC, H2, Gson, BCrypt, HTML, CSS, JavaScript and Chart.js.
