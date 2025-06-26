# My-Application-BudgetApp-

Budget Tracker App (Kotlin + Firebase)
Purpose of the App:
This app helps users track their personal expenses and income by category. It includes visual analytics 
and gamification to motivate better budgeting habits. The app was developed in Kotlin using Android Studio 
and integrates with Firebase for authentication and data storage.

Key Features:
User authentication with Firebase
Add income and expense transactions
View categorized spending data in a bar chart
Set monthly minimum and maximum budget goals per category
Track how well you are meeting your goals visually
Earn badges for good financial habits (gamification)
Save user profile details and preferences
Navigation using BottomNavigationView

Design Considerations:
Firebase Firestore was used for its real-time sync and ease of use with structured data (transactions, 
profiles, goals, badges).
MVVM-like separation was loosely followed to keep logic readable.
UI built with LinearLayout, ScrollView, RecyclerView, and BarChart from MPAndroidChart.
Optimized for mobile usability and offline-first user experience.
Used EditText and Spinner for input, and BarChart for analytics.

Logging and Comments
Comments have been added to all major classes and functions to explain logic clearly.
Log.d() is used in key places to assist with debugging and show understanding of the code.

Video Demonstration
A full video presentation demonstrates all app features, including authentication, adding transactions, 
viewing analytics, earning badges, and setting goals.
Watch here: [Insert YouTube unlisted video link]

APK Download
The final app-debug.apk is included for quick installation on Android devices.

Folder Structure:
📦app
 ┣ 📂src
 ┃ ┣ 📂main
 ┃ ┃ ┣ 📂java/com/example/myapplication
 ┃ ┃ ┃ ┣ AddTransactionActivity.kt
 ┃ ┃ ┃ ┣ AnalyticsActivity.kt
 ┃ ┃ ┃ ┣ SettingsActivity.kt
 ┃ ┃ ┃ ┣ BadgeActivity.kt
 ┃ ┃ ┣ 📂res
 ┃ ┃ ┃ ┣ layout/
 ┃ ┃ ┃ ┣ drawable/
 ┃ ┃ ┃ ┣ values/

Author
Student 1: Mokgethwa Malose Seema ST10264556
Student 2: Gugu Matutle ST10297839
Module: Open-Source Coding (Introduction)
Code: OPSC6311
