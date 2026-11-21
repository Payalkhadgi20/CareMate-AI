
# CareMate AI – Product Requirements Document (PRD)

## 1. Product Overview

CareMate AI is an AI-powered healthcare appointment assistant designed to help users explore medical specialities, discover suitable doctors, check appointment availability, and navigate the booking process.

### Product Goal
Simplify doctor discovery and healthcare appointment booking through a conversational AI experience.

### AI Purpose
The assistant helps users understand medical specialities and navigate appointment booking.

It is not designed to diagnose medical conditions or replace professional medical advice.

## 2. Problem Statement

People often face difficulties:
- Identifying the appropriate medical speciality.
- Finding suitable doctors.
- Checking appointment availability.
- Navigating the appointment booking process.

CareMate AI aims to reduce these difficulties through conversational assistance.


## 3. Target Users and User Personas

### Primary Target Users
- People looking for suitable doctors.
- Users unfamiliar with medical specialities.
- People who find appointment booking confusing or time-consuming.

### User Needs
- Understand which medical speciality may be relevant.
- Discover suitable doctors.
- Find appointment availability.
- Complete the booking process easily.

### User Persona

**Persona: Healthcare Appointment Seeker**

- Goal: Find a suitable doctor and book an appointment.
- Need: Clear guidance throughout the appointment journey.
- Pain Point: Difficulty identifying the right speciality and finding available appointments.
- Expected Experience: Simple, conversational, and easy-to-understand assistance.


## 4. Functional Requirements

| ID | Requirement |
|---|---|
| FR-01 | The system should accept natural-language user input. |
| FR-02 | The AI assistant should ask clarifying questions when user requests are unclear. |
| FR-03 | The assistant should provide non-diagnostic guidance. |
| FR-04 | The system should help users explore medical specialities. |
| FR-05 | The assistant should suggest relevant specialities without diagnosing. |
| FR-06 | Users should be able to select a speciality. |
| FR-07 | The system should support doctor discovery based on selected specialities. |
| FR-08 | The system should help users explore doctor profiles. |
| FR-09 | The assistant should guide users through appointment booking. |

## 5. Non-Functional Requirements

- Reliability: Provide consistent and dependable responses.
- Usability: Maintain a simple and user-friendly conversational experience.
- Privacy: Protect sensitive user information.
- Safety: Avoid medical diagnosis and unsupported medical recommendations.
- Clarity: Communicate information in simple language.


## 6. AI Behaviour and Limitations

### Expected AI Behaviour

1. Understand natural-language appointment requests.
2. Ask clarifying questions when user input is incomplete.
3. Suggest relevant medical specialities without diagnosing.
4. Provide clear and understandable responses.
5. Guide users through doctor discovery and appointment booking.
6. Communicate limitations when reliable information is unavailable.

### AI Limitations

1. The assistant must not diagnose medical conditions.
2. The assistant must not prescribe medicines.
3. The assistant must not replace professional medical advice.
4. The assistant must not invent doctor details or appointment availability.
5. The assistant should direct users to appropriate emergency services when urgent symptoms are reported.

### Reliability and Safety

- Use reliable information sources.
- Communicate uncertainty clearly.
- Protect user information.
- Avoid unsupported medical claims.


## 7. Risks, Dependencies and Assumptions

### Risks
- Incorrect or outdated doctor information.
- Unavailable or inaccurate appointment slots.
- AI-generated responses containing unsupported information.
- User privacy and data security concerns.
- Users misunderstanding AI suggestions as medical diagnosis.

### Dependencies
- Reliable doctor and hospital information.
- Appointment availability data from connected systems.
- Secure backend infrastructure.
- AI model and API availability.
- Appropriate data protection mechanisms.

### Assumptions
- Users need help identifying suitable medical specialities.
- Users value a simple conversational appointment experience.
- Reliable doctor and appointment data can be accessed through integrations.
- Users will review appointment details before confirming a booking.


## 8. Product Roadmap and Launch Plan

### Phase 1 – MVP
- Build conversational appointment assistance.
- Enable speciality exploration.
- Support doctor discovery.
- Provide a basic appointment booking journey.

### Phase 2 – Product Enhancement
- Integrate reliable appointment availability data.
- Improve AI clarification capabilities.
- Improve doctor discovery experience.
- Support appointment status updates.

### Phase 3 – Future Expansion
- Expand hospital and healthcare provider integrations.
- Improve personalization.
- Enhance AI response evaluation.
- Optimize product performance and reliability.

### Launch Plan
1. Complete the initial product prototype.
2. Conduct usability testing.
3. Identify and resolve usability issues.
4. Validate AI behaviour and safety.
5. Evaluate the MVP before considering a wider launch.


## 9. Success Metrics and Measurement Plan

### Primary Success Metrics

1. Task Completion Rate
   - Measures the percentage of users successfully completing the appointment discovery and booking journey.

2. Booking Conversion Rate
   - Measures the percentage of users who complete the appointment booking process.

3. AI Response Accuracy
   - Measures whether AI responses are relevant, accurate, and aligned with product requirements.

4. User Satisfaction
   - Measures user satisfaction with the overall assistant experience.

5. Response Time
   - Measures how quickly the assistant responds to user requests.

### Measurement Plan

- Conduct usability testing.
- Track appointment journey completion.
- Evaluate AI responses using predefined test cases.
- Collect user feedback.
- Monitor response time and reliability.

### Success Evaluation
The product will be evaluated based on usability, task completion, response quality, safety, and user satisfaction.


## 10. Summary

CareMate AI aims to simplify doctor discovery and healthcare appointment booking through an AI-powered conversational assistant.

The product focuses on:
- Understanding user appointment requests.
- Helping users explore medical specialities.
- Supporting doctor discovery.
- Guiding users through appointment booking.
- Providing safe, reliable, and understandable AI assistance.

The product is designed to improve the healthcare appointment experience without replacing professional medical advice.

### Current Project Status

- Product discovery: Documented.
- User research: Conducted.
- PRD: Documented.
- Figma prototype: Created.
- Usability testing: Conducted.
- Product case study: Prepared.

### Next Steps
- Refine the product requirements.
- Define the technical architecture.
- Validate AI behaviour through test cases.
- Improve the prototype based on user feedback.
- Explore future implementation possibilities.

