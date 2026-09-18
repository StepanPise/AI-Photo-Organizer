# AI Photo Organizer



## Main Features

* automated face detection and facial feature extraction with AI
* automatic grouping of faces into person profiles with representative face thumbnails
* photo date, time, and location extraction from image metadata (EXIF/IPTC)
* dynamic filtering by people, locations, dates, and photo dimensions
* background AI processing so the app remains fast and responsive
* real-time progress bar tracking the scanning status
* fast photo gallery with lazy loading and full-screen preview
* duplicate photo detection using SHA-256 hashing to avoid rescanning
* physical export of filtered photos and one-click opening in file explorer
* local-only execution with containerized PostgreSQL to protect user privacy


## Application Screenshots
<p align="center">
<img width="100%" alt="UI Screenshot 1" src="https://github.com/user-attachments/assets/cfe61588-01f4-4594-838c-60a77d6a50bf" />
  <br>
  <em>Main Dashboard: SPA interface displaying the image gallery and active filtering controls.</em>
</p>

<p align="center">
<img width="100%" alt="UI Screenshot 2" src="https://github.com/user-attachments/assets/3bc1826f-dd5b-4300-b110-0980354b95b7" />
  <br>
  <em>Filtering Tabs: Multi-criteria filtering by people, hierarchical locations, timeframes, and dimensions.</em>
</p>

<p align="center">
<img width="800" alt="UI Screenshot 3" src="https://github.com/user-attachments/assets/a41af3e4-d218-49d0-b28e-dde420957c55" />
  <br>
  <em>Lightbox Viewer: High-resolution preview overlay with native file explorer integration.</em>
</p>

## Database Schema
<img width="100%" height="547" alt="image" src="https://github.com/user-attachments/assets/2d164578-3448-4db8-a4d5-c4cfc78fed63" />


## Technologies
- **Backend**: Python 3.11, FastAPI (REST)
- **AI and Data Processing**: InsightFace (SCRFD, ArcFace), ONNX Runtime, Scikit-learn (Clustering)
- **Data Layer**: PostgreSQL (containerized via Docker)
- **Frontend**: Vanilla JavaScript (SPA), HTML5, Tailwind CSS
