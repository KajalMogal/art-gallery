# Art Gallery

Art Gallery a fullstack express app, where user can add painting and other users can see and comment on it. Hashing is used to store users password in database.

![art](https://github.com/user-attachments/assets/6130730d-92f7-4738-9a55-96298a0572ba)


## Tech Stack
- `Node.js` : Javascript runtime for building the app server.
- `Express.js` : Web framework for building RESTFul APIs.
- `MongoDB` : Database to store user data.
- `EJS` : Templating engine for rendering dynamic HTML views.
- `bcrypt` : Hashing and securing user password.
- `CSS` : Styling the application frontend.
  

  ## Features
- Authentication : User can register, login, logout.
- Hashing : Passwords are hashed before storing in database.
- Dynamic views : Views are rendered dynamically using EJS templates.
- Responsive design : Basic frontend layout styled with css.

  
  ## Installation
1. Clone the repository to your local machine:
   ```bash
      git clone https://github.com/KajalMogal/art-gallery.git
   ```

2. Install dependencies using npm:
   ```bash
      npm install
   ```

3. Create a .env file in the root directory of the project to store environment variables.
   ```bash
      MONGODB_URI=mongodb://localhost:27017/app
      SECRET_KEY=secret-key
      CLOUDINARY_CLOUD_NAME=cloud-name
      CLOUDINARY_KEY=cloudinary-key
      CLOUDINARY_SECRET=cloudinary-secret
   ```

4. Start the app:
   ```bash
      npm start
   ```
