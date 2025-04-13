# Ikemba AI Financial Assistant

<img width="1006" alt="image" src="https://github.com/user-attachments/assets/8ea13dd0-7bca-4faf-92d8-643282ea7c4a" />


## Overview

Ikemba AI is a financial knowledge platform designed to empower individuals in the Global South with practical strategies for economic sovereignty. This repository contains a web-based chatbot interface that delivers Ikemba's financial wisdom directly to users.

Named after the Igbo word for "strength of the people," Ikemba stands at the intersection of fintech, crypto, and AI-driven education, offering frank guidance on navigating unstable economies, preserving wealth, and building financial independence.

## Features

- **Interactive Chatbot Interface**: User-friendly design with an intuitive chat experience
- **Financial Knowledge Base**: Curated responses on topics like inflation protection, cryptocurrency usage, DeFi strategies, business building, and more
- **Quick Topic Access**: Topic pills for immediate access to common financial concerns
- **Mobile Responsive**: Works seamlessly across desktop and mobile devices
- **Standalone Solution**: No server-side dependencies, can be deployed as a static site

## Core Knowledge Areas

The Ikemba chatbot provides guidance on:

- Navigating currency crises and hyperinflation with crypto and stablecoins
- Bypassing exploitative fees and controls through peer-to-peer trade
- Leveraging DeFi protocols for saving, lending, or raising capital outside traditional banks
- Using AI automation and analytics to make smarter business decisions
- Understanding global macro trends and applying that knowledge locally
- Security and privacy practices for financial self-defense

## Mission

Ikemba AI's mission is to equip individuals in the Global South with unapologetic insight and tactics to reclaim economic agency. We believe economic independence is a form of liberation, and we actively support users in waging that liberation struggle one transaction, one lesson at a time.

## Installation and Deployment

### Local Development

1. Clone this repository:
   ```
   git clone https://github.com/Dubby1of1/chatbot.git
   ```

2. Navigate to the project directory:
   ```
   cd ikemba-chatbot
   ```

3. Open `index.html` in your browser to view the chatbot locally.

## Customization

### Updating Responses

The chatbot's knowledge base is located in the JavaScript section of `index.html`. Look for the `ikembaKnowledge` object to modify or expand the responses.

### Visual Customization

The chatbot's appearance can be customized by modifying the CSS variables in the `:root` section:

```css
:root {
    --primary: #006400;
    --secondary: #004d00;
    --light: #e6f5e6;
    --dark: #333;
    --text: #f0f0f0;
    --container-bg: #fff;
    --message-user: #e9e9e9;
    --message-bot: #006400;
}
```

## Contributing

Contributions to improve Ikemba AI are welcome. Please feel free to submit pull requests or open issues to suggest enhancements.
