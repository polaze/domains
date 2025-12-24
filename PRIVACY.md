# Privacy Policy

**Last Updated:** December 24, 2025

## 1. Introduction

This Privacy Policy explains how our Discord bot (the "Bot") collects, uses, and protects your information. We are committed to protecting your privacy and handling your data responsibly.

## 2. Information We Collect

### 2.1 Automatically Collected Data
- **Discord User ID**: Your unique Discord identifier
- **Usage Statistics**: Command usage counts and timestamps
- **Domain Monitoring Data**: Domains you choose to monitor, expiration dates, and check timestamps

### 2.2 Stored Database Information
We store the following in our database:
- User ID
- User rank (normal, premium, etc.)
- DM preference settings
- Domain snipe records (domain name, TLD, expiration date, status)
- Usage tracking (command type, date)
- Timestamps for account creation and last checks

### 2.3 Message Content
- The Bot processes message content to detect domain names and commands
- Message content is not permanently stored
- Domain names you query or monitor are stored for service functionality

## 3. How We Use Your Information

### 3.1 Service Provision
- To provide domain monitoring and notification services
- To track usage limits and enforce quotas
- To send you notifications about domain status changes

### 3.2 Service Improvement
- To analyze usage patterns and improve the Bot
- To troubleshoot errors and optimize performance

### 3.3 Direct Messages
- We only send DMs if you have opted in via the DM settings command
- DM notifications are sent for domain availability changes

## 4. Third-Party Services

### 4.1 AI Services
- We use OpenRouter, OpenAI, and Anthropic APIs to generate AI responses
- Your prompts may be sent to these services
- These services have their own privacy policies:
  - OpenRouter: https://openrouter.ai/privacy
  - OpenAI: https://openai.com/privacy
  - Anthropic: https://www.anthropic.com/privacy

### 4.2 RDAP Servers
- Domain queries are sent to public RDAP servers (rdap.net, rdap.denic.de, etc.)
- These queries may be logged by RDAP service providers
- We follow RDAP server redirects automatically

### 4.3 Discord
- All Bot interactions occur through Discord's platform
- Discord's Privacy Policy applies: https://discord.com/privacy

## 5. Data Retention

- **Active Monitoring Data**: Retained while domains are actively monitored
- **Usage Statistics**: Retained indefinitely for service improvement
- **Completed Snipes**: Marked as "completed" but retained in database
- **User Accounts**: Retained while you use the Bot

## 6. Data Sharing

We DO NOT:
- Sell your personal information
- Share your data with advertisers
- Publicly disclose domains you monitor

We MAY share data:
- When required by law or legal process
- To protect our rights or safety
- With your explicit consent

## 7. Your Rights

### 7.1 Access and Control
You can:
- View your monitored domains using Bot commands
- Opt in for DM notifications by sniping a domain
- Request data deletion by contacting the Bot administrator

### 7.2 Data Deletion
To request deletion of your data:
- Contact the Bot administrator through Discord
- We will remove your data within a reasonable timeframe
- Some data may be retained for legal or operational requirements

## 8. Security

We implement reasonable security measures to protect your data:
- Database is stored locally with restricted access
- API keys are stored securely in environment variables
- No plain-text storage of sensitive information

However, no method of electronic storage is 100% secure.

## 9. Children's Privacy

The Bot is not intended for users under 13 years of age (or the minimum age required in your jurisdiction to use Discord). We do not knowingly collect data from children.

## 10. International Users

- The Bot may be accessed from various countries
- Data is stored on our servers in Germany
- By using the Bot, you consent to data transfer and processing

## 11. Cookies and Tracking

The Bot does not use cookies or tracking technologies. All interaction occurs through Discord's interface.

## 12. Changes to This Policy

We may update this Privacy Policy from time to time. Continued use of the Bot after changes constitutes acceptance of the updated policy.

## 13. Data Accuracy

While we strive for accuracy:
- Domain information is sourced from third-party RDAP servers
- We cannot guarantee real-time accuracy
- AI-generated content may contain errors

## 14. Your Consent

By using the Bot, you consent to:
- Collection and use of information as described in this policy
- Processing of your data through third-party services
- Storage of your data in our database

## 15. Contact Information

For privacy-related questions, concerns, or data deletion requests, please contact the Bot administrator through Discord.

## 16. Specific Data Processing Details

### 16.1 Domain Monitoring
- Expiration dates are checked at varying intervals based on domain lifecycle stage
- Old checks are tracked to optimize query frequency

### 16.2 Rate Limiting
- Usage is tracked per user per day
- Limits vary by user rank
- Rate limit data is stored in the usage table

### 16.3 Automated Processing
- The Bot automatically reacts to domain names posted in chat
- RDAP queries are made automatically for valid domain formats
- No human review of these automated processes occurs

---

By using the Bot, you acknowledge that you have read and understood this Privacy Policy.
