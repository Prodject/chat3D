
## Chat with 3D environment



###INFO

Chat with 3D environment made for UPF's subject *Entorns de comicació virtual (ECV)* with Client & Server side to learn JavaScript/NodeJS and Three.js.

### *NEW FEATURES*

	-A 3D environment has been added to the previous chat with the following features:
		-Every User is represented as a cube which is marked with a red Cone
		-Users can move within the plane with arrow keys or by doing left-clicks with the mouse
		-Users can change the Cube color or the User's name by selecting the edition icon (in the top-left side)
		-Every User can receive a message depending on the distance, if you are too far from another user you cannot receive his message
	-Node Server which handles:
		-Websocket + HTTP server listening to the port 9026
		-Random positions and color for every new user
		-Broadcast of chat messages depending on the distance
	-Skybox
	-Responsive website behaviour
	-Simple Orbital Camera (drag with right-click) + Zoom (scroll or pinch)

### RUN chat on LOCALHOST

On the terminal..
- Install npm and nodeJS.
- Git clone this repository
'git clone https://github.com/pvalls/chat3D'
- Change directory to source
'cd chat3D/source'
- Install dependencies using provided package.json
'npm install'
- Start server
'node ChatServer.js'
- Go to browser and open the url "http://localhost:9026/index.html".


### Authors
	pol.valls02@estudiant.upf.edu
	lie.jin01@estudiant.upf.edu

### Pending to implement
	-2D Label Text for the users' name and messages
	-changing between a fixed camera to first person camera
	-clicking other users cube






