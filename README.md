# YouTube Content Performance Optimization Dashboard

An end-to-end web application that empowers content creators and marketers to analyze and optimize YouTube video performance. This interactive KPI dashboard provides actionable insights using machine learning models, clustering, and real-time data pulled from the YouTube Data API.

## Project Overview

YouTube has become a dominant platform for content consumption, yet creators and marketing teams often lack visibility into what drives true engagement and subscriber growth. Our goal was to build a scalable, real-time analytics solution that answers key questions like:

- What factors drive views, likes, and subscriber growth?
- Which videos or channels are underperforming?
- How can content strategy be improved through data?

This project combines data engineering, machine learning, and visualization into one seamless experience using a modern web interface.

---

## Features

### YouTube KPI Dashboard
- View key performance indicators including:
  - **Views**, **Likes**, **Comments**, **Subscribers**
  - **Engagement per Upload**, **Subscriber Growth Rate**, etc.
- Filter by time range and categories
- Visual comparison across top-performing vs. underperforming content
- Live data integration and customizable layout

### Embedded Chatbot
- Ask questions like:  
  _“What’s the best-performing video this month?”_  
  _“Which brand had the highest engagement rate?”_
- Automatically fetch insights from your uploaded/streamed YouTube dataset
- Built-in typing animation and clean interface

### Machine Learning Insights
- Linear, Ridge, and Lasso regression models to predict:
  - **Subscriber Growth Rate**
  - **View Count**
- K-Means clustering to segment:
  - **High-performing Powerhouses**
  - **Standard Performers**
  - **Rapidly Growing Channels**

### Content Strategy Insights
- Real insights from YouTube metadata (title, tags, published time)
- Track views-per-upload, engagement-per-upload, and upload frequency
- Normalize performance across different-size channels for fair comparison

---

## Tech Stack

- **Frontend**: React + Vite
- **Styling**: Tailwind CSS
- **Visualization**: Recharts
- **AI Chatbot**: Custom logic (can integrate with LLM APIs)
- **Data Engineering (Upstream)**: Pub/Sub, Dataflow, Cloud Functions
- **Modeling**: BigQuery ML, Python (via Colab)

---

## Getting Started

```bash
git clone https://github.com/BrandyHuang/Youtube_Video_Analysis.git
cd kpi-dashboard-website
npm install
npm run dev
