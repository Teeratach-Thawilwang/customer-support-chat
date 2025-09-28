# <img src="./logo_icon.png" width="28"/> Customer Support Chat

A real-time customer support system built as a practice project to explore:

- Real-time communication using WebSocket
- Backend microservices with NestJS
- Frontend development with NextJS
- Mobile app development with Flutter

The project scope is intentionally kept small for faster completion while still covering essential concepts.

## 📚 Tech Stack

- Backend → NestJS
- Web → NextJS
- Mobile → Flutter

## 🎨 Design

Designed in Figma:
👉 [Figma](https://www.figma.com/design/utKxTtAWKMvcxo5hExcV1b/Customer-support-Chat?node-id=0-1&t=BYOvFEKor2Go7FUh-1)

- Mobile App → for customers
- Web App → for human agents

## 🚀 Features

#### 👤 Customer

- Authentication: Sign in / Sign up / Sign out
- View ticket history
- Start new support chats
- Continue chat if ticket status is not closed
- Chat room capabilities:
  - Chat with AI agent
  - Chat with Admin (human agent)
  - Real-time messaging
  - Chat status: typing, sent, read
  - File upload: PDF, images (≤ 10MB)

#### 🧑‍💼 Admin

- Authentication: Sign in / Sign out
- Ticket management with categories:
  - All | Awaiting for agent | Assigned to me | Handled by AI agent
- Filter tickets by status and order
- View list of human agents (10 shown, expandable)
- Chat room capabilities:
- Real-time messaging
- Chat status: typing, sent, read
  - File upload: PDF, images (≤ 10MB)
  - Update ticket status
  - Ticket Information panel with:
  - Assign owner admin (search + checkbox)
  - Internal notes

## 🏷️ Ticket status

- Open → Customer requests admin or AI escalates
- Pending → In progress (e.g., waiting for external action)
- Resolved → Fixed but not confirmed by customer
- Closed → Confirmed resolved by customer
- Abused → Marked as spam/misuse by admin
