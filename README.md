# Vince Analytics Railway Template

This template allows you to deploy Vince Analytics on Railway with minimal configuration.

## Deployment Steps

1. **Deploy on Railway**  
   Click the button below to deploy:

   [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?repositoryUrl=https://github.com/gillkyle/vince-analytics-template)

2. **Configure Environment Variables**  
   After deploying, set the following environment variables in the Railway dashboard:

   - `VINCE_ADMIN_NAME`: The admin username for Vince Analytics.
   - `VINCE_ADMIN_PASSWORD`: The admin password for Vince Analytics.

3. **Access the Vince Analytics Dashboard**  
   Once the deployment is complete, visit the Railway-generated domain or your custom domain to access Vince Analytics.

4. **Login**  
   Use the credentials you configured in the environment variables to log in.

---

## Notes

- Ensure your `DOMAINS` variable matches the actual domain where Vince Analytics will run. This is critical for proper functionality.
- Railway automatically manages container restarts and scaling.

For further information about Vince Analytics, visit the [official website](https://vinceanalytics.com).
