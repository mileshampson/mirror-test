# mirror-test

Demonstrates that commits to a gitlab repository can be mirrored to github.
<p>
The gitlab public key should be temporarily added to github authorized users,
github added as a remote, and a gitlab pre-receive hook for pushing branch 
merges back to the github remote (only on a branch merge) should be added.
</p>
<p>
If you are seeing this text in github, this does indeed work!
</p>