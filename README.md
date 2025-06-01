# GameHaven API

## Project Structure

```bash
gamehaven-api/
├── models/
├── controllers/
├── services/
├── routes/
├── middleware/
├── uploads/
├── app.js
├── .env
├── .gitignore
├── README.md
```

##  Features

- User Registration & Login (JWT + bcrypt)
- Role-based Authorization (Admin/User)
- CRUD for Games, Cart, Orders
- File Upload (Multer)
- Input Validation (express-validator)

##  Technologies

- Node.js + Express
- MongoDB + Mongoose
- JWT + bcryptjs
- Multer
- express-validator
- dotenv + morgan

##  Getting Started

```bash
git clone https://github.com/Abdelrhman1020/GameHavenAPI-Project.git
cd gamehaven-api
npm install
```

### Create `.env` file with:

```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/gamehaven
JWT_SECRET=supersecretkey123
```

### Run the app:

```bash
node app.js
```

##  Team Members

- **Abdelrhman Ali Abozaid** (Team Leader) – Project Structure, User Authentication
- **Basant Elsaey** – Game Module
- **Mohamed Abdelkader** – Cart Module
- **Mohamed Shawky** – Order Module

##  To Do

- [ ] Setup MVC + Service structure
- [ ] User Registration & Login (with validation)
- [ ] Game CRUD
- [ ] Cart logic
- [ ] Order processing
- [ ] Admin role + restrictions
- [ ] Deployment & Documentation

