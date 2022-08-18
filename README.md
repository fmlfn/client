# CClient

Fixes TLS and stuff. Uses the yawning utls fork instead of the original refraction-networking one.


# Notes

If you experience any issues with the gitlab.com/yawning/utls import during installation, please try: `go get gitlab.com/yawning/utls`. Some path issue with go and gitlab ¯\\\_(ツ)\_/¯

The go.mod issue with git etc. was fixed by using my fork of the project with a change to the go.mod file instead of yawning's fork
