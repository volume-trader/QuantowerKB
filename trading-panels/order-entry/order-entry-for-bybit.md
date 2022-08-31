---
description: >-
  How to create an order on Bybit exchange from the OE (order entry) panel and
  the chart trading sidebar. Differences and features of order entry panels for
  Bybit
---

# Order entry for Bybit

Placing of orders on the VT-Terminal platform can be done in several ways:

* using the Order Entry panel (OE)
* Quick order placement through the chart area with a mouse (visual trading)
* via [**DOM Trader panel**](../dom-trader/)****

### **How to place an order from the OE (Order Entry) panel**

* ****[**How to open the Order Entry panel**](order-entry-for-bybit.md#how-to-open-the-order-entry-panel)****
* [**General view of the OE (Order Entry) panel for Bybit**](order-entry-for-bybit.md#general-view-of-the-oe-order-entry-panel-for-the-bybit-exchange)****
* [**Order parameters — Type, Price, Quantity, TP (take profit) and SL (stop loss)**](order-entry-for-bybit.md#select-order-volume)****

### **How to place an order from the Chart trading sidebar**

* ****[**General view of Chart Trading Sidebar**](order-entry-for-bybit.md#general-view-of-the-quick-trade-panel-from-the-chart-for-bybit)****
* [**Order quantity selection**](order-entry-for-bybit.md#order-volume-selection)
* ****[**Quick order quantity buttons**](order-entry-for-bybit.md#quick-change-order-amount-buttons)
* [B**uttons for fast change of order volume Order parameters** ](order-entry-for-bybit.md#order-volume-selection)**- type, TIF, price, algorithmic settings TP (take profit) and SL stop limit (stop loss) orders**

### How to open the Order Entry panel?

Open the main menu by clicking the logo and in the **Trading section** click on the OE icon.

![Open Order Entry panel in general menu](../../.gitbook/assets/oe-general.png)

## General view of the OE (Order Entry) panel for the Bybit exchange

![Order Entry panel for Bybit exchange](<../../.gitbook/assets/image (291).png>)

The entire panel is conventionally divided into several **zones**:

* choice of trading instrument and trading account;
* setting the required order type, TIF condition, order quantity, and the order side (Buy or Sell);
* setting of the order price, stop loss and take profit prices;
* order placing strategy for advanced trading algorithms
* information on current Ask and Bid prices, spread size, as well as an order placement button

### Selection of Order Type, Time if Force and Order Quantity

Bybit exchange provides 3 main order types: **Market, Limit, Conditional orders**.

![](<../../.gitbook/assets/image (290).png>)

You can enter an order volume by specifying the amount in the currency of the quote and as a percentage of the available margin. There are three ways to do this, as described below:

* Enter the desired amount of coins/lots based on the selected trading pair;
* Enter the total amount of the order. This field is very useful when you need to quickly specify the amount of entry into the transaction immediately in the currency of the balance, without recalculating the number of coins on the exchange rate;&#x20;
* Select with the slider the order amount in % of the total maximum available balance taking into account the set leverage.



### TP and SL orders from the OE panel (order entry)

&#x20;Bybit exchange allows users to calculate possible risks even **before opening a transaction (!)** and users can set their goals - TP (Take Profit) and limit losses with SL order (Stop Loss), simultaneously with order entry into position. To do this, on the order entry panel at the same time as setting an order, you can immediately set the necessary parameters TP and SL

![](<../../.gitbook/assets/image (289).png>)

### How to create a Bybit order from the quick order entry panel from the chart&#x20;

Below we will look at how to create an order on the Bybit exchange from the quick order entry panel from the chart. Before we do this, make sure that you have successfully connected to the Bybit exchange, and selected a trading pair from this connection.

You can open the Bybit chart quick order entry toolbar as shown in the figure below:

![](<../../.gitbook/assets/image (272).png>)

### General view of the quick trade panel from the chart for Bybit

&#x20;The general view of the order entry panel for Bybit connection looks like the following and is divided into the following categories:&#x20;

* Account and symbol selection&#x20;
* Order volume selection and direction selection
* Order parameters - type, TIF, price, algorithmic settings.&#x20;
* Mode for Stop Loss and Take Profit.&#x20;
* Order placement parameters (strategy)

![](<../../.gitbook/assets/image (274).png>)

### Order volume selection&#x20;

You can select the order volume by specifying the amount in the quote currency and in percentage of the available margin. This can be done as described below, depending on your trading style and type:

* enter the desired number of coins/lots based on the selected trading pair;&#x20;
* Using the quick change order amount buttons;&#x20;
* enter the total amount of the order. This field is extremely convenient when you need to quickly specify the amount of entry into the transaction immediately in the currency of the balance, without recalculating the number of coins on the exchange rate at the same time;&#x20;
* select with the slider the order amount in % of the total maximum available balance taking into account the set leverage.

![](<../../.gitbook/assets/image (268).png>)

### Quick change order amount buttons&#x20;

The quick change order amount buttons will help you change the specified volume in one click, based on your trading strategy. You can set by default any parameters that you need to quickly change the values. Moreover, the buttons can change not only the specified position volume, but also apply any (!!!) formulas to calculate the order volume. To set your personal values for a quick change of the order, you need to go to the settings of the chart in the menu section "Order entry" and find the field "OE buttons"

![](../../.gitbook/assets/kolvo.jpg)

You can set standard values of the order amount, which corresponds to your risks. This is very convenient for manual trading.

{% hint style="success" %}
Buttons can change not only to a given amount of position, but also apply any formulas
{% endhint %}

![](../../.gitbook/assets/vvod-baibit-ordera-kolvo.gif)

### Order parameters - type, TIF, price, algorithmic settings

Time-in-Force (TIF) parameters determine the length of time an order will continue to run before it is canceled. Bybit provides a variety of TIFs:

![](<../../.gitbook/assets/image (288).png>)

* GTC (Good Until Cancelled) - Orders will work until they are cancelled by the trader or the contract expires;&#x20;
* FOK (or Fill or Kill) - the order will be canceled if it is not executed in full as soon as it becomes available; I
* OC (Immediately or Cancel) - requires that any part of the order that has not been executed as soon as it becomes available in the market will be canceled;

### Post-Only

&#x20;When the "Post-Only" option is checked, the order is not executed as a Taker operation, and therefore a Maker's fee is earned when the order is executed. The order "Post-Only" is automatically cancelled if it can be executed immediately against an existing order in the market.

### Reduce-Only&#x20;

Used to reduce the size of a position and does not increase its size.&#x20;

### TP (Take Profit) and SL Stop Limit (Stop Loss) orders&#x20;

Bybit allows users to calculate potential risks before opening a position (!) and users can set their objectives as TP (Take Profit) and SL (Stop Loss) orders, simultaneously with an order to enter the position. To do this, on the order entry panel at the same time as setting an order, you can immediately set the necessary parameters **TP and SL**

![](<../../.gitbook/assets/image (286).png>)

{% hint style="success" %}
After placing the position, TP and SL can be changed according to the situation directly from the chart by moving the mouse to new levels:
{% endhint %}



![](https://gblobscdn.gitbook.com/assets%2F-M\_\_G3zsA7jr\_pKwIdiz%2F-McD\_QwL-lRHN-5um-7w%2F-McDfC-w\_k3YXQVrVXEV%2F%D1%81%D1%82%D0%BE%D0%BF%20%D0%B8%20%D1%82%D0%B5%D0%B9%D0%BA%20%D0%B1%D0%B0%D0%B9%D0%B1%D0%B8%D1%82.gif?alt=media\&token=daf20a92-ff2f-4aef-834a-cea4a36cedca)

Next comes a large **block of functions for managing the current position**. You can delete or limit orders or stops. You can also reverse your position with a single button or set a lossless position. These are very functional buttons, do not miss them.&#x20;

More detailed settings with trading examples and additional conditions in the ByBit exchange's own "order execution " section
