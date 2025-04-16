# 👥 User List App

An Android application built with Java that fetches a list of users from a remote API (https://reqres.in), displays them in a custom list view, supports search functionality, pull-to-refresh, and shows detailed information on item click.

## ✨ Features

- 🔍 Search users by name
- 📱 Custom list layout with avatar, name, email, and ID
- 🔁 Swipe-to-refresh functionality
- 📄 Detailed user view on item click
- 📡 API data fetching using OkHttp and Gson
- 📸 Image loading using Glide

## 📸 Screenshots

| User List | Search User | User Detail |
|----------|-------------|-------------|
| ![User List](screenshots/user_list.png) | ![Search](screenshots/search_user.png) | ![User Detail](screenshots/user_detail.png) |

## 🔧 Tech Stack

- Language: Java
- Android SDK: 32
- UI: XML, ListView
- Networking: OkHttp
- JSON Parsing: Gson
- Image Loading: Glide
- Architecture: Activity-based

## 🚀 Getting Started

### Prerequisites

- Android Studio (Arctic Fox or newer)
- Java 8+
- Internet connection for API calls

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/User-List-App.git

2. Open the project in Android Studio.

3. Run the project using an emulator or a physical device.

📁 Project Structure

UserListApp/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/userlistapp/
│   │   │   │   ├── MainActivity.java
│   │   │   │   ├── DetailActivity.java
│   │   │   │   ├── UserAdapter.java
│   │   │   │   ├── User.java
│   │   │   │   ├── ApiResponse.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── activity_detail.xml
│   │   │   │   │   ├── item_user.xml
│   │   │   │   ├── drawable/
│   │   │   │   ├── values/
│   │   │   │   │   ├── strings.xml
│   │   │   │   │   ├── colors.xml
│   │   │   │   │   ├── themes.xml
│   │   │   ├── AndroidManifest.xml
│   ├── build.gradle
├── build.gradle
├── README.md


📦 Dependencies

implementation 'com.squareup.okhttp3:okhttp:4.12.0'
implementation 'com.google.code.gson:gson:2.10.1'
implementation 'com.github.bumptech.glide:glide:4.16.0'
annotationProcessor 'com.github.bumptech.glide:compiler:4.16.0'
implementation 'androidx.swiperefreshlayout:swiperefreshlayout:1.1.0'
implementation 'androidx.appcompat:appcompat:1.4.2'
implementation 'com.google.android.material:material:1.6.1'

🧠 Credits
Developed by Prateek Shinde

You can copy this into a file named README.md at the root of your project.

Let me know if you'd like me to include animated GIFs, add contribution instructions, or tailor it for a submission (like in a hackathon or competition).
