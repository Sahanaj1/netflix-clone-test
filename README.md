

## Details

This project contains APIs built using Next.js for managing user accounts, favorites, authentication(google oauth), and fetching movies and tv shows data from external services- The Movie Database (TMDb) Api.

## APIs

### Account-related APIs

#### Create Account
- **Description**: Create a new user account.
- **Endpoint**: `POST /api/account/create-account/`

#### Get All Accounts
- **Description**: Retrieve all accounts associated with a specific user ID.
- **Endpoint**: `GET /api/account/get-all-accounts`

#### Login to Account
- **Description**: Handle user login authentication based on account credentials.
- **Endpoint**: `POST /api/account/login-to-account`

#### Remove Account
- **Description**: Delete a user account based on the provided account ID.
- **Endpoint**: `DELETE /api/account/remove-account`

### MyFavorites-related APIs

#### Add Favorite
- **Description**: Add a favorite item to a user's list.
- **Endpoint**: `POST /api/favorites/add-favorite`

#### Get All Favorites
- **Description**: Retrieve all favorites associated with a specific user and account ID.
- **Endpoint**: `GET /api/favorites/get-all-favorites`

#### Remove Favorite
- **Description**: Remove a specific favorite item from a user's list based on its ID.
- **Endpoint**: `DELETE /api/favorites/remove-favorite`

### Authentication

#### NextAuth
- **Description**: Handle authentication using NextAuth with Google as the authentication provider.
- **Endpoint**: `api/auth`

### Media-related APIs

#### Media Functions
- **Description**: Provide functions to fetch media data (movies, TV shows) from The Movie Database (TMDb) API.
- **File**: `utils/index.js`

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
