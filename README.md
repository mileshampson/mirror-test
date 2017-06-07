# mirror-test

Demonstrates that commits to a gitlab repository can be mirrored to github.
<p>
The gitlab public key can be temporarily added to github authorized users, github added as a remote, and a gitlab 
post-receive server hook checking the branch revisions and pushing them to the github remote should be added.
</p>
<p>
If you are seeing this text in github, then the above does indeed work!
</p>