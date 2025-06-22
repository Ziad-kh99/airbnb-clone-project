# AirBnB Clone:
## Overview:
- The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security.

## Technology Stack:
- **Backend**: Python (Django Rest Framework)
- **Database**: PostgreSQL

## Database Design:
- The following ER Diagram represents the initial database design.
- Link: https://lucid.app/lucidchart/2bd08398-3aee-4630-92d6-95afe31784f9/edit?invitationId=inv_ff773498-04ee-42e0-99eb-cd98d14ac405

## Feature Breakdown:
1. API Documentation:
OpenAPI Standard: The backend APIs are documented using the OpenAPI standard to ensure clarity and ease of   integration.
Django REST Framework: Provides a comprehensive RESTful API for handling CRUD operations on user and property data GraphQL: Offers a flexible and efficient query mechanism for interacting with the backend.

2. User Authentication:
Endpoints: /users/, /users/{user_id}/
Features: Register new users, authenticate, and manage user profiles.

3. Property Management:
Endpoints: /properties/, /properties/{property_id}/
Features: Create, update, retrieve, and delete property listings.

4. Booking System:
Endpoints: /bookings/, /bookings/{booking_id}/
Features: Make, update, and manage bookings, including check-in and check-out details.

5. Payment Processing
Endpoints: /payments/
Features: Handle payment transactions related to bookings.


## Team Roles:
### Backend Developer:
- Backend developer implements the core of an app—its algorithms and business logic. 

### DevOps Engineer:
- DevOps engineer serves as a link between the two teams (Dvelopment team and Operations team), unifying and automating the software delivery process and helping strike a balance between introducing changes quickly and keeping an application stable.- DevOps engineer oversee and facilitate code releases on a CI/CD basis.