0x03. AirBnB clone - Deploy static

0. Prepare your web servers
Bash script that sets up your web servers for the deployment of web_static

1. Compress before sending
Fabric script that generates a .tgz archive from the contents of the web_static folder of your AirBnB Clone repo, using the function do_pack

2. Deploy archive!
Fabric script (based on the file 1-pack_web_static.py) that distributes an archive to your web servers, using the function do_deploy

3. Full deployment
Fabric script (based on the file 2-do_deploy_web_static.py) that creates and distributes an archive to your web servers, using the function deploy

4. Keep it clean!
Fabric script (based on the file 3-deploy_web_static.py) that deletes out-of-date archives, using the function do_clean

5. Puppet for setup
task #0 but by using Puppet
