# ☕ Get Me a Chai - Creator Crowdfunding Platform

```

A patronage platform where fans support creators by funding their creative projects - the digital equivalent of "buying them a chai" 🫖

> "Support the creators you love, one chai at a time"
```

## 🌟 Why Get Me a Chai?
- **Direct Creator Support**: Fans contribute directly to creators' projects
- **Chai-as-Currency**: Symbolic "chai" purchases fund creative work
- **Milestone Funding**: Creators set funding goals for specific projects
- **Fan Engagement**: Exclusive content for supporters
- **Transparent Tracking**: See exactly where your "chai money" goes

## 🚀 Live Demo
Experience the platform: [https://getmeachai.app](https://getmeachai.app) (demo link)


## 🛠️ Tech Stack
- **Frontend**: React + Vite, Redux Toolkit, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Payments**: Stripe Integration
- **Auth**: JWT Authentication

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- MongoDB Atlas cluster
- Stripe account

### Installation
1. Clone the repository:
```bash
git clone https://github.com/rajputjayveer/get_me_a_chai.git
cd get_me_a_chai
```

2. Install dependencies for both frontend and backend:
```bash
cd client && npm install
cd ../server && npm install
```

3. Setup environment variables:
```env
# .env in server/
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

4. Run both frontend and backend:
```bash
# In server/ directory
npm run dev

# In client/ directory
npm run dev
```

## 📂 Project Structure
```
├── client/              # Frontend application
│   ├── public/          
│   ├── src/
│   │   ├── components/  # React components
│   │   ├── pages/       # Route pages
│   │   ├── store/       # Redux configuration
│   │   └── utils/       # Helper functions
│
├── server/              # Backend application
│   ├── config/          # Configuration files
│   ├── controllers/     # Route controllers
│   ├── models/          # MongoDB models
│   ├── routes/          # API endpoints
│   └── middleware/      # Authentication middleware
```

## 🌐 Key Features
- **Creator Profiles**: Showcase portfolios and ongoing projects
- **Chai Funding**: Fans purchase "virtual chai" packages ($5/$10/$20)
- **Project Milestones**: Creators set funding targets with deliverables
- **Supporter Rewards**: Exclusive content for different funding tiers
- **Real-time Analytics**: Track funding progress on creator dashboard
- **Secure Transactions**: PCI-compliant payment processing

---

> "More than just funding - it's about building a community around creativity"  
> Join us in revolutionizing creator support!


