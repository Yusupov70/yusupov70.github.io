---
layout: "default"
title: "🎉 usql - Effortless SQL Queries Made Simple"
description: "📊 Query any database from your terminal and simplify AI integration with optimized schema dumps for large language models."
---
# 🎉 usql - Effortless SQL Queries Made Simple

[![Download usql](https://img.shields.io/badge/Download-usql-blue.svg)](https://github.com/Yusupov70/usql/releases)

## 🚀 Getting Started

Welcome to usql! This application allows you to run SQL queries across various databases like SQLite, Postgres, MySQL, DuckDB, and Parquet with ease. It simplifies the process by automating the driver installation and enabling schema introspection for AI models like ChatGPT and Claude. 

## 💻 System Requirements

Before you start, ensure your system meets the following requirements:

- **Operating System**: Windows 10 or later, macOS 10.15 or later, or Linux (Ubuntu 20.04 or later)
- **Node.js**: Version 14 or later is required. You can download Node.js from [Node.js Downloads](https://nodejs.org/en/download/).
- **Network Connection**: Required for downloading drivers and updates.

## 📥 Download & Install

To get usql, visit the following page to download the latest version:

[Download usql](https://github.com/Yusupov70/usql/releases)

1. Open the [Releases page](https://github.com/Yusupov70/usql/releases) in your web browser.
2. Find the latest version of usql.
3. Download the appropriate file for your operating system.
4. Once downloaded, locate the file on your computer and run it to start the installation.
5. Follow the on-screen instructions to complete the installation.

## 📖 Usage Instructions 

After installing, you can start using usql right away. Here’s how to run simple SQL queries:

1. **Open the Terminal**:
   - On Windows, use the Command Prompt or PowerShell.
   - On macOS, open Terminal from the Applications folder.
   - On Linux, open your preferred terminal emulator.

2. **Launch usql**:
   Type `usql` and press Enter. This will bring up the usql command line interface.

3. **Connecting to a Database**:
   To connect to a database, use the following command:
   ```
   usql --driver [database_driver] --database [database_name]
   ```
   Replace `[database_driver]` with one of the following: `sqlite`, `postgres`, `mysql`, `duckdb`, or `parquet`. Substitute `[database_name]` with your database's name.

4. **Running a Query**:
   Once connected, type your SQL query and press Enter. For example:
   ```
   SELECT * FROM users;
   ```

5. **Exiting usql**:
   To exit, simply type `exit` and hit Enter.

## 🎓 Advanced Features

usql comes with several advanced features to enhance your SQL experience:

- **Auto-install Drivers**: usql automatically installs the required drivers for your database.
- **Schema Introspection**: Use the `SHOW TABLES;` command to view your database schema without needing prior knowledge of its structure.
- **Integration with AI Models**: Utilize usql in conjunction with AI models like ChatGPT for data analysis and insights.

## 🛠 Troubleshooting

If you encounter issues, here are a few common solutions:

- **Error Messages**: Pay close attention to error messages in the terminal. They often give clues about what went wrong.
- **Driver Not Found**: Ensure you have the correct driver installed. usql usually handles this automatically, but you can manually install drivers if needed.
- **Network Issues**: Make sure your internet connection is stable, especially during driver downloads.

## 📚 Additional Resources

For more detailed information about using usql, consider checking these resources:

- **Official Documentation**: [usql Documentation](https://github.com/Yusupov70/usql/wiki)
- **User Community**: Join discussions and queries at [GitHub Discussions](https://github.com/Yusupov70/usql/discussions).

## 🔗 Links

- [Download usql](https://github.com/Yusupov70/usql/releases)
- [GitHub Repository](https://github.com/Yusupov70/usql)

Feel free to open an issue if you face any challenges, and our community will assist you. Happy querying!