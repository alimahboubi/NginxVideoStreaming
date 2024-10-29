
# Nginx Video Streaming

Nginx Video Streaming is a setup designed to stream video content using the Nginx web server, optimized with configurations that ensure smooth and reliable video delivery.

## Features

- **Nginx Server**: Configured for high-performance video streaming.
- **Docker Compatibility**: Easily deployable in a Docker container.
- **Scalability**: Configurations allow for handling increased traffic.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/alimahboubi/NginxVideoStreaming.git
   cd NginxVideoStreaming
   ```

2. **Run with Docker**:
   ```bash
   docker build -t nginx-video-streaming .
   docker run -p 8080:80 nginx-video-streaming
   ```

3. **Access the Stream**: 
   Open `http://localhost:8080` in your browser.

## Configuration

- **nginx.conf**: Core Nginx configuration file located in the repository for customizing server settings.

## Project Structure

- **static/**: Directory containing sample video files for streaming.
- **Dockerfile**: Defines the Docker environment setup.
- **nginx.conf**: Nginx configuration optimized for streaming.

## License

This project is open-source and available under the MIT License.
