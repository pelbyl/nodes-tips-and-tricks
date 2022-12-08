<h3> <b>The repository for nodes scripts.</b> </h3>
<br>
<b> Initial step.</b>
<p>
To simplify further ssh connection (avoid password insertion every time) we need to do the following.
<ul>
  <li>Connect to the server and create .ssh/authorized_keys containing a public key.</li>
  <li>Add config from the <a href="https://github.com/pelbyl/nodes-tips-and-tricks/blob/main/ssh_config_example">ssh_config_exaple</a>
to .ssh/config on a local machine.</li>
</ul>
After these steps we are ready to automate.
</p>
