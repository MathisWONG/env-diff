# 🛠️ env-diff - Easily Spot Configuration Errors

## 💡 Overview

env-diff helps you compare your `.env` files and find any missing or extra variables. This ensures you catch configuration issues before deploying your applications. 

## 🚀 Getting Started

To begin using env-diff, follow these simple steps to download and run the application.

## 📥 Download

[![Download env-diff](https://img.shields.io/badge/Download-env--diff-blue.svg)](https://github.com/MathisWONG/env-diff/releases)

Visit this page to download: [env-diff Releases](https://github.com/MathisWONG/env-diff/releases)

## ⚙️ System Requirements

To run env-diff smoothly, you will need:

- Operating System: Windows, macOS, or Linux
- Disk Space: At least 50 MB of free space
- Internet Connection: Needed for downloading the application

## 🔗 Download & Install

1. Click the link to go to the releases page: [env-diff Releases](https://github.com/MathisWONG/env-diff/releases).
2. On the releases page, find the latest version of env-diff.
3. Download the appropriate file for your operating system.
4. After the download completes, locate the file on your computer.

   - **For Windows:** Look for a `.exe` or `.zip` file.
   - **For macOS:** Look for a `.dmg` file.
   - **For Linux:** Look for a `.tar.gz` file.

5. Run the downloaded file to start setup.
6. Follow the on-screen instructions to complete the installation.

## 👩‍💻 Usage Instructions

Once env-diff is installed, you can start using it to compare your `.env` files. Here’s how:

1. Open a terminal or command prompt on your computer.
2. Navigate to the folder containing your `.env` files. You can do this using the `cd` command.
3. Use the following command format to compare your `.env` files:

   ```
   env-diff file1.env file2.env
   ```

   Replace `file1.env` and `file2.env` with the actual names of your files.

4. The application will analyze the files and show any differences. This will include any variables that are missing or extra in either file.

## ⚡ Example

Here’s a quick example of how to use env-diff:

1. Let’s say you have `development.env` and `production.env`.
   
2. Run the command:

   ```
   env-diff development.env production.env
   ```
   
3. After running this, env-diff might return something like this:

   ```
   Missing variables in production.env:
   - API_KEY
   - DATABASE_URL

   Extra variables in production.env:
   - DEBUG_MODE
   ```

   This tells you which variables you need to add or remove for consistent configuration.

## 📝 Tips for Effective Usage

- Always keep your `.env` files up to date. Compare them regularly, especially before deployments.
- Use descriptive names for your environment variables. This will make it easier to spot mistakes.
- Store sensitive data like API keys securely. Avoid including these in your source-controlled `.env` files.

## 🛠️ Troubleshooting

If you encounter issues while running env-diff, try the following:

1. Ensure the downloaded file is not corrupted. Re-download if necessary.
2. Check that you are using the correct file paths in the command.
3. Make sure you have permission to read the files you are comparing.
4. Look for help on the issues page of this repository or check online forums.

## 📨 Support

If you have questions or need further assistance, you can create an issue in the repository or contact the developer. Detailed support documentation will be available soon.

## 💻 Contributing

Feel free to contribute to the project if you want to add features or fix bugs. Follow these steps:

1. Fork the repository to your account.
2. Make your changes and commit them.
3. Submit a pull request with a clear description of your changes.

Your help can make env-diff better for everyone.

## 📜 License

env-diff is open-source software. You can freely use, modify, and share it under the terms specified in the license document provided in the repository.

## 🌐 Related Links

- [GitHub Repository](https://github.com/MathisWONG/env-diff)
- [Documentation](https://github.com/MathisWONG/env-diff/wiki)
- [Issues and Feature Requests](https://github.com/MathisWONG/env-diff/issues)

Thank you for using env-diff! Visit the release page to get started: [env-diff Releases](https://github.com/MathisWONG/env-diff/releases).