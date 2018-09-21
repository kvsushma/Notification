Broadcasting a piece of HTML code to a channel from the Rails console usig Action Cabel.

Ruby ~ 2.3.3
Rails ~ 5.2.1 

Steps:
1. Run Redis server on your system 
2. Start the rails server
3. In console you can broadcast a message to the web_notifications_channel using command: 
   ActionCable.server.broadcast 'web_notifications_channel', message: 'Hello World!'
