## Hi there 👋, I'm Andrew

Backend Engineer | Python | Distributed Systems

Building high-performance backend systems, async pipelines, and scalable infrastructure.

📍 Slovakia (EU) – open to relocation  
📧 shvartsae@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/andrew-shvarts-60944b267/

## Tech Stack
**Languages & Frameworks:** Python, FastAPI, Django  
**Databases & ORM:** PostgreSQL, SQLAlchemy, Redis  
**Messaging & Background Jobs:** RabbitMQ, Celery  
**Architecture:** Microservices, Distributed Systems, Async, System Design  
**DevOps & CI/CD:** Docker, Kubernetes, AWS, CI/CD  
**Observability & Testing:** Prometheus, Grafana, Sentry, pytest

## Highlight Projects

### Stereo vision pipeline for generating depth datasets and training a monocular depth estimation model.
The system computes depth maps using stereo cameras and OpenCV, automatically builds a dataset (image, disparity, depth), and uses it to train a U-Net model capable of estimating depth from a single RGB image.

### TROSS — A parallel orchestrator for computer vision and speech processing, designed as the brain of an anthropomorphic robot.
Multi-threaded C++ core with 
 - Python bindings
 - Object detection (ONNX/Haar)
 - Stereo depth estimation
 - Audio processing
 - Thread-safe queues
 - OpenCV

### Team Task Tracker
Track your team's tasks, visualize priorities, and get insights to improve your product. Simple and effective.
Built with Django + PostgreSQL, supporting concurrent users, background jobs (Celery), and real-time updates, featuring priority visualization and burndown charts to help teams ship faster.


### Audio Mistake Detector
Automatically detects errors in voice-over recordings by comparing Whisper-transcribed speech with the original script. 
Uses Levenshtein distance, audio overlap analysis, confidence scores, and timestamps to identify and classify mistakes (factual, diction, missing, duplicate, overlapping).

### Secure Messenger (Rust)
End-to-end encrypted messaging system implementing asymmetric cryptography and a mixnet routing model to resist traffic interception and metadata analysis.

Features:
- mixnet routing
- metadata protection
- secure key exchange

Used in two financial sector deployments (NDA).

