📝 How This Project Is Different
This project builds on the typical Node.js + MongoDB todo app, but introduces several key differences and improvements:

🔍 Schema Validation with Zod
Unlike many basic implementations, this app uses Zod for input validation, ensuring cleaner, more predictable request handling.

Helps reduce runtime errors by validating request structure at the API level.

🧠 Cleaner Error Handling
Includes specific error messages (e.g., duplicate user detection).

Provides structured feedback using safeParse instead of unstructured or missing validation responses.

📦 Minimal but Extendable Structure
Focuses on a clean and functional base, avoiding unnecessary boilerplate.

Easily extendable for roles, filters, due dates, priorities, etc.

⚙️ Authentication Logic Improvements
JWT is implemented with clear separation of auth logic into its own module (auth.js), promoting better maintainability.

Authenticated routes (/todo, /todos) are protected in a reusable way.

🛠️ Production-Oriented Improvements
Includes recommendations for .env use and .gitignore best practices (not always handled in beginner-level projects).

Uses bcrypt with a salt round for hashed passwords, adhering to security best practices.

