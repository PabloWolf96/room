# Room - Zoom Clone

Room is a video conferencing application built with Next.js, leveraging Clerk for authentication, shadcn/ui for the user interface, and GetStream for real-time communication features.

## Features

- Real-time video conferencing
- User authentication and management
- Modern and responsive UI
- Screen sharing
- Chat functionality
- Room creation and joining

## Technologies Used

- [Next.js](https://nextjs.org/) - React framework for building the application
- [Clerk](https://clerk.dev/) - User authentication and management
- [shadcn/ui](https://ui.shadcn.com/) - UI component library
- [GetStream](https://getstream.io/) - Real-time video and chat functionality

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or later)
- npm or yarn

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/pablowolf96/room.git
   cd room
   ```

2. Install dependencies:

   ```
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the following variables:

   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_STREAM_API_KEY=your_getstream_api_key
   STREAM_SECRET_KEY=your_getstream_api_secret
   ```

4. Run the development server:

   ```
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Usage

1. Sign up or log in using the authentication provided by Clerk.
2. Create a new room or join an existing one using the provided room code.
3. Start your video conference and enjoy features like screen sharing and chat.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
