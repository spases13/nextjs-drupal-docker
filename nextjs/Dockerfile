# Use the official Node.js image
FROM node:18

# Set the working directory inside the container
WORKDIR /app

# Install create-next-app globally
RUN npm install -g create-next-app

# Generate the Next.js application
RUN npx create-next-app@latest . --ts --use-npm --no-eslint --no-tailwind

# Expose port 3000 for the Next.js app
EXPOSE 3000

# Start the development server
CMD ["npm", "run", "dev"]