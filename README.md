# Carbon Relay

Carbon Relay is an application built using the following tech stacks:

## Tech Stacks

- **Frontend**: Next.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **API Testing**: Postman
- **Hosting**: Vercel, GoDaddy

## Components

- **Status**
- **Project ID**
- **Project Name**
- **Vintage**
- **Offer**
- **Bid**
- **Share**

## Flow

### User Registration and Authentication

- Users can register an account with the application using their email and password.
- Implement authentication mechanisms such as JWT (JSON Web Tokens) to secure the application and protect user data.
- Users can log in to access their personalized dashboard.

### Dashboard Overview

- Upon logging in, users are presented with an overview of their dashboard.
- The dashboard displays relevant information such as the user's current status, active bids, and claimed offers.

### Status Editing by Companies

- Companies with appropriate permissions can edit the status of a project.
- Implement an interface that allows companies to select a project and update its status (e.g., "In Progress," "Completed," "On Hold").

### Bidding by Individuals

- Individuals can create bids for projects listed by companies.
- Provide a form where individuals can enter details about their bid, such as the amount of carbon they are willing to offer.
- Validate the bid data on the frontend and backend to ensure its correctness.

### Offer Listing and Claiming

- Companies can view the list of bids submitted by individuals for their projects.
- Display the bid details, including the offered amount of carbon.
- Companies can choose to accept a bid and generate an offer for the individual.
- Individuals can view the offers made by companies and claim the ones they wish to accept.

### Carbon Bidding and Transactions

- Implement a mechanism for individuals to bid and offer carbon units.
- Users can specify the amount of carbon they want to bid or offer within the application.
- Implement transactional logic to handle the transfer of carbon units between users when bids are accepted and offers are claimed.

### Static Status and Project ID

- You mentioned that the status and project ID will be static.
- Consider storing this information in your backend database or a separate configuration file.
- Retrieve the static status and project ID when needed to display or update them in the frontend.

### Social Media Sharing

- Allow users to share their project statuses, bids, and offers on social media platforms to reach a wider audience.
- Implement social media sharing buttons or links within your dashboard interface.
- When a user clicks on a social media share button, generate a pre-populated message or post that includes relevant details about the project status, bid, or offer.
- Integrate with social media APIs (e.g., Facebook Graph API, Twitter API) to enable users to post directly from your application.
- Handle the authentication and authorization process with the respective social media platforms to ensure the user has the necessary permissions to post on their behalf.

## Links

- [GitHub](https://github.com/Block-Developers/Carbon-Relay)
