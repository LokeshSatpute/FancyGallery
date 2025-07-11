# 📸 FancyGallery Android App

**FancyGallery** is a modern Android application that downloads and displays a collection of curated images from Flickr, allowing users to view them in a scrollable grid or on an interactive world map. This project combines advanced Android development techniques, including REST APIs, JSON deserialization, caching, WebViews, and OpenStreetMap integration.

---

## ✨ Features

- 🧭 **Bottom Navigation**
  - Seamless switching between Gallery and Map views.
- 🌐 **Flickr Integration**
  - REST API calls over HTTPS to download photos.
  - JSON parsing into Kotlin data classes.
- 🖼️ **Gallery Grid**
  - Loads and displays network images in a RecyclerView grid.
  - Cache refresh on demand.
- 🗺️ **Interactive Map View**
  - Displays photo markers based on geo-coordinates.
  - Supports pan and zoom.
  - Tapping a marker shows the photo; tapping again opens the Flickr page.
- 🌍 **WebView**
  - Embedded browser to view the Flickr page of any photo.
- ⚡ **Performance Optimizations**
  - Coil image loading with memory cache.
  - Custom marker drawables for smooth rendering.
- 💾 **State Persistence**
  - Retains map zoom and center between sessions.
- 🔄 **Data Sharing**
  - Shared ViewModel between Gallery and Map fragments.

---

## 📽️ Demo Video

You can [**click here to watch the FancyGallery demo video**](https://drive.google.com/file/d/1aodCkiGX209BDtAJPo8eYmGG449c3ZKp/view?usp=sharing).


---

## 🛠️ Tech Stack

- **Languages:** Kotlin
- **Architecture:** MVVM
- **Networking:** Retrofit, Moshi
- **Image Loading:** Coil
- **Mapping:** OSMDroid (OpenStreetMap)
- **Navigation:** Android Navigation Component
- **UI:** RecyclerView, WebView, MapView

---


## 🖼️ Screenshots

| Gallery View | Image Viewer |
|---|---|
| ![Gallery Grid](.images/Home.png) | ![Image Viewer](.images/OpenImg.png) |

| Map View | Navigation Drawer |
|---|---|
| ![Map View](.images/Map.png) | ![Options Menu](.images/Options.png) |

✅ *Note: These images are for reference only. Functionality requires a valid Flickr API key and internet connectivity.*

---

## 🚀 Getting Started

To build and run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/FancyGallery.git

Open in Android Studio

Recommended version: Android Studio Giraffe | 2022.3.1 Patch 2

Install SDK Tools

Ensure Android SDK Platform-Tools v34.0.5 are installed.

Sync Gradle

Run on emulator or device

✅ Note:

You will need a free Flickr account to obtain an API key.

Internet permission is enabled in AndroidManifest.xml.

🗂️ Project Overview
This project was completed as part of a mobile development course. It was developed in phases:

Phase 1: Bottom navigation and Flickr API integration.

Phase 2: Gallery grid with caching and WebView for photo pages.

Phase 3: Map view with interactive markers and image overlays.

For details on implementation steps, refer to project documentation or the source code.



📝 License
This project is licensed under the MIT License.

🙌 Acknowledgments
Big Nerd Ranch Guide (BNRG) — inspiration for some components

OSMDroid — open-source mapping library

Flickr — for providing API access to image data

Android Developers — documentation and best practices



