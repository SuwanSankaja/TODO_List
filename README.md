# To-Do List Application

## 🚀 Overview
The **To-Do List Application** is a full-stack project that allows users to manage tasks seamlessly. With a sleek interface powered by React and a robust backend built using Go and MongoDB, this application ensures a smooth and efficient task management experience.

## ✨ Features
- **Add, Update, and Delete Tasks**: Manage your to-do list with ease.
- **Mark Tasks as Completed**: Track progress with a single click.
- **Real-Time Updates**: Changes are instantly reflected.
- **Responsive Design**: Optimized for desktops and mobile devices.

## 🛠 Tech Stack
### Frontend
- **React**
- **TypeScript**
- **Chakra UI**

### Backend
- **Go** (Golang)
  - Fiber Framework
- **MongoDB**

## 📂 Project Structure
```
To-Do_List/
├── main.go          # Backend entry point
├── go.mod           # Go module configuration
├── client/          # Frontend code
│   ├── src/         # React source files
│   ├── public/      # Public assets
│   ├── package.json # Frontend dependencies
```

## ⚙️ Installation and Setup
### Prerequisites
- **Node.js** and **npm** (for frontend)
- **Go** (for backend)
- **MongoDB**

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/SuwanSankaja/To-Do_List.git
   cd To-Do_List
   ```

2. **Setup Backend:**
   ```bash
   cd To-Do_List-main
   go mod tidy
   go run main.go / air
   ```

3. **Setup Frontend:**
   ```bash
   cd client
   npm install
   npm run dev
   ```

4. **Environment Variables:**
   Create a `.env` file in the root directory:
   ```env
   MONGODB_URI=Mongo_URI
   PORT=5000
   ```

5. **Run the Application:**
   Access the application at [http://localhost:3000](http://localhost:3000).


