# sushy-tools

~~~bash
sudo podman create --net host --privileged --name sushy-tools -v "/etc/sushy":/etc/sushy -v "/root/.ssh":/root/.ssh "${SUSHY_TOOLS_IMAGE}" sushy-emulator -i :: -p 8000 --config /etc/sushy/sushy-emulator.conf
sudo podman start sushy-tools
~~~
