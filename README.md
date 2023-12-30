# Algotive Technical Challenge
## Test Instructions
**Problem**

    You are tasked with building a Django backend system for transmitting video at a specified velocity (x) to a React frontend. The backend should integrate with an AI server for video processing and a Video Management System (VMS) for storage and retrieval.

**Requirements**
1. Django backend
    - Create a Django project named VideoTransmissionSystem.
    - Implement a Django app named video_transmission to handle video transmission.
    - Configure Django settings appropriately.
    - Create a model named Video with fields for title, description, velocity, timestamp, and any other necessary fields.
    - Implement API endpoints for:
        - Uploading a video with metadata.
        - Retrieving a list of all videos.
        - Retrieving a specific video by ID.
2. Integration with an AI server
    - Integrate the backend with a mock AI server (can be a simple mock API or function). The AI server should receive a video and return processed data (you can simulate this step).
3. Integration with the frontend
    - Create a React frontend to interact with the Django backend.
    - Implement a video upload form with fields for title, description, and velocity.
    - Display the list of uploaded videos.
    - Retrieve and display details of a selected video, including processed data, from the AI server.
4. Integration with a Video Management System
    - Integrate the backend with a mock VMS (can be a simple mock API or function) for storing and retrieving videos.
5. Report
    - Write a brief technical report of your solution.
6. Additional guidelines
    - Use Django Rest Framework for API development.
    - Ensure code is modular and follows best practices.
    - Use version control (Git) for your project and make meaningful commits.
7. BONUS
    - Implement proper error handling and validation.
    - Implement user authentication for uploading and accessing videos.
    - Optimize the system for scalability.
    - Dockerize the Django application.
    - Write unit tests for critical parts of your code.