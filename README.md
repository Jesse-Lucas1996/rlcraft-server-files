## How to run RLCraft Minecraft Server on a Linux Machine

### Prerequisites

1. Java: RLCraft server runs on Java, so you need to have it installed on your machine. You can check if Java is installed by running `java -version` in your terminal. If it's not installed, you can install it by running `sudo apt install openjdk-11-jdk`.

### Steps to Run the Server

1. Navigate to the directory where you extracted the RLCraft Server pack using the `cd` command.

2. Unzip the RLCraft Server pack by running `unzip 'RLCraft Server Pack 1.12.2 - Release v2.9.3.zip'`.

3. After unzipping get the forge-1.12.2-14.23.5.2860-installer.jar put in the same directory as the unzipped files

4. run java -jar forge-1.12.2-14.23.5.2860-installer.jar --installServer

5. After running you will see a `forge-1.12.2-14.23.5.2860.jar` run java -jar forge-1.12.2-14.23.5.2860.jar

6. Open `eula.txt` with a text editor (e.g., `nano eula.txt`) and change `eula=false` to `eula=true` to agree to the Minecraft EULA.

7. Now you can enjoy playing (and dying) in RLCraft with your friends!

### Troubleshooting

If you encounter any issues while running the server, check the `logs` directory in the server folder. The latest.log file will contain detailed information about any errors or issues.

### Stopping the Server

To stop the server, type `stop` in the server console and press enter. This will save the world and stop the server safely.

**Note:** Running a Minecraft server can consume a lot of resources. Make sure your machine meets the recommended requirements for running a RLCraft server.
