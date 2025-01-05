
#  Lemon Town
A virtual office and community platform designed for real-time collaboration in interactive virtual rooms. Users can join rooms with others, communicate, and participate in meetings. The platform offers role-based access with three levels: Admin, room-admin, and user. Admins and room-admins manage rooms, users, and maps to ensure smooth operation. Real-time messaging, meetings, and synchronized player movements are enabled by dedicated socket servers with advanced authentication for secure and efficient interactions.

## Demo

There no demo right beacuse there are 3 fucking servers so fuck it for now.......

## Tech Stack  

#### Multiplayer Server & SFU Server (Video Calls / Messaging)  
- **Languages & Frameworks**: TypeScript,Socket.IO,Livekit-server
- **Database**: PostgreSQL (via Prisma)  
- **Authentication**: JWT (JSON Web Tokens)  

#### Main Application  
- **Framework**:Next.js,Livekit 
- **Styling**: Tailwind CSS  
- **Game Engine**: Phaser.js  
- **Authentication**: JWT  
- **Database**: PostgreSQL (via Prisma)  
- **Validation**: Zod  


## Features

#### Virtual Rooms
- Interactive virtual spaces where multiple players can join simultaneously.
- Player movements are synchronized across all users in the same room.
- Users can request virtual meetings with other players in the room.

#### Map 
- Room can be assigned different map
- Admin can add new map
- if no speical map is selected then Default map is provided 

####  Meeting and chat
- meeting feature is provided
- user can request another user for meeting
- user can also join existing meeting if admin of meeting accept request 
- user either can meeting directly using chat or his nearest player get option for meeting  
- in meeting user can also share monitor/apps/tabs 

#### Auth Layers 
- 3 layer in user hierarchy
- Admin - one who manage account,maps,virutal rooms and their admin
- Room_Admin - manages room users in rooms , map of room and name of room
- user - which can join virutal room if he has acces, manage charater and username

