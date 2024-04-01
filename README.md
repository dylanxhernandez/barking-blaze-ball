# Barking Blaze Ball

Barking Blaze Ball is a sample HTML5 game created from an old tutorial. It features a running dog that can transform into a flaming ball.

The purpose of this project was to explore standard HTML5 functionality for game design without relying on any special frameworks or plugins. This project was conducted solely for experimental purposes.

The objective of the game is to achieve a winning score of more than 30 points before the timer runs out. Points are earned by colliding with enemies while in a fireball state. However, if an enemy collides with the character, a life is lost. If the character loses 5 lives, it results in a game over. Refreshing the page will initiate a new gaming session.

## Controls
- `Up Arrow Key`: Character Jumps
- `Down Arrow Key`: Character crouches and stops moving
- `Right Arrow Key`: Character moves to the right. If the character is stationary, they will start running.
- `Left Arrow Key`: Character moves to the left. Note that the character will continue moving.
- `Enter`: Character transforms into a fireball, increasing speed.
- `F5`: Browser refresh, initiating a new session.

## Play a Demo Online
You can experience the game through the following demo link [here](https://barking-blaze-ball.netlify.app/).

## Play Locally

### Play Directly in Your Browser
The game runs on static HTML5. If desired, you can simply open the `index.html` file in your preferred browser, and the game will run.

### Play Using Docker
If you prefer to launch the game from a VM/Server, you can utilize the Docker Compose service to generate a container running NGINX on Port 80.

This option requires Docker and Docker Compose to already be installed on your machine. You can start the container and retrieve the hostname it will run on by executing the following command:
```
docker compose up -d && hostname -I
```
Copy the hostname or IP address and paste it into your browser. The game will run as if it were on your local machine. To stop the service, simply run:
```
docker compose down 
```
