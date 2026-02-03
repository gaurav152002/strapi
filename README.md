# ============================================================
# STRAPI LOCAL SETUP – GENERAL (INTERNSHIP TASK)
# ============================================================

# Clone the Strapi repository (framework reference)
git clone https://github.com/strapi/strapi

# Create a new Strapi application using the official CLI
npx create-strapi@latest

# During setup, choose:
# - Default database (SQLite)
# - TypeScript
# - Example data
# - npm for dependencies
# - Initialize Git repository

# Navigate into the created Strapi app
cd <strapi-app-directory>

# Run Strapi in development mode
npm run develop

# Open Admin Panel in browser
# http://localhost:1337/admin

# Admin Panel actions:
# - Create administrator account
# - Create Collection Type: Article
#   - title (Text)
#   - description (Rich Text)
#   - publishedDate (Date)
# - Create and publish a sample Article entry

# Stop the Strapi server
# Press CTRL + C

# Commit and push changes
git add .
git commit -m "Set up Strapi locally and create Article content type"
git push
