# Collaborative Live Editor

This project is a collaborative live editor built using modern web technologies. It allows multiple users to edit documents in real-time, providing a seamless and interactive experience.

## Features

- Real-time collaboration
- User authentication and management
- Mention suggestions
- Loading indicators
- Error handling

## Technologies Used

- React
- Next.js
- Clerk for user authentication
- Liveblocks for real-time collaboration
- TypeScript

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses `next/font` to automatically optimize and load Geist, a new font family for Vercel.

## Environment Variables

Create a `.env.local` file in the root directory and add the following variables:

```env
NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
CLERK_API_KEY=<your-clerk-api-key>
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=<your-liveblocks-public-key>
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [Next.js GitHub Repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Folder Structure

```
components/    # Reusable React components
lib/          # Utility functions and API calls
pages/        # Next.js pages
styles/       # CSS and styling files
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Clerk](https://clerk.dev/) for user authentication
- [Liveblocks](https://liveblocks.io/) for real-time collaboration

## Contact

For any questions or feedback, please open an issue on the GitHub repository.
