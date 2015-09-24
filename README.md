# CentOS 7.1 x86_64 with the puppet 3 agent pre-installed.

Can be used with `puppet apply` as a vagrant provisioner. The puppet agent service is not running by default. Firewall is enabled. Selinux is set to permissive.

You can find builds at https://atlas.hashicorp.com/jorisw/boxes/centos7.1-puppet3. If you are using vagrant you can use: `vagrant init jorisw/centos7.1-puppet3 && vagrant up --provider virtualbox`
