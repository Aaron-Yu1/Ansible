First run hosts.yaml, then run run_change_host_script.yml, then run install_containerd.yml, last run install_kubeadm.yml

Add a node to the cluster based on the command output of debug infomation.

After the installation is complete, you can use 'kubeadm token create' command to create a new token. Or view echo of  install_kubeadm.yml.
