# AI Chat & Object Detection App

## Overview
This Android application integrates two AI functionalities:
- **Real-time AI Chat:** Engage in interactive conversations with an AI model via the Ollama API. Enjoy streaming responses, customizable settings, and a dynamic chat interface.
- **On-device Object Detection:** Leverage TensorFlow Lite to detect objects in images and overlay bounding boxes with labels and confidence scores.

The app showcases advanced mobile AI integration by combining seamless AI chat with real-time object detection capabilities.

## Features
- **AI Chat Interface:**
  - Interactive chat powered by the Ollama API.
  - Real-time streaming of AI responses.
  - Customizable settings including model selection, API endpoint, and system prompt.
  - Connection status testing to verify server connectivity.
  
- **Object Detection Module:**
  - Utilizes TensorFlow Lite for on-device object detection.
  - Overlays bounding boxes and labels on detected objects.
  - Supports custom detection thresholds and multiple delegate options (CPU, GPU, NNAPI).
  - Built on a pre-trained MobileNet model (or similar) to recognize specific objects.

## Technologies & Libraries
- **Android SDK & Java/Kotlin:** Core development platform and languages.
- **Ollama API:** Enables AI chat functionality.
- **OkHttp & Gson:** For asynchronous HTTP communication and JSON parsing.
- **RecyclerView:** Efficiently manages dynamic chat message lists.
- **TensorFlow Lite & Task Library:** For on-device object detection.
- **Material Design Components:** Enhances the UI with modern design elements.
