# Database Schema

MongoDB collections and data schemas.

## User Model
- email (String, unique)
- fullName (String)
- password (String)
- profilePic (String)

## Message Model
- senderId (ObjectId)
- receiverId (ObjectId)
- text (String)
- image (String)

