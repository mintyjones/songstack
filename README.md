# songstack
Repo for T3A2_Full Stack App

# Purpose

The purpose of the application is to allow multiple users to collaboratively create a spotify playlist together. This will be done in real time through the use of websockets and the socket.io library.

# Functionality/Features

Users will be able to create their own rooms, as well as join rooms created by others. The room creator can select seed songs that will inform the song suggestions by the spotify api. Once the game begins, all users will be taken to a new screen where they will have 10 seconds to vote for one of three tracks. After the time expires, the track with the most votes will be added to the playlist, and the next round will begin. As tracks are selected, users will be able to see the growing playlist on their screen. After the game ends, the completed playlist will be displayed to the users, and the room creator will have the option to save the playlist to their personal spotify account.

Users will be able to set their own nickname when they open up the application, this nickname will be how the user is identified inside of the application.

# Target Audience
The target audience for this application is spotify users and music lovers of all ages and demographics. Users do not need to have a spotify account to join rooms and play the game with others, but a spotify account is needed to create a room.

# Tech Stack
- React.js
- Node.js
- Express.js
- Socket.io
- Spotify API
- MongoDB

# Dataflow Diagram
![Data_flow_process](https://user-images.githubusercontent.com/358304/126722670-e4c47b7f-5f9c-468e-ba5d-a849f3ab5c69.png)

# Application Architecture Diagram
![Application_Architecture_Diagram](https://user-images.githubusercontent.com/358304/126722726-07107e4d-f45f-49ca-ad76-2deb66303996.png)

# User Stories
- As a room creator, I want to be in charge of starting the game and moving between rounds so that someone else in the room cannot interrupt my user experience.

- As a room creator, I want to choose a few seed songs before the game starts, so that the reccomended songs from spotify match my musical interests.

- As a room creator, I want to review the playlist after the game has ended before I save it to my spotify account, so that I don't populate my account with a number of unwanted playlists

- As a user, I want to choose my nickname every time I open the app so that I can have a new nickname every time, and also not have to sign up and create an account.

- As a user, I want to see the votes that are being cast by other users in real time, so that I can have more information to base my vote on.

- As a user, I want to see a list of all of the available rooms when I open the app, so that I can quickly join a room and begin playing.

- As a user, I want to be able to leave a room at any time and not have the game end for the other players, so that I'm not locked in until the game is finished.

- As a user, I want to see the nicknames of every person in the room, so that I know who I am playing with.

- As a party host, I want a way to create a playlist for the party, so that the party music can be appreciated by everyone attending.

# Wireframes

## Choose Nickname screen

![1_home_screen_w_splash](https://user-images.githubusercontent.com/358304/126736506-5f29936c-6878-45e5-af13-8debf384067b.jpg)

## Home screen

![2_home_screen](https://user-images.githubusercontent.com/358304/126736511-f343a312-de5e-409d-979e-98cc047f0b47.jpg)

## Create Room screen

![3_Room_Creation](https://user-images.githubusercontent.com/358304/126736517-e9103a54-d38b-4e58-92e8-d65da92c24bd.jpg)

## Room Lobby screen

![4_Room_Lobby](https://user-images.githubusercontent.com/358304/126736523-a8b73b66-96d1-4e82-8803-a520c79817d6.jpg)

## Game screen

![5_Game_screen](https://user-images.githubusercontent.com/358304/126736528-e11a17bc-d22e-4c45-bb65-f8e083acd02a.jpg)

## Game over screen

![6_Game_over](https://user-images.githubusercontent.com/358304/126736534-eccdd9c1-b36f-48c1-bb25-7ed737f5a21c.jpg)

# Trello screenshots

![Trello_screenshot_1](https://user-images.githubusercontent.com/358304/126736732-33217b46-7dd3-4b7b-b7ab-299938a1f48b.png)
![Trello_screenshot_2](https://user-images.githubusercontent.com/358304/126736733-02fdf44b-abed-4725-a758-17b67963f185.png)
![Trello_screenshot_3](https://user-images.githubusercontent.com/358304/126736735-c4ce3d81-007b-4221-9bbd-dffe90295263.png)
![Trello_screenshot_4](https://user-images.githubusercontent.com/358304/126736737-5a2dcce2-165f-42f3-b364-363c0782db85.png)
![Trello_screenshot_5](https://user-images.githubusercontent.com/358304/126736739-2da9da5f-bea4-4072-9d36-ddb641befddf.png)
![Trello_screenshot_6](https://user-images.githubusercontent.com/358304/126736742-34221343-6f1b-4c67-9312-efe87410a203.png)
![Trello_screenshot_7](https://user-images.githubusercontent.com/358304/126736743-0163dc53-9f35-4237-90b3-95fdc8b92669.png)