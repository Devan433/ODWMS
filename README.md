ODWMS: On-Demand Waste Management System

ODWMS is a comprehensive end-to-end waste management ecosystem developed as part of the Binnit project. It is designed to streamline eco-waste collection by connecting residents, waste collectors, and administrators through a unified, real-time platform.

Project Structure

The project is organized as a monorepo consisting of three primary modules:

user_app/
A Flutter-based mobile application that enables residents to schedule waste pickups, track collectors in real time, and manage their recycling history.
collector_app/
A Flutter-based mobile application designed for waste collection personnel to manage assigned tasks, navigate optimized routes, and monitor earnings.
admin_dashboard/
A web-based administrative interface that provides system-wide oversight, including assignment management and operational monitoring.
Getting Started
1. Prerequisites
Flutter SDK (stable channel)
Node.js (required for running the admin dashboard)
Firebase CLI (for backend configuration and rule management)
2. Running the Admin Dashboard

The admin dashboard is a lightweight JavaScript application that can be served locally:

cd admin_dashboard/Admin_web
npx live-server .

3. Running the Flutter Applications

Navigate to the respective directories and execute the following commands:

# User Application
cd user_app/eco_waste_app
flutter pub get
flutter run

# Collector Application
cd collector_app
flutter pub get
flutter run

Technology Stack
Mobile Frontend: Flutter, Dart
Web Frontend: HTML5, CSS3, JavaScript
Backend: Firebase (Firestore, Authentication, Cloud Storage)
Routing and Real-Time Tracking: OSRM (Open Source Routing Machine)
License

This project is licensed under the MIT License. Refer to the LICENSE file for further details.

Documentation

For detailed development progress and updates, refer to:
user_app/Binnit_Progress_Report.md
