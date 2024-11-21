# **Airbnb Clone - Use Case Diagram**

This document provides a comprehensive visualization of system interactions in the Airbnb Clone backend. The diagram captures the relationships between users and system functionalities, including user authentication, property management, booking, and payment systems.

---

## **Objective**

The purpose of this diagram is to:
1. Illustrate the interactions between actors (users, property owners, payment gateways, and administrators) and system functionalities.
2. Serve as a foundational guide for understanding system workflows during development.

---

## **System Features and Functionalities**

### **1. User Authentication**
- **Register**: Users create accounts to access the platform.
- **Login**: Authenticate existing users securely.
- **Reset Password**: Allow users to reset passwords via email or phone verification.
- **Multi-Factor Authentication (MFA)**: Enhance security by adding a secondary verification step.

### **2. Property Management**
- **Add Listing**: Property owners upload property details for booking.
- **Edit Listing**: Modify property details and availability.
- **Delete Listing**: Remove properties no longer available for booking.

### **3. Property Booking**
- **Search Property**: Users explore available properties using filters.
- **Book Property**: Reserve properties with instant confirmation.
- **Cancel Booking**: Cancel reservations and manage refunds.
- **View Booking History**: Track past reservations.

### **4. Payments**
- **Make Payment**: Process secure payments for bookings.
- **Process Refund**: Issue refunds for canceled bookings.

---

## **Actors**

### **Primary Actors**
- **User**: Interacts with the platform to search, book, and pay for properties.
- **Property Owner**: Hosts listing properties for rent.

### **Secondary Actors**
- **Payment Gateway**: External system handling payments and refunds.
- **System Administrator**: Oversees platform operations and user management.

---

## **Use Case Diagram**

The use case diagram visualizes:
1. **Actors**: Represented as stick figures.
2. **Use Cases**: Enclosed within ellipses.
3. **System Boundary**: Enclosing rectangle labeled *Airbnb Clone System*.
4. **Interactions**: Lines connecting actors to corresponding use cases.

### **Diagram Details**

#### **Actors and Their Interactions**

| Actor               | Interacting Use Cases                                                      |
|---------------------|----------------------------------------------------------------------------|
| **User**            | Register, Login, Reset Password, Search Property, Book Property, Make Payment |
| **Property Owner**  | Add Listing, Edit Listing, Delete Listing                                  |
| **Payment Gateway** | Make Payment, Process Refund                                               |
| **System Admin**    | Monitors and supports all functionalities                                  |

---

### **Diagram Visualization**

The following image provides a complete visualization of system interactions and functionalities.

![Use Case Diagram](use-case-diagram/use-case-diagram.png)

---

## **Diagram File Location**

- **File Path**: `use-case-diagram/use-case-diagram.png`
- Exported using **Draw.io** for compatibility and future updates.

---

## **How to Contribute**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/steve9948/alx-airbnb-project-documentation.git
   cd alx-airbnb-project-documentation
