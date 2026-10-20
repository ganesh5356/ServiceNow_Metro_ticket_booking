# Book a Metro Ticket — ServiceNow Capstone Project

## Project Overview

**Book a Metro Ticket** is a metro ticket booking solution developed using ServiceNow. It provides a catalog-based interface where passengers can enter their journey details, select metro stations, specify the number of passengers, view fare details, and choose a payment mode.

The project demonstrates how ServiceNow Service Catalog, custom tables, and platform configuration can be used to build a simple ticket booking workflow.

## Objectives

- Create a user-friendly metro ticket booking form.
- Maintain metro station details in a custom ServiceNow table.
- Collect passenger journey and payment information.
- Configure catalog variables for station selection and journey details.
- Explore Service Portal integration and ServiceNow configuration management.

## Technologies Used

- **Platform:** ServiceNow Australia release
- **Development Scope:** Global
- **Service Catalog:** Catalog Builder
- **Database:** ServiceNow platform tables
- **Configuration Management:** ServiceNow Update Sets
- **Version Control and Submission:** GitHub

## Features

### 1. Metro Ticket Booking Form
The catalog item collects the information required to book a metro journey.

### 2. Station Selection
Passengers can select their starting station and destination from the available metro station records.

### 3. Journey Details
The form includes journey type, number of passengers, and fare-related fields.

### 4. Payment Information
Passengers can select a payment mode, such as UPI or card.

### 5. Custom Station Table
A custom table named **Metro Station's Details** stores metro station information.

### 6. Service Portal Interface
The catalog item can be accessed through the Service Portal to provide a user-facing booking experience.

## ServiceNow Components

| Component | Description |
|---|---|
| Catalog Item | Book metro ticket |
| Custom Table | Metro Station's Details |
| Station Name Field | Stores the station name |
| Catalog Variables | Collect journey, passenger, fare, and payment details |
| Metro QR Widget | Custom widget associated with the project |
| Update Set | Packages supported configuration changes |

## Project Structure

```text
book-a-metro-ticket-servicenow/
├── README.md
├── update-set/
│   └── Book-a-Metro-Ticket.xml
├── screenshots/
│   ├── catalog-item.png
│   ├── service-portal.png
│   └── station-table.png
└── documentation/
    └── project-details.md
```

*The filenames above are suggested examples. Replace them with the actual filenames you upload.*

## Setup and Installation

1. Log in to a ServiceNow instance with the required administrative permissions.
2. Import the provided Update Set XML through the supported ServiceNow Update Set workflow.
3. Review the imported configuration and resolve any missing dependencies.
4. Verify the custom metro station table and its station records.
5. Verify the catalog item's variables and configuration.
6. Open the catalog item in Service Portal and test the booking form.

**Note:** The XML file contains only the configuration changes captured in the exported Update Set. Additional station records, dependencies, or other project components may need to be transferred separately.

## Testing

The following checks can be performed:

- Verify that the catalog item is visible in Service Portal.
- Confirm that station names appear correctly in the Starting From and Going To fields.
- Test journey type and passenger selection.
- Verify fare-related fields.
- Test the payment mode selection.
- Confirm that the submission produces the expected ServiceNow record or request.

## Future Enhancements

- Calculate fares automatically based on source and destination.
- Generate a QR code for each confirmed booking.
- Add booking confirmation and cancellation features.
- Integrate a payment gateway in a suitable test environment.
- Provide booking history and administrative reports.

## Learning Outcomes

This project demonstrates practical experience with ServiceNow Catalog Builder, custom tables, dictionary configuration, catalog variables, Service Portal, Update Sets, and GitHub-based project documentation.

## Project Deliverables

- ServiceNow catalog item and configuration
- Custom metro station table
- Exported Update Set XML, where applicable
- Screenshots and project documentation

## Author

**Ganesh Kumar Rao**

ServiceNow Capstone Project — Book a Metro Ticket

## Thank you 


