# 📱 Scanner App

An Android barcode scanner app developed using **Kotlin** and **Firebase Realtime Database** that identifies Israeli products and suggests local Pakistani alternatives. Designed to promote ethical consumer choices through a real-time scanning experience, with a focus on speed, accuracy, and clean architecture.


## 🚀 Features

- 🔍 Barcode scanning with ZXing library or ML Kit
- 🇮🇱 Identifies Israeli products from a Firebase-hosted product list
- 🇵🇰 Suggests local Pakistani alternatives in real time
- 🔄 Uses Firebase Realtime Database for dynamic product updates
- 🧠 Built with MVVM architecture for clean, maintainable code
- 📦 Organized product data with category-based structure


## 🛠️ Tech Stack

- **Language**: Kotlin
- **Architecture**: MVVM
- **Database**: Firebase Realtime Database
- **UI Toolkit**: Android XML
- **Libraries**: ZXing / ML Kit (for barcode scanning), Firebase SDK

---



📂 Folder Structure
bash
Copy
Edit
ScannerApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── ui/              # Activities and layouts
│   │   │   ├── data/            # Model classes
│   │   │   ├── viewmodel/       # ViewModels and LiveData
│   │   │   └── firebase/        # Firebase DB access
├── README.md
├── .gitignore
🧪 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/Scanner-App.git
cd Scanner-App
Set up Firebase

Create a Firebase project

Enable Realtime Database

Add google-services.json to /app

Run the app

Open the project in Android Studio

Connect an Android device or emulator

Click Run

🌐 Firebase Structure (Example)
json
Copy
Edit
{
  "products": {
    "123456789012": {
      "title": "Product X",
      "company": "Israeli Brand",
      "alternative1": "Local Brand A",
      "alternative2": "Local Brand B"
    }
  }
}

✍️ Future Improvements
Add user-authentication for scan history

Export scan results to PDF

Dark mode support

Admin panel for product uploads

👤 Author
Hamza Amjad
📧 11hamza.ha11@gmail.com

🛡 License
This project is licensed under the MIT License. See the LICENSE file for details.
