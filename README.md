# SharePlay

SharePlay is a music streaming service that allows users to upload and stream music, enjoying their favorite songs anytime, anywhere. The service features recurring monthly subscriptions for uninterrupted access to its extensive music library.

## Features

- **Upload Music**: Users can upload their own music tracks.
- **Stream Music**: Enjoy seamless streaming of your favorite songs.
- **Subscriptions**: Recurring monthly subscriptions for premium access.

## Technology Stack

- **Next.js**: A React framework used for building the user interface of SharePlay.
- **SupaBase**: An open-source Firebase alternative used for the backend database and authentication.
- **Stripe**: A payment processing platform used to handle monthly subscriptions.

## Installation

To set up SharePlay locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/shareplay.git
    cd shareplay
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env.local` file in the root directory and add the following variables:
    ```
    #STRIPE
    STRIPE_WEBHOOK_SECRET=
    STRIPE_SECRET_KEY=
    NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=

    #SUPABASE
    NEXT_PUBLIC_SUPABASE_URL=
    NEXT_PUBLIC_SUPABASE_ANON_KEY=
    SUPABASE_SERVICE_ROLE_KEY=
    ```

4. **Run the development server**:
    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

1. **Sign Up / Log In**: Create an account or log in to your existing account.
2. **Upload Music**: Upload your music tracks to the platform.
3. **Stream Music**: Browse and play music from the library.
4. **Manage Subscription**: Subscribe to a monthly plan for premium access and manage your subscription via Stripe.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork the Project**: Create a copy of this repository on your GitHub account.
2. **Create your Feature Branch**:
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3. **Commit your Changes**:
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4. **Push to the Branch**:
    ```bash
    git push origin feature/AmazingFeature
    ```
5. **Open a Pull Request**: Navigate to the original repository on GitHub and open a pull request to merge your feature branch.

We appreciate your contributions and efforts to improve SharePlay!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
