from gcr.io/cloud-solutions-images/jenkins-k8s-slave

run apt-get -y install --no-install-recommends python-pip

# lxc

copy test-git-install /tmp/test-git-install
copy test-ggl-install /tmp/test-ggl-install

run pip install -r /tmp/test-git-install/requirements.txt

run pip install -r /tmp/test-ggl-install/requirements.txt

 
