# mirror-test

Demonstrates that commits to a gitlab repository can be mirrored to github.
<p>
The gitlab public key should be temporarily added to github authorized users,
github added as a remote, and a gitlab post-receive server hook checking the 
last revision for a branch merge and pushes it to a github remote should be added.
<p>
If you are seeing this text in github, it is possible!
</p>