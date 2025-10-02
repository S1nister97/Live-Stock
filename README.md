# Real-Time Stock Market App with Alerts

A full-stack real-time stock tracking application. Users can browse stock data, set personalized alerts, view historical charts, read daily market digests, and manage a watchlist. Built with Next.js, Better Auth, and Inngest.

## 🚀 Features

- Secure email/password authentication & session management  
- Real-time stock price updates and streaming dashboard  
- Interactive charts and historical data visualization  
- Watchlist: Add / remove stocks to monitor  
- Custom alert thresholds (price changes, etc.)  
- Automated daily news digest & market summary emails  
- Deployment-ready (production setup, environment configs)  

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend & framework | Next.js (React) |
| Authentication | Better Auth |
| Background jobs / workflows | Inngest |
| Stock / Market API | (e.g. Finnhub, etc.) |
| Database | (e.g. MongoDB or preferred DB) |
| Email / Notification | SMTP / third-party email provider |
| Deployment | (Vercel / AWS / other platform) |

## 📦 Getting Started

### Prerequisites

- Node.js (v16+ recommended)  
- npm or yarn  
- A database (e.g. MongoDB)  
- Stock API key (e.g. from Finnhub or another provider)  
- SMTP / email credentials  
- Environment variables

### Installation

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
npm install
