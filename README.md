🎮 GameReview App - Gamer Binder
Welcome! This is a simple but complete game review application built in Mendix, where users can rate games they've played, leave comments, and store their own reviews.

This project was developed as part of a learning challenge, and it helped me understand several key concepts of low-code development, database logic, and user experience.

✨ What You Can Do
✅ Create a personal list of game reviews

📝 Add a rating (score + stars) and a comment for each game

📅 Save the date you played the game

🔒 Secure access with user roles (Admin and User)

🧾 Display all your reviews in a custom page

🧑‍💼 Admins can manage users and delete reviews when needed

🔧 What I Learned
This project taught me a lot! Some of the things I practiced and understood better:

How to create entities and set associations in a domain model

Use of microflows to process logic and store data

Handling user roles and access restrictions

Filtering and displaying user-specific content

Creating clean and usable interfaces with Atlas UI

Adding a touch of style customization, like rounded corners for images ✨

Structuring the app to meet real-world requirements

🧱 Entities and Structure
The app includes at least 3 main entities:

Game (from external API or created manually)

Review (rating, stars, comment, date)

User (with role-based permissions)

All reviews are associated with a specific user, ensuring personal data is safely stored and displayed only to the owner (unless you're an admin).

🔐 Roles and Permissions
User: can add and view only their own reviews

Admin: has access to an exclusive dashboard to:

Create, update or delete users

Delete any review in the system

🎓 Final Thoughts
This was my first real Mendix project and I’m proud of what I built. I learned how to think like a developer: structure logic, manage data, and deliver a working solution that solves a real problem. Plus, it was really fun to work on something related to games!

Thanks for checking out my project! 😊
