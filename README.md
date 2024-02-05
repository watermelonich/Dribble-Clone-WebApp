# Dribble Clone WebApp

A Dribble Clone WebApp UI Template made with NextJS 13

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/watermelonich/Dribble-Clone-WebApp.git
cd project_nextjs13_flexibble
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
NEXTAUTH_URL=
NEXTAUTH_SECRET=
CLOUDINARY_NAME=
CLOUDINARY_KEY=
CLOUDINARY_SECRET=
GRAFBASE_API_URL=
GRAFBASE_API_KEY=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the corresponding websites from [Google Cloud](https://console.cloud.google.com), [Cloudinary](https://cloudinary.com/), and [Grafbase](https://grafbase.com/).

For the Next Auth secret, you can generate any random secret using [crytool](https://www.cryptool.org/en/cto/openssl).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.