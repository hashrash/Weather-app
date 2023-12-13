**Steps to Download and Run the Weather Forecasting Web Application Locally:**

**Prerequisites:**
- Ensure that Docker and Docker Compose are installed on your local machine.

**Step 1: Download the Repository**
```bash
# Clone the repository
git clone https://github.com/hashrash/Weather-app.git
```

**Step 2: Navigate to the Repository Directory**
```bash
cd Weather-app
```

**Step 3: Set Environment Variables**
- Create a file named `.env` in the root directory.
- Open the `.env` file and configure the MongoDB connection details:
  ```env
  MONGO_HOST=test_mongodb
  MONGO_PORT=27017
  MONGO_USER=root
  MONGO_PASSWORD=pass
  ```

**Step 4: Build and Start Docker Containers**
```bash
docker-compose up
```

**Step 5: Access the Application**
- Open a web browser and navigate to [http://localhost:5000](http://localhost:5000)

**Step 6: Register a New User**
- Click on the "Register" link and fill in the required information.
- Ensure that you follow the specified password and email format rules.

**Step 7: Login**
- After registration, click on the "Login" link and enter your registered email and password.

**Step 8: Explore the Application**
- Once logged in, you can explore the Weather Forecasting Web Application.

**Step 9: Logout**
- To logout, click on the "Logout" link.

**Step 10: Stop Docker Containers**
- In the terminal where Docker Compose is running, press `Ctrl + C` to stop the containers.
