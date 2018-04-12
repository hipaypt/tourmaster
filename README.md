# HiPay Professional for GoodLayers Tourmaster integration

[![GitHub license](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://raw.githubusercontent.com/hipay/hipay-enterprise-sdk-prestashop/master/LICENSE.md)

## Getting started

To use **Hipay Professional** payments you need to previously create an account. To create a sandbox (test purposes) account please use https://test-www.hipaydirect.com/registration/register and for a live account please use https://www.hipaydirect.com/registration/register.

## Configuration

**What do you need to start?**
- Get your Hipay account webservice access - login and password - from Hipay Professional Administration;
- Create a website, get the ID of the website and the id of the category;

**Get the website category id**
Replace WEBSITEID in one of the folllowing urls, depending on the type of your account: Live or Sandbox (test). For a sandbox account use https://test-payment.hipay.com/order/list-categories/id/WEBSITEID and for a live account use https://payment.hipay.com/order/list-categories/id/WEBSITEID. Use one of the IDs of the list.

**Set your Hipay account in Tourmaster plugin**
- Hipay Live Mode: on for a live account and off for a sandbox account;
- Hipay Webservice Login: webservice access login from your Hipay account;
- Hipay Webservice Password: webservice access password from your Hipay account;
- Hipay Website Category: one of the categories ids of the website;
- Hipay Website Shop ID: id of the shop associated with the website (if you have created one);
- Logo URL: absolute link to an image that is shown in Hipay payment window - usually the website logo;
- Technical Email: email address that receives the result of payment notifications;
- Hipay Website Rating: choose between: ALL, +18, +16 or +12;
- Hipay Account Currency: 3 digit code of the currency of the account;
- Minimum amount: minimum amount to use Hipay as payment method (not yet used);
- Maximum amount: maximum amount to use Hipay as payment method (not yet used);

## Requirements

Uses **SOAP Extension** to generate payments and **SimpleXML Extension** to process payments notifications. Configuration panel will let you know if these extensions are active or not.

## Features

Provide local and international payment methods using an Hipay Professional account, integrated with **GoodLayers Tourmaster**. **GoodLayers Tourmaster**, a Premium WordPress plugin that comes with most complete tour management system. This plugin is especially designed for tour operator, tour package, travel agency, travel ticket seller, transportation ticket and much more.

## License

The **HiPay Professional for GoodLayers Tourmaster integration** is available under the **Apache 2.0 License**. Check out the [license file][project-license] for more information.

[project-issues]: https://github.com/hipaypt/hipay-professional-tourmaster/issues
[project-license]: LICENSE.md
[project-changelog]: CHANGELOG.md
