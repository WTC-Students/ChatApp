# ChatApp

**ChatApp** is a modern, minimalistic chat application built using **Java**, **Supabase**, and optionally **Javalin**. It supports user authentication, secure chat storage, and a clean 5-screen user flow. Supabase handles user authentication and data storage using PostgreSQL.

---

## Screens Overview

The application consists of the following five screens:

1. **Welcome** – Entry point with options to sign up or sign in  
2. **Sign Up** – Register a new user using Supabase Auth  
3. **Sign In** – Log in an existing user  
4. **Conversations** – List all conversations the user is part of  
5. **Conversation** – View and send messages within a selected conversation  

---

## Tech Stack

| Layer       | Technology                          |
|-------------|-------------------------------------|
| Language    | Java                                |
| API Layer   | [Javalin](https://javalin.io/)      |
| Database    | [PostgreSQL](https://postgresql.org) via [Supabase](https://supabase.com) |
| Auth        | Supabase Auth                       |
| Realtime    | Supabase Realtime / Polling         |
| Build Tool  | Gradle                              |

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/WTC-Students/ChatApp.git
cd ChatApp
