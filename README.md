# Heroku Minecraft WebSocket Tunnel Client

This code was extracted from https://github.com/jacobwgillespie/heroku-minecraft.
Now you can connect to a minecraft server running on heroku without cloning all the heroku-minecraft repo.

## Usage

1. Install

   ```
   npm install hmwtc
   ```

2. Run the proxy service. This will proxy the Minecraft server on Heroku to your local machine. The server will appear to be a Minecraft server running on your local machine.

   ```
   hmwtc my-app-name.herokuapp.com
   ```

3. **Leave the terminal window open** and launch Minecraft. Add a new server with the address `localhost`. Hit connect and play! When you're done playing, close the terminal window.

## Credits

Much of the original Heroku setup by [Jacob Gillespie](https://github.com/jacobwg).

Updates, refactoring, and the WebSockets proxying by [Wil Gieseler](https://github.com/wilg).
