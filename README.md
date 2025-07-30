# n8n on Render (Docker)

This project deploys n8n on Render using Docker and Railway PostgreSQL.

## Steps

1. Push this folder to a GitHub repo
2. Go to [Render.com](https://render.com) > New Web Service
3. Select your repo and make sure "Docker" is detected
4. Confirm the environment variables are auto-filled
5. Deploy

Webhook URLs should now look like:

    https://n8n.onrender.com/webhook/your-workflow-id
