Feb 01 18:22:40 test-netology systemd[1]: var-lib-docker-overlay2-dc5aca292a6e09dad837a27f4ecc476932583614bf33ddfe60319f9cfd812db2\x2dinit-merged.mount: Succeeded.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit var-lib-docker-overlay2-dc5aca292a6e09dad837a27f4ecc476932583614bf33ddfe60319f9cfd812db2\x2dinit-merged.mount has successfully entered the 'dead' state.
Feb 01 18:22:40 test-netology systemd[1]: var-lib-docker-overlay2-dc5aca292a6e09dad837a27f4ecc476932583614bf33ddfe60319f9cfd812db2-merged.mount: Succeeded.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit var-lib-docker-overlay2-dc5aca292a6e09dad837a27f4ecc476932583614bf33ddfe60319f9cfd812db2-merged.mount has successfully entered the 'dead' state.
Feb 01 18:22:40 test-netology networkd-dispatcher[744]: WARNING:Unknown index 63 seen, reloading interface list
Feb 01 18:22:40 test-netology systemd-udevd[8863]: ethtool: autonegotiation is unset or enabled, the speed and duplex are not writable.
Feb 01 18:22:40 test-netology systemd-udevd[8863]: Using default interface naming scheme 'v245'.
Feb 01 18:22:40 test-netology systemd-udevd[8863]: veth52cee47: Could not generate persistent MAC: No data available
Feb 01 18:22:40 test-netology kernel: docker0: port 1(veth52cee47) entered blocking state
Feb 01 18:22:40 test-netology kernel: docker0: port 1(veth52cee47) entered disabled state
Feb 01 18:22:40 test-netology kernel: device veth52cee47 entered promiscuous mode
Feb 01 18:22:40 test-netology systemd-udevd[8861]: ethtool: autonegotiation is unset or enabled, the speed and duplex are not writable.
Feb 01 18:22:40 test-netology systemd-udevd[8861]: Using default interface naming scheme 'v245'.
Feb 01 18:22:40 test-netology systemd-udevd[8861]: vethd1c94e6: Could not generate persistent MAC: No data available
Feb 01 18:22:40 test-netology systemd-networkd[434]: veth52cee47: Link UP
Feb 01 18:22:40 test-netology containerd[893]: time="2022-02-01T18:22:40.379882865Z" level=info msg="starting signal loop" namespace=moby path=/run/containerd/io.containerd.runtim>
Feb 01 18:22:40 test-netology systemd[1]: run-docker-runtime\x2drunc-moby-eb75af43de5388761808db3d959d5353b9311493888e442d8db7064e2d965930-runc.qJ7GPj.mount: Succeeded.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit run-docker-runtime\x2drunc-moby-eb75af43de5388761808db3d959d5353b9311493888e442d8db7064e2d965930-runc.qJ7GPj.mount has successfully entered the 'dead' state.
Feb 01 18:22:40 test-netology systemd[1497]: run-docker-runtime\x2drunc-moby-eb75af43de5388761808db3d959d5353b9311493888e442d8db7064e2d965930-runc.qJ7GPj.mount: Succeeded.
-- Subject: Unit succeeded
<details>
  <summary>docker run hello-world</summary>
  
```shell
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit UNIT has successfully entered the 'dead' state.
Feb 01 18:22:40 test-netology systemd-networkd[434]: veth52cee47: Gained carrier
Feb 01 18:22:40 test-netology systemd-networkd[434]: docker0: Gained carrier
Feb 01 18:22:40 test-netology kernel: eth0: renamed from vethd1c94e6
Feb 01 18:22:40 test-netology kernel: IPv6: ADDRCONF(NETDEV_CHANGE): veth52cee47: link becomes ready
Feb 01 18:22:40 test-netology kernel: docker0: port 1(veth52cee47) entered blocking state
Feb 01 18:22:40 test-netology kernel: docker0: port 1(veth52cee47) entered forwarding state
Feb 01 18:22:40 test-netology containerd[893]: time="2022-02-01T18:22:40.996915811Z" level=info msg="shim disconnected" id=eb75af43de5388761808db3d959d5353b9311493888e442d8db7064e>
Feb 01 18:22:40 test-netology containerd[893]: time="2022-02-01T18:22:40.996958681Z" level=error msg="copy shim log" error="read /proc/self/fd/12: file already closed"
Feb 01 18:22:40 test-netology dockerd[1191]: time="2022-02-01T18:22:40.997742522Z" level=info msg="ignoring event" container=eb75af43de5388761808db3d959d5353b9311493888e442d8db706>
Feb 01 18:22:41 test-netology systemd-networkd[434]: veth52cee47: Lost carrier
Feb 01 18:22:41 test-netology kernel: docker0: port 1(veth52cee47) entered disabled state
Feb 01 18:22:41 test-netology kernel: vethd1c94e6: renamed from eth0
Feb 01 18:22:41 test-netology networkd-dispatcher[744]: WARNING:Unknown index 63 seen, reloading interface list
Feb 01 18:22:41 test-netology systemd-udevd[8930]: ethtool: autonegotiation is unset or enabled, the speed and duplex are not writable.
Feb 01 18:22:41 test-netology systemd-udevd[8930]: Using default interface naming scheme 'v245'.
Feb 01 18:22:41 test-netology lldpd[945]: removal request for address of fe80::27:7eff:fe04:7c30%64, but no knowledge of it
Feb 01 18:22:41 test-netology systemd-networkd[434]: veth52cee47: Link DOWN
Feb 01 18:22:41 test-netology systemd-networkd[434]: rtnl: received neighbor for link '64' we don't know about, ignoring.
Feb 01 18:22:41 test-netology kernel: docker0: port 1(veth52cee47) entered disabled state
Feb 01 18:22:41 test-netology kernel: device veth52cee47 left promiscuous mode
Feb 01 18:22:41 test-netology kernel: docker0: port 1(veth52cee47) entered disabled state
Feb 01 18:22:41 test-netology systemd-networkd[434]: rtnl: received neighbor for link '64' we don't know about, ignoring.
Feb 01 18:22:41 test-netology systemd-udevd[8930]: vethd1c94e6: Failed to get link config: No such device
Feb 01 18:22:41 test-netology systemd[1497]: run-docker-netns-ae319e5094c3.mount: Succeeded.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit UNIT has successfully entered the 'dead' state.
Feb 01 18:22:41 test-netology systemd[1]: run-docker-netns-ae319e5094c3.mount: Succeeded.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit run-docker-netns-ae319e5094c3.mount has successfully entered the 'dead' state.
Feb 01 18:22:41 test-netology systemd[1497]: var-lib-docker-overlay2-dc5aca292a6e09dad837a27f4ecc476932583614bf33ddfe60319f9cfd812db2-merged.mount: Succeeded.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit UNIT has successfully entered the 'dead' state.
Feb 01 18:22:41 test-netology systemd[1]: var-lib-docker-overlay2-dc5aca292a6e09dad837a27f4ecc476932583614bf33ddfe60319f9cfd812db2-merged.mount: Succeeded.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: http://www.ubuntu.com/support
-- 
-- The unit var-lib-docker-overlay2-dc5aca292a6e09dad837a27f4ecc476932583614bf33ddfe60319f9cfd812db2-merged.mount has successfully entered the 'dead' state.
Feb 01 18:22:41 test-netology systemd-networkd[434]: docker0: Lost carrier
```
  
</details>
