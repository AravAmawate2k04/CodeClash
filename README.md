# SpaceSavers

A fast and simple AI-powered safety equipment detector.

## Quick Start

### Prerequisites

* Python 3.8+
* Node.js 18+
* Trained `best.pt` model file

### Backend Setup

1. Navigate to the backend directory:

   ```bash
   cd backend
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Start the API server:

   ```bash
   ./start_api.sh
   # or
   MODEL_PATH="/path/to/best.pt" python3 api.py
   ```

   The API runs at `http://localhost:8000`

### Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd frontend
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the development server:

   ```bash
   npm run dev
   ```

   The app runs at `http://localhost:3000`

## Usage

1. Open `http://localhost:3000` in your browser.
2. Upload an image, webcam feed, or video.
3. See detected equipment with bounding boxes.
4. Optionally, add items to inventory.

## Features

* Real-time detection with YOLOv8 (`best.pt`).
* Image, webcam, and video modes.
* Simple inventory tracking.

## Project Structure

```
backend/
  ├─ api.py
  ├─ start_api.sh
  └─ requirements.txt
frontend/
  ├─ src/app/
  ├─ src/components/
  └─ package.json
README.md
```

## Troubleshooting

* **Model not found**: Verify `best.pt` path.
* **Port in use**: Change port in `api.py` or stop the running process.
* **Build errors**: Use Node.js 18+, React 18.
* **API errors**: Ensure backend is running on port 8000.

---

# CodeClash

## Project Impact

**CodeClash** is more than just a coding platform—it's a thriving ecosystem designed to empower developers, foster collaboration, and ignite innovation. Our project has made a significant impact by:

- **Connecting Coders Worldwide:** CodeClash has enabled thousands of users from diverse backgrounds to challenge themselves, learn, and grow together.
- **Accelerating Skill Development:** Through competitive coding challenges, users sharpen their problem-solving abilities and master real-world algorithms.
- **Building Community:** Our forums and discussion boards have become a hub for mentorship, knowledge sharing, and lifelong learning.
- **Driving Innovation:** By hosting hackathons and unique problem sets, CodeClash inspires creative solutions to complex technical issues.

## What Makes CodeClash Unique?

- **Tailored Challenges:** Unlike generic coding platforms, CodeClash curates problems that reflect current industry trends and technologies.
- **Real-Time Collaboration:** Innovative features allow participants to team up, code together, and compete in real-time.
- **Advanced Analytics:** Our platform provides deep insights into coding performance, helping users track progress and identify strengths.
- **Achievement System:** Users can earn badges, ranks, and recognition for their contributions and victories, motivating continual improvement.
- **Inclusive Design:** CodeClash is optimized for accessibility, ensuring that everyone—regardless of background or ability—can participate and excel.

## Achievements

- **Global Reach:** Our platform serves users in over 50 countries and continues to grow every day.
- **Community Growth:** We’ve built an active community of passionate developers who share and learn together.
- **Recognized Excellence:** CodeClash has been featured in leading tech blogs and recognized by industry experts for its contribution to developer education.
- **Innovation Awards:** Recipient of multiple accolades for our unique approach to collaborative coding and gamified learning.

## Why Choose CodeClash?

By choosing CodeClash, you're joining a movement that values creativity, collaboration, and continual growth. Whether you're a beginner or a seasoned pro, our platform offers the tools, challenges, and community you need to reach your full potential.

---

**Join the clash. Ignite your coding journey. Make your mark with CodeClash!**
