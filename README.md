# Football Player Tracking and Performance Analysis using AI/ML

This project is a comprehensive AI/ML-based system for analyzing football match videos to track player movement and evaluate their performance metrics, such as speed and distance traveled (in meters) throughout the match.

It integrates several computer vision techniques to process video data and extract meaningful insights:

YOLO (You Only Look Once): Used for real-time object detection to accurately identify and track players and the ball on the field.

K-Means Clustering: Applied for pixel-level segmentation to distinguish between players, teams, and the field background.

Optical Flow: Utilized for motion tracking to estimate the movement of players frame by frame.

Perspective Transformation: Converts 2D video coordinates into a real-world perspective, enabling accurate distance and speed calculations.

By combining these techniques, the system can analyze football match footage and compute each player's speed and total distance covered in meters, offering valuable insights for coaching, player evaluation, and game analysis.
