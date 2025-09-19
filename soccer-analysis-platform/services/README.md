# Core Services

Microservices architecture for the soccer analysis platform.

## Services

- `video_ingestion/` - Stream processing and video input
- `detection_service/` - Player and object detection
- `tracking_service/` - Multi-object tracking with persistent IDs
- `team_classifier/` - Team assignment and jersey recognition
- `analytics_engine/` - Tactical analytics and metrics
- `visualization_api/` - REST/WebSocket APIs for frontend

Each service is independently deployable and scalable.
