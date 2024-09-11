# Fintech Bank Application

## ⚙️ Tech Stack

- **Next.js**
- **TypeScript**
- **Appwrite**
- **Plaid**
- **Dwolla**
- **React Hook Form**
- **Zod**
- **TailwindCSS**
- **Chart.js**
- **ShadCN**

## 🔋 Features

👉 **Authentication**: Ultra-secure SSR authentication with proper validations and authorization.

👉 **Connect Banks**: Integrates with Plaid for multiple bank account linking.

👉 **Home Page**: Displays a general overview of the user account, including total balance from all connected banks, recent transactions, and money spent on different categories.

👉 **My Banks**: Provides a complete list of all connected banks along with respective balances and account details.

👉 **Transaction History**: Includes pagination and filtering options for viewing transaction history from different banks.

👉 **Real-time Updates**: Automatically reflects changes across all relevant pages upon connecting new bank accounts.

👉 **Funds Transfer**: Allows users to transfer funds using Dwolla to other accounts, with required fields and recipient bank ID.

👉 **Responsiveness**: Ensures seamless adaptation to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.

And many more, including code architecture and reusability.

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure that the following tools are installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/adrianhajdin/banking.git
cd banking
```

### Installation

Install the project dependencies using npm:

```bash
npm install
```

### Set Up Environment Variables

1. Create a new file named `.env` in the root of your project.
2. Add the following content to the file:

```env
#NEXT
NEXT_PUBLIC_SITE_URL=

#APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

#PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

#DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox
```

Replace the placeholder values with your actual account credentials. You can obtain these credentials by signing up on [Appwrite](https://appwrite.io/), [Plaid](https://plaid.com/), and [Dwolla](https://www.dwolla.com/).

### Running the Project

Run the project with the following command:

```bash
npm run dev
```

Once the server is running, open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

--- 
