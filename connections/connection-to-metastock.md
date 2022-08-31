---
description: >-
  This guide walks you through the process of registering a new account for
  MetaStock XENITH, installing the Eikon application and how to connect it via
  VT-Terminal platform
---

# Connection to MetaStock

* ****[**Download and install Metastock XENITH**](connection-to-metastock.md#download-and-install-metastock-xenith)****
* ****[**Launch VT-Terminal with Metastock connection**](connection-to-metastock.md#launch-quantower-with-metastock-connection)****
* ****[**How to add symbol to the chart or other panel**](connection-to-metastock.md#how-to-add-symbol-to-the-chart-or-other-panel)****

### How to install Meta**S**tock XENITH / EIKON and create an account?

Metastock provides trial access to its platform for 1 month. [**Follow the link**](https://www.metastock.com/offer/ek/?whc=quantowerek\&pc=Eq-quantower) and click on the button “_**Get a FREE 1 month trial of XENITH**_”. Select the market data you'd like to subscribe to.

![Prices for subscription to MetaStock XENITH market data ](../.gitbook/assets/pricing-metastoc-xenith-\_-eikon.png)

Metastock offers a database of various analytical data that is divided not only by type, but also by region. For example, if you need market data for a specific exchange, or a region (Asia, Europe), you can easily select it on their website. But we recommend using Metastock support for that, which will help you to create the data plan that will fit your requirements.

![MetaStock Eikon in action](<../.gitbook/assets/screenshot\_3 (1).png>)

**Create an account** to get their products. If you already have an account, please login into the system.

![Login to your account or create a new one](../.gitbook/assets/create-an-account-metastock.png)

### **Download and install Metastock XENITH**

After you have chosen the necessary subscription and created a new account, you need to sign User Agreement, download and install Metastock XENITH. The link is available in your personal cabinet after registration.

### **Launch VT-Terminal with Metastock connection**

Select Metastock connection in the VT-Terminal connection manager and press Connect. That will also launch Metastock software. Enter the credentials you’ve got from Metastock in their application.

![Click on the Connect button and the platform will start Eikon platform automatically](../.gitbook/assets/connection-to-metastock.png)

![MetaStock XENITH Eikon lauching](../.gitbook/assets/thomson-reuters-eikon-connection.png)

### **How to add symbol to the chart or other panel**

{% hint style="warning" %}
Due to API restrictions, connection to MetaStock Xenith can only **find symbols by the exact ticker (!)**
{% endhint %}

The search engine in the Eikon platform allows you to search for stocks by text description or using letters of any case. Unfortunately, this mechanism does not apply to other platforms through the API. 

For this reason, **it is important to use the exact stock ticker as presented on the Eikon platform**. Otherwise, you will not receive search results.

![Use the exact stocks ticker to get market data in VT-Terminal ](<../.gitbook/assets/image (300).png>)

![Use the exact stocks ticker to get market data in VT-Terminal](<../.gitbook/assets/image (298).png>)

![Search by description does not find stocks](<../.gitbook/assets/image (299).png>)

![Search by exact ticker only](<../.gitbook/assets/image (301).png>)

![Search by exact ticker only](<../.gitbook/assets/image (302).png>)
