# Bifrost

> [!IMPORTANT]  
> The project is currently under development.

Bifrost is a WebRTC-based P2P file sharing tool.

## How to set up?

* Fork and clone the repository.
* Run the `make build` command.
* Run the binary created at `/bin/bifrost`


## How to use?

> [!NOTE]  
> This will be updated once we add support file transfer.

* Run the `./bin/bifrost send <...files>` and `./bin/bifrost receive` commands in seperate terminals.
* Copy the SDP key generated by the `send` command as user input for `receive` command.
* Copy the SDP key generated by `receive` command as user input for `send` command.
* Review and agree for file transfer on the receiver side.