# Auto deploy db's to VPS with GH actions

Instructions

  1. Fork the repository
  2. Clone the repository in your VPS (in the root directory)
  3. Set the secrets in github (VPS_PUBLIC_IP_ADDRESS, VPS_PASSWORD, MONGO_PASSWORD, MONGO_USERNAME, REDIS_PASSWORD)
  4. Run the deploy.yml workflow
