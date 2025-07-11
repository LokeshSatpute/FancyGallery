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

[![Watch the Demo](images/fancygallery-thumbnail.png)](https://drive.google.com/file/d/1aodCkiGX209BDtAJPo8eYmGG449c3ZKp/view?usp=sharing)

*Click the image above to watch the video on Google Drive.*


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

## 🚀 Getting Started

To build and run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/FancyGallery.git
