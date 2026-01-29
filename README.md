# Full-Stack Deployment

Live Link: https://full-stack-deployment-frontend-fxad.onrender.com

## Deploy the Backend to Render

- Now we deploy the server (backend).
- On Render, we:
- Create a Web Service
-Connect it to our GitHub repository
-Choose the server folder
- Add environment variables like:
- Render runs our backend code and gives us a live API URL.

## Deploy the Frontend to Render
- Next, we deploy the React frontend.
- On Render, we:
- Create a Static Site
- Choose the client folder
- Set the build command (npm run build)
- Set the publish directory (build)
- Add the backend API URL as an environment variable
- This allows the frontend to talk to the backend.

## Verify Everything Works
- Finally, we open the frontend URL in the browser.
- We test the app.