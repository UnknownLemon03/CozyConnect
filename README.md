
#  Lemon Town
A virtual office and community platform designed for real-time collaboration in interactive virtual rooms. Users can join rooms with others, communicate, and participate in meetings. The platform offers role-based access with three levels: Admin, room-admin, and user. Admins and room-admins manage rooms, users, and maps to ensure smooth operation. Real-time messaging, meetings, and synchronized player movements are enabled by dedicated socket servers with advanced authentication for secure and efficient interactions.

## Demo

[project code](https://github.com/UnknownLemon03/Lemon-Town)

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

## Pictures 
![Screenshot from 2025-01-07 18-32-45](https://github.com/user-attachments/assets/ef86f7f6-1d3b-452c-b1dc-bc8250f7c9fe)
![Screenshot from 2025-01-07 18-33-22](https://github.com/user-attachments/assets/7e0ac09b-1558-4f7d-a525-79a656ae27ef)
![Screenshot from 2025-01-07 18-33-28](https://github.com/user-attachments/assets/cbe70531-8761-47c2-9fa6-a30db64b3f3e)
![Screenshot from 2025-01-07 18-33-33](https://github.com/user-attachments/assets/b35d5c79-3280-4871-956c-81bcbf60d240)
![Screenshot from 2025-01-07 18-33-39](https://github.com/user-attachments/assets/0e5dc92c-c06a-489f-b51e-e5f6ed91d9a3)
![Screenshot from 2025-01-07 18-34-02](https://github.com/user-attachments/assets/a8142ffd-17d8-4167-9850-89e8da222861)
![Screenshot from 2025-01-07 18-34-27](https://github.com/user-attachments/assets/191dbe20-7ce6-45f2-807d-c524bb795fa0)
![Screenshot from 2025-01-07 18-35-28](https://github.com/user-attachments/assets/76d844b4-4dfb-44c1-8891-a41ccaa83ba9)
![Screenshot from 2025-01-07 18-35-45](https://github.com/user-attachments/assets/442a78ca-114a-4910-8197-ffa2fc5e9b41)
![Screenshot from 2025-01-07 18-37-12](https://github.com/user-attachments/assets/fa35c5f9-fb5f-4596-b85b-aca12278f38e)
![Screenshot from 2025-01-07 18-37-43](https://github.com/user-attachments/assets/59245ed4-8c45-4837-b6f9-53f43badd44c)



