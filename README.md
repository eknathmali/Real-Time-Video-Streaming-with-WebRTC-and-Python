# Real-Time-Video-Streaming-with-WebRTC-and-Python
# Real-Time Video Streaming with WebRTC and Python

## Introduction

This repository contains the source code for streaming camera frames in real-time from one machine to another using WebRTC and Python. The project demonstrates setting up a WebRTC connection and capturing video frames with OpenCV.

## Features

- Real-time video streaming
- Peer-to-peer communication using WebRTC
- Simple signaling server setup
- Python implementation using aiortc and OpenCV

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Pip (Python package manager)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourgithubprofile/real-time-video-streaming-webrtc-python.git
    cd real-time-video-streaming-webrtc-python
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Start `sender.py` on Remote Server:

```bash
python sender.py
```
### Start `receiver.py` on Local Machine:

```bash
python receiver.py
```
