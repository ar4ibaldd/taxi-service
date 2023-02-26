# Taxi service app
    Simple taxi service app
# Features
    Create new Car / Manufacturer / Driver
    Authentication / Logout options for Driver
    Display cars by authenticated Driver
    Soft delete Car / Manufacturer / Driver
    Display all Cars / Manufacturers / Drivers
    Add Driver to Car
# Structure
    Servlets linked to 3-layer DAO services for each scoped object, covered by a filter 
    to protect data from unauthorised access
# Used technologies
    JDK 17.0.5
    Tomcat 9.0.71
    Maven 3.8.6
    MySQL 8.0
# Start-up instructions
    Download and install Tomcat 9.0.71
    Use SQL-scripts from init_db_sql file
    Configure ConnectionUtil class with your parameters