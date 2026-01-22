Chat-app

COMPANY NAME:CODETECH IT SOLUTIONS

NAME:MANSI AMRUTKAR

INTERN ID:CTIS2311

DOMAIN:MERN STACK WEB DEVELOPMENT

DURATION:4 WEEKS

MENTOR:NEELA SANTOSH

Build a Real-Time Chat App with React, Node.js, Socket.IO & Prisma
A full-stack real-time chat application built using React, Node.js,  
Express, Prisma, MySQL, and Socket.IO. This project demonstrates 
how to implement session-based one-to-one chat, real-time messaging ,
and persistent chat history using a modern tech stack. 


| Layer            | Technology                    |
| ---------------- | ----------------------------- |
| Frontend         | React.js (Vite), Tailwind CSS |
| Backend          | Node.js, Express.js           |
| Database         | MySQL with Prisma ORM         |
| Real-Time Engine | Socket.IO                     |
| Authentication   | JWT (JSON Web Token)          |

🔄 Real-Time Communication Flow

1️⃣ User logs in → authenticated using JWT 

2️⃣ User connects to Socket.IO → added to online users map

3️⃣ Chat session is fetched or created (once per user pair) 

4️⃣ Messages are emitted in real time using Socket.IO  

5️⃣ Messages are saved in MySQL via Prisma  

6️⃣ Chat history loads automatically on session open 


