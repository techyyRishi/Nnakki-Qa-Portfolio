
# Availability and Calendar Testing

## Project
Nnakki – Service Marketplace

## Overview
This section covers provider availability configuration, calendar behaviour, booking slot generation, time-slot restrictions, and scheduling-related workflows.

## Modules Covered
- Provider Availability
- Calendar
- Booking Time Slots
- Working Hours
- Break Time
- Call Out Availability
- Travel Buffer
- Booking Slot Restrictions
- Availability Settings
- Customer Booking Availability
- Reminder Notifications

## Testing Scope

### 1. Availability Configuration
- Default availability setting
- Every Hour and Every Half Hour options
- Save Changes button behaviour
- Availability settings persistence
- Availability configuration across listings

### 2. Calendar and Time Slots
- Available slot generation
- First and last available slot
- Working hours validation
- Provider break time restrictions
- Booking slot visibility
- Slot availability after refresh

### 3. Call Out Availability
- Opening buffer slot restriction
- Closing buffer slot restriction
- Travel buffer before booking
- Travel buffer after booking
- Multiple Call Out bookings
- Booked slot restrictions
- Availability after cancellation

### 4. Booking and Scheduling
- Customer booking time selection
- Booking start and end time
- Existing booking restrictions
- Multiple service duration calculation
- Availability after provider configuration changes
- Reminder notification timing

### 5. Concurrency and Integration
- Two customers attempting to book the same slot
- Overlapping booking prevention
- Availability consistency across listings
- Provider-side booking details
- Customer-side booking details
- Notification consistency

## Test Case Coverage
- Functional Testing
- Negative Testing
- Regression Testing
- Integration Testing
- Concurrency Testing
- UI/UX Testing
- Accessibility Testing

## Test Execution Platforms
- Windows
- Android
- iOS

## Test Documentation
Refer to the test case document in this folder for detailed availability, calendar, scheduling, and booking slot test scenarios.
