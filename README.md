# SSHBinding

ssh [user]@[remoteServer] -f -N -L [localPort]:localhost:[remotePort]

-f Requests ssh to go to background

-N Do not execute a remote command

-L Actually binds the ports
