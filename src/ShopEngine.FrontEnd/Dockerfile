# Stage 1: Build the Angular app
FROM node:16-alpine AS build

WORKDIR /app

# Install dependencies
COPY package.json package-lock.json ./
RUN npm install

# Copy the rest of the project files
COPY . .

# Build the Angular app
RUN npm run build --prod

# Stage 2: Serve the Angular app with NGINX
FROM nginx:alpine

# Copy the built app files to the NGINX directory
COPY --from=build /app/dist/<your-angular-project-name> /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
