# TravelBook

TravelBook is an iOS application built with Swift and UIKit. It allows users to mark custom locations on a map, save them with a title and comment, view them in a list, and navigate to any saved location via Apple Maps. Locations are stored persistently using Core Data.

## Features

- Map Interaction
  - Long-press on the map to drop a pin at any location
  - Automatically zooms into selected or saved places
  - Tap on a pin’s info (annotation view) to start Apple Maps navigation
- Apple Maps Integration
  - When a saved pin is tapped, the app opens Apple Maps with driving directions to that location
- Persistent Storage
  - Uses Core Data to store location data permanently
- Details View
  - Each saved location includes a title and comment
  - Saved entries can be deleted via swipe action
- User Interface
  - UITableView for listing saved locations
  - MKMapView for interactive map usage
  - Navigation Controller for screen transitions
- Navigation Flow
  - Smooth transitions between views using storyboard segues
  - User can open saved location details from the list or directly start navigation from the map

 
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/zelihainan/TravelBookApp.git
2. Open TravelBookApp.xcodeproj in Xcode.
3. Build and run on a simulator or device.

Note: Don’t forget to enable Location Services in your simulator:
Features > Location > Custom Location

## Screenshots
<p align="center">
<img width="250" alt="Simulator Screenshot - iPhone 16 Plus - 2025-08-08 at 20 10 20" src="https://github.com/user-attachments/assets/bd634849-0d4a-4255-82f0-a0708c691330" />
<img width="250" alt="Simulator Screenshot - iPhone 16 Plus - 2025-08-08 at 20 10 33" src="https://github.com/user-attachments/assets/19afe5ae-d971-4db6-b7df-19947baa8092" />
<img width="250" alt="Simulator Screenshot - iPhone 16 Plus - 2025-08-08 at 20 10 47" src="https://github.com/user-attachments/assets/613f4553-0d02-4a5c-9a1a-ff86ba524b95" />
<img width="250" alt="Simulator Screenshot - iPhone 16 Plus - 2025-08-08 at 20 10 54" src="https://github.com/user-attachments/assets/b4e6f943-e90e-4ed7-96d8-48bd8a19b23d" />
<img width="250" alt="Simulator Screenshot - iPhone 16 Plus - 2025-08-08 at 20 11 10" src="https://github.com/user-attachments/assets/5b6e99fc-15f9-4dc2-be49-d0a723ab1c2e" />
</p>

