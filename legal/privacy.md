---
title: Privacy Policy
---

# Privacy Policy

**Effective Date:** May 26, 2026

This Privacy Policy describes how the AIOS Data Collector software ("the Software") handles data. The Software is a self-use application developed and operated by Keith Quick.

## 1. Sole User

The Software is operated exclusively by Keith Quick for personal use across business entities he owns and operates (including Nicky Quick and Company LLC and Serene Bebe Doula Agency LLC). There are no other users.

## 2. Data Accessed

The Software accesses business data via OAuth-authorized API calls to:

- **QuickBooks Online** (read-only access): bank account balances, accounts receivable, accounts payable, profit and loss summaries, and invoice metadata.
- **Stripe** (read-only access): revenue, charges, customers, subscriptions, and account balances.
- **Other public APIs** as configured: such as foreign exchange rate APIs that require no authentication.

All access is authorized by Keith Quick as the account owner for each connected account.

## 3. Data Storage

All data collected by the Software is stored exclusively on Keith Quick's personal local computer in a SQLite database file. No data is transmitted to any external server, cloud service, or third party.

## 4. Data Sharing

No data collected, processed, or stored by the Software is shared with any third party. No data is sold. No data is used for advertising, profiling, or any commercial purpose beyond Keith Quick's personal business operations.

## 5. Data Retention

Data is retained on Keith Quick's local machine indefinitely, or until manually deleted by Keith Quick. There is no automated transmission, backup, or deletion of data.

## 6. Security

API credentials (OAuth tokens, API keys) are stored in a local `.env` file on Keith Quick's machine. This file is excluded from version control and is not transmitted off the machine.

## 7. Contact

For any questions regarding this Privacy Policy, contact the developer via the GitHub repository hosting this notice.

---

*This Privacy Policy applies only to the AIOS Data Collector self-use application.*
