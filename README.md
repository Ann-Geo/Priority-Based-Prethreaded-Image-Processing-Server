# Priority-Based-Prethreaded-Image-Processing-Server
Project description
1. An image processing server is developed that interacts with clients through a pool of worker threads
2. The client inputs the color image from the user to the server.
3. The server consists of a main thread and a set of worker threads with the main thread running at a higher priority than the worker threads.
4. The server listens to connection requests and processes the image by converting it to greyscale and sends it back to the client.
5. The client displays both the color and greyscale image
