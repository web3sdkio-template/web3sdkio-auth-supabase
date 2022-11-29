## Getting Started


This example demonstrates how to use web3sdkio Auth with Supabase.

Before running the project, you'll need to seutp and configure Supabase [as specified here](https://portal.web3sdk.io/auth/integrations/supabase).

To run the project, first clone this repository, and then run one of the following commands to install the dependencies:

```bash
npm install
# or
yarn install
```

Next, you need to create a `.env.local` file and add the `ADMIN_PRIVATE_KEY` variable to it with the private key of the wallet you want to use as the admin wallet to generate and verify payloads. Your file should use something like the following:

```.env
ADMIN_PRIVATE_KEY=...
```

Finally, you can run the project with one of the following commands:

```bash
npm run dev
# or
yarn dev
```

Now, you can navigate to [http://localhost:3000](http://localhost:3000) to visit the client side page where you can connect a wallet, sign-in with ethereum and view the payload, and use the payload to authenticate with the backend.
## Learn More

To learn more about web3sdkio, take a look at the following resources:

- [web3sdkio Auth Documentation](https://docs.web3sdk.io/auth) - learn about web3sdkio Auth.
- [web3sdkio React Documentation](https://docs.web3sdk.io/react) - learn about our React SDK.
- [web3sdkio Portal](https://docs.web3sdk.io) - check our guides and development resources.

You can check out [the web3sdkio GitHub organization](https://github.com/web3sdkio) - your feedback and contributions are welcome!

## Join our Discord!

For any questions, suggestions, join our discord at [https://discord.gg/web3sdkio](https://discord.gg/web3sdkio).
