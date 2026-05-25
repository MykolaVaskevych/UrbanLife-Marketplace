# UrbanLife — CS4116 Project

A service marketplace web app where customers browse local businesses, request service inquiries, and engage in moderated discussions with providers.

## Features

- Browse and search business service listings
- Customer inquiry system with provider responses
- Moderated discussion threads per service
- User authentication and profile management
- Admin moderation panel

## Stack

- **Backend**: Django 5 · Django REST Framework · JWT auth · Docker · Railway
- **Frontend**: Angular 19 · TypeScript
- **Database**: PostgreSQL (production) / SQLite (dev)

## Team

| Student ID | Name |
|---|---|
| 22372199 | Mykola Vaskevych |
| 22079017 | Vivian Jently |
| 22331549 | Nur Alislam Kastiro |

## Artefacts

- [Design document (PDF)](https://github.com/user-attachments/files/19340238/CS4116.Design.document.pdf)
- [Trello board](https://trello.com/b/dbEAbVVm/cs4116)

## Run

```bash
docker compose up --build
```

Backend: http://localhost:8000  
Frontend: http://localhost:4200
