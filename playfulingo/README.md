# Playfulingo


Our app Playfulingo is an app to get people interested in American Sign Language. We have components to learn and games to practice your learning! 

## Backend

For our database we're using Firebase Cloud database Firestore, also using Firebase Authentication for Singing up and Logging in. That instance of the authentication of a particular user assigns an ID to each user. That id is used to fetch relevant information in Firestore and also perform read and write operations.

## Prerequisites

- Ensure you have the Flutter SDK installed on your machine. If not, [Get Flutter here](https://flutter.dev/docs/get-started/install).
- Set up an emulator (Android/iOS) or have a physical device connected to your machine.
- Install cocoapods if needed
- Make sure Git is installed on your machine. If not, [Download Git here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

## Setting Up and Running the Project

### 1. Clone the Repository
To clone this repository to your local machine, open your terminal and enter:
```
git clone https://github.com/your_username/playfulingo.git
```
### 2. Create a New Flutter Project (Optional)
If you're starting fresh and need to create a new Flutter project, use:
```
flutter create playfulingo
```
### 3. Navigate to the Project Directory
Switch to your project directory:
```
cd playfulingo
```
### 4. Check installation(This command won't run if flutter is not configured properly, might need to export path then)
```
flutter doctor
```

### 5. Fetch Dependencies
Inside the project directory, fetch all necessary dependencies:
```
flutter pub get
```

### 6. Run the Flutter App
Finally, build and launch the app on your emulator or connected device:
```
flutter run
```

## Project Structure:

all code files are in lib folder and then the folder names correspond to the functionality. 
 
## Demo 


https://www.youtube.com/watch?v=sBeg7dDgyn8