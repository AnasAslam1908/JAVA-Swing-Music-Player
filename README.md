# JAVA-Swing-Music-Player
## Abstract

The **JAVA-Swing-Music-Player** is a music player application designed to offer users a comprehensive and interactive music experience. The application features a vast music library, enabling users to listen to their favorite songs and create personalized playlists. Users can add songs, delete songs, and manage multiple playlists with ease. With the ability to create and manage an unlimited number of playlists, users can tailor their music experience according to their preferences. The application offers a free solution to access music with minimal hassle, catering specifically to users in Pakistan where similar free apps are limited.

## Chapter 1: Introduction

### 1.1 Background

Music is an art that unites people across cultures and boundaries. Unfortunately, there is a lack of free applications available in Pakistan that offer proper music functionalities. Our application aims to provide a free, easy-to-use music platform for local users, offering them the opportunity to access a vast collection of songs without any costs involved. The app removes the barrier of expensive or limited-access services, allowing users to enjoy music without any hassle.

### 1.2 Objectives

The main objective of this application is to make music more accessible to the public by offering a free music platform. Our goal is to increase the reach of music to users and keep them engaged with the app by providing functionalities like creating and managing playlists. Users can also collect their favorite songs and curate personal playlists, ensuring that they have a tailored music experience that suits their tastes.

## Chapter 2: Literature Review

The **JAVA-Swing-Music-Player** utilizes several key data structures and algorithms to enhance the user experience. The application employs the following:

- **Doubly Linked List (GENERIC):** Enables efficient bidirectional navigation through the playlist, making it easy for users to move to the next or previous song.
  
- **Queue Linked List (GENERIC):** Enforces a First-In-First-Out (FIFO) order, ensuring songs are handled in the proper sequence.

- **Bubble Sort:** Used for sorting the songs by their numbers, ensuring consistency in the playlist, particularly in the shuffle function.
  
- **File Operations:** Optimize data management by storing song and playlist information in text files, allowing users to persist their data across sessions.

- **Dynamic JButton Queue:** A queue of JButtons representing songs and playlists allows real-time updates to the GUI, ensuring interactive playlist management.

- **Randomized Number Assignment:** Introduces unpredictability in the shuffle feature, enhancing the playlist's randomness and making the experience more dynamic.

The integration of these elements was inspired by established principles in data structures and algorithms, contributing to a responsive, user-friendly, and efficient music player application. The literature review ensured that these components were selected based on their suitability for the task, creating a robust and diverse playlist experience.

## Chapter 3: Methodology

### 3.1 Data Structures Selection

- **Doubly Linked List (GENERIC):**
  - The song names in the playlist are stored in a doubly linked list. This data structure allows easy navigation between songs, as users can move to the next or previous song seamlessly within the playlist.
  
- **Queue Linked List (GENERIC):**
  - A queue linked list is used to implement FIFO functionality. It efficiently handles the addition (enqueue) and removal (dequeue) of songs within the playlist, ensuring that the songs are managed in the correct order.

- **Bubble Sort:**
  - Bubble Sort is used to arrange the songs in ascending order by their assigned numbers, particularly in the shuffle method. This ensures that the song order is consistent and follows a predictable pattern.

### 3.2 Implementation

- The **Doubly Linked List** stores the names of the songs in the playlist, allowing for efficient forward and backward movement through the playlist.
  
- **Text File Storage:** The song names and playlists are initially stored in `.txt` files. The files are read to retrieve the playlist data, which is then loaded into memory. The songs and playlists are stored in queues, and whenever new songs are added or new playlists are created, these queues are updated and the data is written back to the `.txt` files.

- **Queue of JButtons:** JButtons representing songs and playlists are stored in a queue. This dynamic queue of JButtons is used to update the GUI in real time. As songs are added or removed from playlists, the JButtons are enqueued or dequeued, ensuring that the GUI remains interactive and updated.

- **Randomized Class:** To add variety to the shuffle feature, a randomized number generator is used to assign numbers to the songs. The songs are then sorted in ascending order, ensuring a consistent and shuffled playlist experience.

By utilizing these data structures and algorithms, the application efficiently manages the music library, playlists, and user interactions, providing a smooth and responsive music experience.

## Features

- **Music Library:** Access a wide range of songs to listen to.
- **Playlists:** Create and manage multiple personalized playlists.
- **Song Management:** Add or delete songs from playlists.
- **Shuffle:** Shuffle songs within a playlist using randomization.
- **Real-Time GUI Updates:** Interactive playlist management with dynamic buttons.

## Installation

### Prerequisites
- Java 8 or higher
- Java Swing for the graphical user interface
