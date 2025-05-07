# -Requirement Analysis in Software Development.
This repository documents the process of requirement analysis in software projects. It documents how to properly gather, analyze, and document software requirements in order to deliver successfull projects.

## What is Requirement Analysis?
Requirement Analysis is the process of determining user expectations for a new or modified software product. It is a critical phase in the Software Development Life Cycle (SDLC) where business requirements are translated into detailed technical specifications.

During requirement analysis, stakeholders collaborate to:
- Identify the problem to be solved
- Define the system's functional and non-functional needs
- Establish constraints and assumptions
- Create models and prototypes when necessary

This phase helps ensure that the final product meets business objectives and user needs while minimizing costly changes during later development stages.
## Why is Requirement Analysis Important?

1. **Reduces Project Risks**: Proper analysis helps identify potential issues early, preventing costly rework later in development.
2. **Sets Clear Expectations**: Documents exactly what needs to be built, aligning stakeholders and development teams.
3. **Foundation for Design**: Provides the necessary information for architects and developers to create appropriate technical solutions.
4. **Facilitates Accurate Estimation**: Helps project managers create more realistic timelines and budgets.
5. **Improves Quality**: Clear requirements lead to better testing criteria and higher quality end products.
## Key Activities in Requirement Analysis

- **Requirement Gathering**: Collecting all possible requirements from stakeholders through interviews, surveys, and workshops.
  
- **Requirement Elicitation**: Extracting hidden or unstated needs through techniques like prototyping and user observation.

- **Requirement Documentation**: Creating clear, unambiguous requirement documents like Software Requirement Specifications (SRS).

- **Requirement Analysis and Modeling**: Using tools like use case diagrams, flowcharts, and entity-relationship diagrams to represent requirements visually.

- **Requirement Validation**: Ensuring requirements are complete, consistent, and achievable through reviews and prototyping.

  ## Types of Requirements

### Functional Requirements
These define what the system should do:

1. **User Registration**: The system shall allow new users to create an account with email and password.
2. **Booking Creation**: The system shall enable registered users to create new bookings for available time slots.
3. **Payment Processing**: The system shall process credit card payments for confirmed bookings.

### Non-functional Requirements
These define how the system should perform:

1. **Performance**: The system shall load booking pages in under 2 seconds for 95% of users.
2. **Security**: The system shall encrypt all user passwords using bcrypt hashing.
3. **Availability**: The system shall maintain 99.9% uptime during business hours.

   ## Use Case Diagrams

This diagram shows the key interactions in our booking system:

![Booking System Use Case Diagram](## Use Case Diagrams

This diagram shows the key interactions in our booking system:

![Booking System Use Case Diagram](alx-booking-uc.png)

**Actors**:
- Guest: Unregistered users who can browse availability
- Registered User: Can book, cancel, and pay
- Admin: Manages user accounts

**Use Cases**:
- Browse Availability
- Make Booking
- Cancel Booking
- Process Payment
- Manage Users)

**Actors**:
- Guest: Unregistered users who can browse availability
- Registered User: Can book, cancel, and pay
- Admin: Manages user accounts

**Use Cases**:
- Browse Availability
- Make Booking
- Cancel Booking
- Process Payment
- Manage Users

  ## Acceptance Criteria

Acceptance criteria define the conditions that must be met for a feature to be considered complete. They serve as:
- Test cases for QA teams
- Completion guidelines for developers
- Verification points for stakeholders

**Example for Checkout Feature**:
1. Given a user has selected items to book, when they proceed to checkout, then they should see a summary of their selections.
2. Given a user is at checkout, when they enter valid payment details, then the system should process payment and display a confirmation.
3. Given payment fails, when the user retries with correct details, then the system should complete the booking.
4. Given a successful booking, when the transaction completes, then the system should email a confirmation to the user.
