# User Registration Process Flowchart

## **Objective**
This flowchart illustrates the backend workflow and data flow for the **User Registration** process in a system. It provides a clear visual representation of the steps involved, from user input to successful account creation.

---

## **Flowchart Description**
The flowchart consists of the following key steps:

1. **Start**  
   The process begins when a user initiates the registration.

2. **Input User Details**  
   The user enters their registration details, such as:
   - Name
   - Email address
   - Password

3. **Validate Input**  
   The system verifies that the submitted details meet required rules:
   - Email format validation
   - Password strength check  
   **Decision:**
   - If **Valid**, proceed to the next step.
   - If **Invalid**, return an error message and prompt the user to re-enter their details.

4. **Check for Existing User**  
   The system checks whether the provided email or username already exists in the database.  
   **Decision:**
   - If the user **already exists**, return an error message.
   - If the user **does not exist**, proceed to create the account.

5. **Create Account**  
   Save the user's information securely in the database.

6. **Send Confirmation Email**  
   A confirmation email or OTP (One-Time Password) is sent to the user's email address for verification.

7. **End**  
   The registration process concludes successfully once all steps are completed.

---

## **Flowchart Visual**
The flowchart follows this sequence visually:
- **Start**
- **Input User Details**
- **Validate Input** → Valid / Invalid
- **Check for Existing User** → Yes / No
- **Create Account**
- **Send Confirmation Email**
- **End**

---
