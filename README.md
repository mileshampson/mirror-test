# mirror-test

Demonstrates that commits to a gitlab repository can be mirrored to github.
<p>
The gitlab public key should be temporarily added to github authorized users,
github added as a remote, and a gitlab post-receive server hook that checks all 
revisions for a branch merge and pushes these to a github remote should be added.
</p>
<p>
If you are seeing this text in github, this does indeed work!
</p>