---
description: >-
  Binance Futures allows traders to trade futures on main cryptocurrencies with
  leverage and open both long & short positions.
---

# Connection to Binance Futures

To start trading on Binance Futures through VT-Terminal platform, you need to open an account and create an **API Key** and **Secret Key**. In this guide, we will show you step-by-step how to set up the connection, change margin type and leverage size.

* ****[**How to create a new Binance Futures account**](./#how-to-create-a-new-binance-futures-account)****
* ****[**How to connect to Binance Futures in VT-Terminal platform**](./#how-to-connect-to-binance-futures-in-quantower-platform)****
* ****[**How to get Full License of VT-Terminal for free with Binance?**](./#how-to-get-full-license-of-quantower-for-free-with-binance)****
* ****[**How to change Leverage and Margin Type**](./#how-to-change-leverage-and-margin-type)****
* ****[**How to load the history of past trades (for previous days)**](./#how-to-load-the-history-of-past-trades-for-previous-days)****
* ****[**How to place Stop Loss and Take Profit for a position (server-side)**](./#how-to-place-stop-loss-and-take-profit-for-a-position-server-side)****
* ****[**How to change Hedge Mode (One position & Multiple positions)**](./#how-to-change-hedge-mode-one-position-and-multiple-positions)****
* ****[**Possible Errors with Binance Futures connection**](errors-with-binance-connection.md)****

## How to create a new Binance Futures account

* Go to the **** [**Binance Futures**](https://www.binance.com/en/futures) official website to open a _**live account**_. \
  If you want to create a _**demo account**_, you can open it on [**Testnet Binance Futures**](https://testnet.binancefuture.com/en/futures) website

![](../../.gitbook/assets/create-account-binance-futures.png)

* Fill in the account registration form with your email and safe password. Click on Create account and you will receive a verification email shortly. Follow the instructions in the email to complete your registration.
* Once you are on the Binance Futures page, you should be able to see the first two characters of your email address associated with your account in the top right corner.

![](../../.gitbook/assets/binance-futures-their-terminal.png)

* Click on the logo of your account and in the _**Settings**_ section select _**API Management**_. Create a new API Key (if you don't have it) and save it.

![](../../.gitbook/assets/api-binance-futures.png)

Once you will create an API key, please click on the **Wallet** menu and select **Futures** section. After confirming the opening of a futures account, an additional option will appear for your key, which is called **Enable Futures**.

Please activate it and after you can connect to Binance Futures in VT-Terminal

![](<../../.gitbook/assets/image (87).png>)

![](<../../.gitbook/assets/image (90).png>)

{% hint style="danger" %}
Go to the futures trading section and take the test to activate your futures account.
{% endhint %}

![](<../../.gitbook/assets/image (316).png>)

## How to connect to Binance Futures in VT-Terminal platform

* Launch VT-Terminal platform and open [Connections Manager](../connections-manager.md). Select Binance Futures in the list and select the type of connections — **INFO** or **TRADING** mode.

![](../../.gitbook/assets/connection-binance-futures.gif)

* For trading, please enter your **API Key** and **Secret Key**.

## How to get Full License of VT-Terminal for free with Binance?

{% hint style="danger" %}
If you already have a binance account and it is older than **1 FEBRUARY  2021**, then you need to create a new account in order to use all the paid quantower features
{% endhint %}

First, you need to register a new account on Binance exchange, that wouldn’t be connected with any referral previously. In order to do this, please follow the [https://accounts.binance.com/en/register](https://accounts.binance.com/en/register) link and fill in the registration form.

{% hint style="danger" %}
Please note! The Referral ID field must be empty. If you see any prefilled ID in this field you should CLEAR YOUR **REFERRAL ID** COOKIES in the browser before registration.
{% endhint %}

![Make sure that the Referral ID field is empty](../../.gitbook/assets/screenshot\_1.png)

### Clearing Referral ID cookies

To clear your saved cookies in the Chrome browser, you should proceed to the “Site information block” and follow the “Cookies section”

![Page cookies can be found via the Page info](../../.gitbook/assets/screenshot\_2.png)

Now select each group of cookies and press the “Remove” button. When there will be no cookies in the list, please, press the “Done” button. Now you should refresh your registration page and make sure that the “Referral ID” field is empty.&#x20;

![Binance stores referral data in cookies](<../../.gitbook/assets/screenshot\_3 (3).png>)

When you’ve created a new account with the Binance exchange you may log in using your new credentials via the VT-Terminal terminal and start using all of its premium features for free.

### How to check that your account has a Full license in VT-Terminal?

Once you created a new account with Binance Spot, Binance Futures, please login to the platform in trading mode with your API Keys. After that, open **** [**Account Info** panel](../../informational-panels/account-info.md) and check that the field **Full license is Enabled**.

![](<../../.gitbook/assets/image (167).png>)

## How to change Leverage and Margin Type

* Binance Futures allows you to trade various instruments and manually change the leverage for each one. To change it, open the [**Symbol Info**](../../informational-panels/symbol-info.md) panel and select the necessary symbol. At the bottom of this panel there is a **Leverage** field where you can change the value and apply it by clicking the **Enter** button.

![](../../.gitbook/assets/leverage-binance-futures.png)

Binance offers two types of margin for futures trading:

**Cross Margin Mode**: Share your margin balance across all open positions to avoid liquidation. In the event of liquidation you risk losing your full margin balance along with any remaining open positions.&#x20;

**Isolated Margin Mode**: Manage your risk on individual positions by restricting the amount of margin allocated to each. If the margin ratio of a position reached 100%, the position will be liquidated. Margin can be added or removed to positions using this mode.

![](../../.gitbook/assets/margin-type-binance-futures.png)

{% hint style="danger" %}
For new accounts on which no trades were made, it is **not possible to change the leverage and margin type**.&#x20;

To enable these functions, you need to make at least 1 trade for current symbol. After that, please restart the platform and these features will be available.
{% endhint %}

![Make one trade to activate Leverage and Margin type for Binance Futures in VT-Terminal](../../.gitbook/assets/symbol-info-binance-futures.png)

## **How to load the history of past trades (for previous days)**

All trades made during the active session of the platform can be displayed on the chart, as well as in the Trades panel. To display trades for previous days, you need to activate the option **"Load user trades history"** in the connection settings.

{% hint style="info" %}
Due to Binance API limitations, it takes several minutes (up to 5 minutes) to load data on past trades. In addition, only data from the last 7 days can be downloaded.
{% endhint %}

![](<../../.gitbook/assets/image (175).png>)

## **How to place Stop Loss and Take Profit for a position (server-side)**

Binance Futures provides **server-side SL/TP orders only for the existed (open) position**. It means that you need to open your position first and after you can set server-side SL/TP.

Server-side SL/TP orders are much safer because are sent directly to the exchange and in case of loss of the Internet or other force majeure, your position will be protected.

{% hint style="info" %}
Binance Futures doesn't allow placing server-side SL/TP for Limit orders!

Our team will add client-side (local) SL/TP for limit orders later.
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=FWVy9dyC1HQ" %}



## **How to change Hedge Mode (One position & Multiple positions)**

**One Position mode** means that traders can only hold positions in one direction under one contract. If you open a short position, anticipating that the price will go down in the longer timeframe, but in the meanwhile wanted to open a long to do a trade for a shorter time frame. You are unable to open positions in both directions at the same time. Opening positions in both directions would result in canceling one another out.

**Multiple Positions mode** means that traders can hold positions in both long and short directions at the same time under the same contract. For example, you could now hold both long and short positions of the BTCUSDT contract at the same time.

![](<../../.gitbook/assets/image (176).png>)
