# mirror-test

Demonstrates that commits to a gitlab repository can be mirrored to github.
<p>
The gitlab public key should be temporarily added to github authorized users,
github added as a remote, and the gitlab CI runner will take care of pushing
the change according to the .gitlab-ci instructions when merge to master occrs.
If you are seeing this text in github, this does indeed work!
<p>