# MauiApp1

## Overview

MauiApp1 is a .NET MAUI application for trading Bitcoin. The app allows users to view the current Bitcoin price, buy and sell Bitcoin, and practise their trading skills without risking real money.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) with .NET MAUI workload installed
- An active internet connection to fetch Bitcoin prices

## Running the Application

### 1. Open the Project

1. Open Visual Studio 2022.
2. Select **Open a project or solution**.
3. Navigate to the folder where you have the project files and select the `MauiApp1.sln` file.
4. If needed install this packeges through NuGet
-Newtonsoft.Json
-Microsoft.Maui.Controls
-Microsoft.Maui.Controls.Compatibility
-System.Net.Http

### 2. Build and Run the Project

1. Select your target platform (Android, iOS, Windows, etc.) from the toolbar.
2. Click the **Run** button (green play button). Ensure you have an appropriate emulator or device configured for the selected platform.

## Using the Application

### Start

-  To start trading:
1. Read Tutorial.
2. Open Wallet .
3. Top up your balance.
4. Go to the Trading Page.
5. Enter amount of money to buy a bitcoin.
6. Press "Buy" to buy.

### Start Page
- A short overview of market.
- A small introduction to our application.

### Wallet Page

1. **View Balance**: The wallet page displays your current USD balance and Bitcoin balance.
2. **Top Up Balance**:
   - Click the "Top Up Balance by $1000" button to add $1000 to your USD balance.
3. **Withdraw Funds**:(joke)
   - Enter the amount to withdraw in the "Amount of money to withdraw" field.
   - Enter your card number in the "Card Number" field.
   - Enter the expiry date in the "Date (MM/YY)" field.
   - Enter the CVV in the "CVV" field.
   - (Note: The actual withdrawal functionality needs to be implemented).

### Trading Page

1. **View Bitcoin Price**: The current Bitcoin price is fetched from the CoinGecko API and displayed on the trading page.
2. **Buy Bitcoin**:
   - Enter the amount of money you want to use to buy Bitcoin in the "Amount of money to buy" field.
   - Click the "All" button next to the field to automatically fill in the maximum available balance.
   - Click the "Buy" button to purchase Bitcoin. Ensure you have sufficient balance.
3. **Sell Bitcoin**:
   - Enter the amount of Bitcoin you want to sell in the "Amount of bitcoins to sell" field.
   - Click the "All" button next to the field to automatically fill in the maximum available Bitcoin balance.
   - Click the "Sell" button to sell Bitcoin. Ensure you have sufficient Bitcoin balance.

### Tutorial Page 
- Just a small introduction to trading.

### Button off
- In the upper right corner you can see the off button, it wil close the application.

### News Page
-There you can find all the latest news about crypto.


### Error and Success Messages

- Any errors or success messages during transactions will be displayed at the bottom of the Trading Page.

## Troubleshooting

- Ensure you have an active internet connection for fetching Bitcoin prices.
- If the app fails to start, check the output window in Visual Studio for any error messages.
- Make sure all dependencies are restored by building the project in Visual Studio.
- If the Bitcoin price does not appear then just restart the application until it appears.
- API sometimes can be busy(because of public using).
