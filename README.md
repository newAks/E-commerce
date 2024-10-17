# E-commerce
Developing E-commerce website for learning purpose


1. FastAPI (Backend Framework)
Usage: FastAPI is a modern Python framework used for building APIs quickly with automatic validation and serialization. In an e-commerce website, it can handle server-side operations like user authentication, product management, shopping cart management, and order processing.
Key Responsibilities:
User authentication (JWT tokens, OAuth)
Product and category APIs (CRUD operations)
Cart management and order processing logic
Handling payments (integration with services like Stripe or PayPal)
API documentation (FastAPI generates it automatically)

3. React (Frontend Framework)
Usage: React is a JavaScript library for building interactive user interfaces. For an e-commerce website, it can manage the frontend, providing users with a responsive experience for browsing products, managing carts, and completing orders.
Key Responsibilities:
Displaying product catalogs with filters and sorting options
Implementing shopping cart and wishlist functionality
User registration, login, and profile management
Checkout flow, including payment integration
State management (using Redux or React Context for handling user sessions, carts, etc.)

5. MongoDB (Database)
Usage: MongoDB is a NoSQL database used to store structured and unstructured data. In an e-commerce app, MongoDB can store user information, product details, order history, and more.
Key Responsibilities:
Storing product catalogs, including categories, brands, and availability
User information (credentials, addresses, payment details)
Storing cart data and orders, including product details, prices, and status
Payment transaction records

7. NGINX (Web Server)
Usage: NGINX is commonly used as a reverse proxy to serve the FastAPI backend and React frontend. It can also handle load balancing and improve performance by serving static files efficiently.
Key Responsibilities:
Serve React static files
Reverse proxy API calls to the FastAPI backend
SSL/TLS termination for secure transactions
FARM Stack Workflow in an E-commerce Website:
Frontend: React serves the user interface, allowing users to browse products, manage carts, and complete orders.
API: FastAPI handles the backend logic, exposing endpoints for managing users, products, and orders.
Database: MongoDB stores product data, user profiles, cart items, and orders.
Web Server: NGINX serves both the frontend (React) and the backend (FastAPI) to the user’s browser.




TASK ORDER:
1. Research how E-commerce website work and what are required pieces for it.
2. Research how to make these pieces.
