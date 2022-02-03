# How to get server up and running?

To get the server running you should first run `sbt assembly`. This will create the `Scalatron.jar` file which will run the server.

```
sbt assembly (package?)
```

Then copy Scalatron folder into user folder. On Mac: `/Users/<user>` On Linux: `/home/<user>`.

├── bin
├── doc
├── License.txt
├── Readme.txt
├── samples
├── src
├── target
├── test
├── users
└── webui

Can give cmds to the `Scalatron.jar` file

Can potentially give web dir UI.

Bin is at the same level as webui directory.

Step after assembly that copies it.

Make sbt cmd, setup, that would setup the server correctly.
