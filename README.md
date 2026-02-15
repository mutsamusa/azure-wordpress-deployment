# azure-wordpress-deployment
Building and Deploying Wordpress on Microsoft Azure (App Service + MySQL + Custom Domain)

# Deploying WordPress on Microsoft Azure (App Service + MySQL)

## Project Overview
Built and deployed a production-ready WordPress website using Microsoft Azure services including Azure App Service and Azure Database for MySQL.

This project demonstrates cloud deployment, database connectivity, DNS configuration, HTTPS security, and cost monitoring.

---

## Architecture
- Azure App Service (Linux) → WordPress hosting
- Azure Database for MySQL → backend database
- Azure DNS / GoDaddy → custom domain
- Azure Managed SSL Certificate → HTTPS security
- Azure Cost Management → spending control

---

## Live Website
https://mutsamusa.com

---

## Key Skills Demonstrated
- Cloud infrastructure deployment
- Database configuration and connectivity
- DNS and custom domain setup
- SSL/TLS implementation
- Cost monitoring and budgeting

---

## Problems Solved
- Wordpress showed "Error establishing a database connection" because Azure App Service could not communicate with Azure Database for MySQL.
- Solutions
- ↪ corrected environment variables
- ↪ allowed Azure services access to the database

---

## Deployment Steps
1. Created Azure App Service (Linux)
2. Created Azure Database for MySQL
3. Configured WordPress environment variables
4. Configured MySQL networking and firewall rules
5. Connected WordPress to database
6. Purchased and configured custom domain
7. Configured DNS records (A + TXT)
8. Enabled HTTPS with managed certificate
9. Configured cost monitoring

---

## Screenshots

### Azure App Service Overview
![App Service](screenshots/app-service-overview.png)

### Resource Group Overview
![Resource Group](screenshots/rg-overview.png)

### Live Website
![Live Website](screenshots/live-website.jpg)
