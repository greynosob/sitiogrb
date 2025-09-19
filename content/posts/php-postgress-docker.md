---
title: PHP + Postgress + Node + Docker'
description: I completed a project requiring the development of a PHP-based REST API with a Node frontend and PostgreSQL database, utilizing AI assistance and Docker for efficiency, demonstrating that general concept understanding outweighs language-specific experience.

date: 2025-06-13 15:01:35 +0300
image: ''
image_caption: ''
tags: [php, Node, Postgress, IA, Docker]
---
# 💻 *"PHP + Postgress + Node + Docker"* ⌨️
On this project I created a website with a REST API using PHP for the backend and Node for the frontend 🖥️, connected to a PostgreSQL database. Everything had to be containerized with Docker and configured in a single YAML file.

I must say that the last time I used PHP was in college, and that was over 10 years ago 😅. I had never used PostgreSQL before, but at least I was familiar with Node. As for Docker, I think I had used it a couple of times out of curiosity.

So, I decided to use AI and asked for an action plan based on the requirements given to me 🤖. I was able to set up the project on day 1, ready for PHP and the server with Docker for PostgreSQL, as well as the tools for Node.

**Step 1**: First, I created the database, which consisted of two very simple tables. The interesting part here was getting Docker to execute the table creation script when the server started 🚀.

**Step 2**: Designing the API. I used Composer to generate the backend project so I could focus on the logic. I proceeded to establish a connection with the database using the .env file, and then went on to create the API controllers and routes.

**Step 3**: Frontend. Here, I used AI to generate the pages with the given design and ensure they communicated with the API 🎨.

**Step 4**: Containerizing. This was perhaps the most challenging part as I encountered issues with the API path that used an env file which was overwriting the Docker Compose settings. Thankfully, my old friend Stack Overflow helped me solve this issue 🐳.

**Step 5**: Testing. We conducted tests for initial installation, data loading (as the data is loaded via a JSON file), and deployment 🧪.

With this, the project requirements were fulfilled. What remains on my end is to learn more about implementing security features 🔐.

This project helped me realize that having experience in a specific language isn't as crucial as understanding the general concepts. Using AI definitely helped reduce the time needed for initial research and configuration in a significant way 👍.

It took me three afternoons to achieve the minimum required functionality. I had a great time and learned a lot from this small program! 🎉
