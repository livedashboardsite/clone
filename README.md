# Instagram Clone

A full-stack Instagram clone with real authentication, a live feed, and social
features — built with React, Firebase, and Chakra UI.

**Submitted for:** CodeSprint AI Bootcamp — *"Create Your Own Instagram App with AI"*
(Vedam, 18th July 2026, hosted by Gunjan Madaan, SDE @ Microsoft)

**Live demo:** https://clone-two-dusky.vercel.app

---

## Features

- Email/password and Google authentication
- Post creation with image upload
- Real-time feed with likes and comments
- Follow / unfollow system
- Editable user profiles with avatar upload
- User search
- Notifications and suggested-users panel

## Tech Stack

- **Frontend:** React (Vite), Chakra UI, Framer Motion
- **State management:** Zustand
- **Routing:** React Router
- **Backend:** Firebase (Authentication, Firestore, Storage)

## Getting Started

```bash
git clone https://github.com/livedashboardsite/clone.git
cd clone
npm install
```

Create a `.env` file in the project root with your own Firebase config
(never commit this file):

```
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
VITE_FIREBASE_MEASUREMENT_ID=
```

Then run the dev server:

```bash
npm run dev
```

## Project Structure

```
src/
  components/   # AuthForm, FeedPosts, Profile, Sidebar, SuggestedUsers, Modals
  hooks/        # Firebase-backed hooks (auth, posts, likes, comments, follow, search)
  pages/        # AuthPage, HomePage, ProfilePage
  store/        # Zustand stores (auth, posts, user profile)
  firebase/     # Firebase app config and initialization
```

## License

MIT
