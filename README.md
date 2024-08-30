## Technologies Used

- **Frontend:** Next.js, TypeScript, Tailwind CSS
- **Backend:** Spring Boot
- **Database:** MSSQL
- **Cloud Platform:** Azure

## Live Demo

You can view the live demo of the application at: [https://witty-island-008b1ea0f.5.azurestaticapps.net/](https://witty-island-008b1ea0f.5.azurestaticapps.net/)

## Local Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (v17 or higher)
- [Maven](https://maven.apache.org/) (v3.6.0 or higher)

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository.git
   ```

2. Navigate to the `frontend` directory:
   ```bash
   cd your-repository/frontend
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `.env.local` file in the `frontend` directory with the following content:
   ```env
   NEXT_PUBLIC_API_BASE_URL=http://localhost:8080
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:3000`.

### Backend Setup

1. Navigate to the `backend` directory:
   ```bash
   cd your-repository/backend
   ```

2. Install the dependencies and build the project:
   ```bash
   mvn clean install
   ```

3. Set up the database:
   - Create an MSSQL database and configure it according to the `application.properties` or `application.yml` file in the `backend/src/main/resources` directory.

4. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

   The backend will be available at `http://localhost:8080`.
