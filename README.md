
# Bookify

The E-Commerce Website for Book Sales is a user-friendly online platform that allows customers to browse, purchase, and manage both physical and eBooks seamlessly. The platform is designed to provide a smooth shopping experience while offering powerful tools for administrators to manage inventory, orders, and user access effectively.


## Demo

**Note**: The website may feel a bit slow as it's using a free PostgreSQL database, which can cause some lag. Additionally, the ebook upload and delete features are disabled since they are managed through AWS S3 to avoid S3 charges i hvae disabled it. The book management features (add, edit, delete) are also disabled to prevent unnecessary changes in demo, but please note that these only disabled but they work just fine 🙃.

Check out the [live demo](https://unknownlemon03.github.io/loading/?data=%7B%22sec_count%22%3A30%2C%22req%22%3A%22https%3A%2F%2Flemon-ebook-recommendation.onrender.com%22%2C%22redirect%22%3A%22https%3A%2F%2Fadorable-mandazi-481025.netlify.app%22%2C%22message%22%3A%22%F0%9F%99%83%20Please%20wait%20til%20project%20is%20loading%20(i'm%20using%20free%20services%20so%20it%20takes%20time)%22%7D) of this project.

## Tech Stack

- **Client:**  
  - Next.js
  - Tailwind CSS
  - TypeScript

- **Server:**  
  - Node.js
  - PostgreSQL
  - TypeScript
  - Zod
  - Prisma

- **Recommendation System:**  
  - Python
  - Flask
  - scikit-learn (cosine_similarity, TF-IDF)
  - Docker

## Features

#### Book Search and Recommendations:
Users can search for books by title. When they view a book, they will receive recommendations for similar books based on its description, making it easier to discover new titles.

### User Dashboard

#### Book Recommendations:
The Book Recommendation System suggests books related to those users are currently viewing, based on the book's description. This system helps users easily discover similar titles and improves browsing engagement.


#### User Sign Up and Sign In:
Users can create an account to sign up and sign in securely to access their personal dashboard and order history.


#### Order Management: 
View past and current orders with their status (e.g., processing, shipped, delivered).

#### eBooks Library: 
Access and read purchased eBooks directly in the browser, making it easy to manage digital reading materials.

#### Address Management: 
Users can save and update their delivery addresses for physical book orders, ensuring a smooth checkout experience.

### Admin Dashboard:

#### Order Management: 
Admins can manage the status of customer orders, such as marking them as shipped or completed.

#### Admin Management: 
Admins can control who has access to the admin dashboard, ensuring only authorized personnel can make changes.

#### eBook Management: 
Admins can upload and manage eBooks, adding new titles or updating existing ones.

#### Book Management: 
Admins can add, edit, or remove physical books from the inventory and track stock levels.

#### Sales Reports: 
Generate detailed reports on book sales, helping track performance over time and plan for future sales strategies.

#### Order Placement and Payment Integration:
Users can purchase either physical books or eBooks through a secure checkout process. The platform integrates with Razorpay to handle payments efficiently and safely.

#### Quantity Management:
For physical books, admins can manage inventory to ensure that stock levels are accurate and updated in real-time. For eBooks, users can instantly download after purchase without worrying about stock.

