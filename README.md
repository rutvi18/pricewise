The project involves tracking the prices of product from amazon periodically and alerting the same on given emails.

## Tech Stack
- React 
- Next.js
- Node.js
- Cron-job for scheduling tracking
- BrightData for web scraping
- MongoDb for database management
- Vercel for deployment

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Output
<img width="1440" alt="Screenshot 2024-07-14 at 12 11 23 AM" src="https://github.com/user-attachments/assets/c6ccd487-1d8c-474c-b143-f82e9808b6e6">

The Home page where the link can be copied and pasted to search for the product and track its price changes.

<img width="1440" alt="Screenshot 2024-07-14 at 12 14 19 AM" src="https://github.com/user-attachments/assets/b2c97410-51da-4379-8cc5-41f69a13960f">

The user's search history

<img width="1438" alt="Screenshot 2024-07-14 at 12 16 00 AM" src="https://github.com/user-attachments/assets/a703042e-2b48-4389-aca7-4b3a3f4053c1">

The product's price history with options to send updated to an email for tracking


