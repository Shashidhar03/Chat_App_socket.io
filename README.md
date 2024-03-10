# Chat_App_socket.io

it is a simple chat application developed with node.js and socket.io javascript library

# SERVER SIDE

->in server side, first socket.io is imported in file and port is assigned to io.
-> user list is maintained to store info about users
->then on io connection,
  socket is created and required socket functions are created with the custom event and their       corresponding handler.
-> these socket functions are called from frontend with socket.emit function

# client side

->io is set to the port
->input msg from form is captured and sent to corresponding socket functions to handle event
->sockets functions of backend are called here with socket.emit functions

