# PaggoCase

Instructions for setting up and running locally the solution:

1. Install the dependencies 
* in the project's root
  npm install
* in the backend folder
  cd backend
  npm install
  npx prisma generate // carregar o banco de dados
* in the frontend folder
  cd ../frontend
  npm install

2. Create a file called .env on \backend\.env (I would put the file into git, but since Im going to set into public, I preffer tell you this)

DATABASE_URL="file:./dev.db"
JWT_SECRET="Your_JWT_Secret"
HUGGING_FACE_API_KEY="Your_HUGGING_FACE_API_KEY"

3. Run
  npm run start:all

4. Access application
  http://localhost:3000 or 127.0.0.1:3000

Obs: I develop all the aplication in portuguese because when I was talking with the HR person I was speaking my language, but when I was reading the case I intended to put a "select language" at the end. But I got some troubles with the Language model (as you can see :[ ) and I did'nt want to take too much time making you wait my response.
Anyway, thanks for the Case.

Vinícius Barreto.