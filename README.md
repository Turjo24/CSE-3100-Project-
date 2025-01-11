# TrendyTrade

## Team Members

| Student ID  | Name              | Email                                                                | Role                 |
| ----------- | ----------------- | -------------------------------------------------------------------- | -------------------- |
| 20220104031 | Farhan Islam Ifti | [farhangeneralusage@gmail.com](mailto\:farhangeneralusage@gmail.com) | Lead                 |
| 20220104037 | Sharadindu Dutta  | [turjodutta023@gmail.com](mailto\:turjodutta023@gmail.com)           | Back-end + Front-end |
| 20220104038 | Kalvin Chakma     | [kalvinchakma7@gmail.com](mailto\:kalvinchakma7@gmail.com)           | Front-end            |
| 20220104041 | Asaduzzaman Limon | [adilarian420@gmail.com](mailto\:adilarian420@gmail.com)             | Back-end             |

## Objective

TrendyTrade is an innovative trading platform where customers can post items they want to sell or trade. Interested buyers can negotiate prices through comments or direct messaging. For high-value items like cars or motorcycles, TrendyTrade acts as a trusted third-party mediator to ensure secure transactions.

## Target Audience

Individuals looking to sell, trade, or purchase items securely and efficiently. It caters to general users for everyday items and high-value buyers and sellers requiring mediation services.

## Tech Stack

- **Backend:** Laravel (mandatory)
- **Frontend:** React, Next.js
- **Rendering Method:** Client-Side Rendering (CSR)

## UI Design

### Mock UI

The mock user interface for TrendyTrade has been designed using Figma. It includes screens for:

- Posting items for sale or trade
- Browsing items
- Viewing item details
- Negotiating prices through comments or messaging
- Buyer-seller mediation for high-value items

### Figma Design Link

[View Figma Design](https://www.figma.com/design/2JDqlWCyEQUfr7uX3otESA/CSE-3100?node-id=0-1\&p=f\&t=a4PPMHbUfa8xQnZg-0)

## Project Features

1. **User Authentication:**

   - Registration, login, and profile management.

2. **Item Management:**

   - **GET /items:** Fetch all items.
   - **POST /items:** Add a new item for sale or trade.
   - **GET /items/{id}:** Fetch a specific item's details.
   - **PUT /items/{id}:** Update an item.
   - **DELETE /items/{id}:** Delete an item.

3. **Comment and Messaging System:**

   - Post comments on items for price negotiation.
   - Direct messaging for detailed discussions.

4. **Buyer-Seller Mediation:**

   - Third-party involvement for high-value items like cars or motorcycles.
   - Secure handling of payments and item exchanges.

5. **Search and Filter:**

   - Search items by category, price, or location.
   - Filter items based on trending or new listings.

6. **Interactive Features:**

   - Trending items section for enhanced visibility.
   - User engagement metrics such as views, comments, and interest levels.

## Milestones

### **Milestone 1: User Authentication and Profile Management**

- **Backend:**

  - Set up the Laravel backend for handling CRUD operations.
  - Implement user registration, login, and authentication APIs.
  - Create a database schema for users, including profiles and roles.
  - Build APIs for creating, updating, and deleting user profiles.

- **Frontend:**

  - Design and develop a responsive home page.
  - Display user information (e.g., name, profile picture) on the home page.
  - Set up a basic navigation system for the platform.

### **Milestone 2: Item Management and Search Features**

- Develop the item posting form with text, images, and category input.
- Implement the backend logic for saving items to the database.
- Build APIs for fetching, updating, and deleting items.
- Create the item detail page to display item-specific content.
- Add functionality to post comments on items.
- Add advanced search and filtering capabilities:
  - Categories (e.g., Electronics, Vehicles, Furniture).
  - Price range filters.
  - Location-based search.
- Build APIs to handle filter queries from the frontend.
- Design and develop a filtering UI with dropdowns, sliders, and checkboxes.
- Include pagination for filtered results to enhance performance.

### **Milestone 3: Mediation and Messaging Features**

- Develop the messaging system for buyer-seller communication.
- Add a secure payment gateway for high-value item transactions.
- Build a mediation system where TrendyTrade facilitates transactions between buyers and sellers.
- Create APIs for managing mediation processes.
- Design an admin panel for overseeing and resolving disputes.

