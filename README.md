# Learning Program Operations Tracker

An Excel-based Learning Operations simulation designed to manage and monitor participant registration, course scheduling, attendance, completion, feedback, exceptions, and operational actions.

> **Note:** This is a self-directed simulation using synthetic data. It does not contain real participant, company, or LMS data.

---

## 📌 Project Overview

This project simulates the day-to-day operational activities involved in managing learning programs for employees or participants.

The workbook is designed to help track the complete learning operations workflow — from participant registration and course scheduling to attendance, completion, feedback, exception handling, and follow-up actions.

The simulation contains data for **200 participants** across multiple learning programs.

---

## 🎯 Business Scenario

A learning operations team needs a structured way to:

- Track participant registrations
- Manage course and batch schedules
- Monitor attendance
- Track course completion
- Review participant feedback
- Identify operational exceptions
- Assign and track follow-up actions
- Monitor key learning program KPIs

This workbook brings these activities together into one structured Excel-based tracking system.

---

## 📊 Key Metrics

The dashboard provides visibility into:

- **Total Participants:** 200
- **Registered Participants:** 158
- **Attendance Rate:** 84.2%
- **Completion Rate:** 62.0%
- **Average Feedback:** 4.15 / 5
- **Open Actions:** 101
- **Waitlisted Participants:** 26
- **Dropped Participants:** 16

---

## 🗂️ Workbook Structure

### 1. Read Me
Provides an overview of the workbook, workflow, and simulation context.

### 2. Raw Data
Contains the synthetic participant and learning-program data used throughout the workbook.

### 3. Registration Tracker
Tracks participant registration status including:

- Registered
- Waitlisted
- Cancelled

Also provides registration health monitoring.

### 4. Course Schedule
Tracks:

- Course
- Batch
- Trainer
- Session Date
- Registered Participants
- Capacity
- Available Seats
- Course Status

### 5. Attendance Tracker
Monitors participant attendance and identifies courses requiring attendance follow-up.

### 6. Completion Dashboard
Tracks:

- Completed participants
- Participants in progress
- Dropped participants
- Completion rate
- Average feedback
- Completion and feedback health

### 7. Exception & Action Tracker
Provides an operational follow-up workflow with:

- Action ID
- Participant
- Course
- Batch
- Pending Action
- Priority
- Owner
- Due Date
- Status

This helps identify and manage operational issues requiring follow-up.

### 8. Learning Operations Dashboard
Provides a consolidated view of key operational KPIs and alerts.

---

## ⚙️ Excel Techniques Used

The project uses several Excel features commonly used for operational reporting and tracking:

- COUNTIFS
- AVERAGEIFS
- INDEX/MATCH
- IF formulas
- Data Validation
- Conditional Formatting
- Pivot Tables
- Power Query
- KPI tracking
- Formula-driven exception identification
- Structured data validation and reconciliation

---

## 🔄 Learning Operations Workflow

```text
Participant Registration
        ↓
Course & Batch Scheduling
        ↓
Attendance Monitoring
        ↓
Completion Tracking
        ↓
Feedback Monitoring
        ↓
Exception Identification
        ↓
Action Assignment
        ↓
Follow-up & Status Tracking
        ↓
Operational Dashboard
