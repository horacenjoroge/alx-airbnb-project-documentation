# Use Case Diagram - Airbnb Clone Backend

## Overview
This use case diagram visualizes the interactions between different actors and the Airbnb Clone system, showing the key functionalities and relationships within the platform.

## Actors

### Primary Actors
- **Guest**: Users who search for and book properties
- **Host**: Property owners who list their accommodations
- **Admin**: System administrators who manage the platform

### Secondary Actors (External Systems)
- **Payment Gateway**: Third-party payment processing services (Stripe, PayPal)
- **Email Service**: External email service providers (SendGrid, Mailgun)

## Use Cases by Category

### User Management
- **Register Account**: New users create accounts with role selection
- **User Login**: Authenticated access to the platform
- **Manage Profile**: Update personal information and preferences

### Property Management
- **Create Property Listing**: Hosts add new properties to the platform
- **Edit/Delete Listing**: Hosts modify or remove existing properties
- **Search Properties**: Guests find accommodations using filters
- **View Property Details**: Detailed property information and images

### Booking Management
- **Create Booking**: Guests reserve properties for specific dates
- **Manage Bookings**: View and track reservation status
- **Cancel Booking**: Modify or cancel existing reservations

### Payment Processing
- **Process Payment**: Handle guest payments securely
- **Manage Host Payouts**: Distribute earnings to property hosts

### Review System
- **Submit Review**: Guests provide feedback after stays
- **Respond to Review**: Hosts reply to guest reviews

### Communication
- **Send Notifications**: System-wide communication management

### Administration
- **Moderate Content**: Review and approve user-generated content
- **Manage Users**: User account oversight and management
- **View Analytics**: Platform performance and usage metrics

## Key Relationships

### Include Relationships
- Create Booking includes Process Payment
- Registration includes Send Notification
- All booking actions include Send Notification

### Extend Relationships
- Create Listing extends to Moderate Content (approval process)

### Actor Associations
- **Guests** primarily interact with search, booking, and review functionalities
- **Hosts** focus on property management, booking oversight, and guest communication
- **Admins** have access to platform management and monitoring tools

## System Boundaries
The diagram clearly delineates between internal system processes and external service integrations, showing how the Airbnb Clone interacts with third-party payment and communication services.

## Usage Notes
This diagram serves as a foundation for:
- Understanding system scope and functionality
- Identifying user requirements and workflows
- Planning development priorities
- Creating detailed user stories and technical specifications