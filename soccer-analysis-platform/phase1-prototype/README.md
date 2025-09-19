# Phase 1: Detection & Tracking Prototype

Core system for player detection, tracking, and basic convex hull visualization.

## Components

- Player Detection (YOLOv8)
- Multi-Object Tracking (DeepSORT)
- Team Classification
- Basic Convex Hull Generation
- Simple Visualization

## Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Download YOLOv8 model to `models/`
3. Add sample videos to `data/sample_videos/`
4. Run: `python src/main.py`

## Testing

Run tests: `pytest tests/`
