# logs
root@txtserver:~# docker inspect backend

[
    {
        "Id": "051176bc43d27e968050d65afc78d8f53c3dc46fc01b2e3739f0c3b6d4bb36c5",
        "Created": "2024-11-30T12:39:02.952336665Z",
        "Path": "java",
        "Args": [
            "-jar",
            "app.jar"
        ],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 174070,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-11-30T12:49:50.847924036Z",
            "FinishedAt": "2024-11-30T12:47:20.256373318Z"
        },
        "Image": "sha256:5031c2ed4efff3490aa39d8b570d93b52e68484fa8122a287930e540ec8c387b",
        "ResolvConfPath": "/var/docker/containers/051176bc43d27e968050d65afc78d8f53c3dc46fc01b2e3739f0c3b6d4bb36c5/resolv.conf",
        "HostnamePath": "/var/docker/containers/051176bc43d27e968050d65afc78d8f53c3dc46fc01b2e3739f0c3b6d4bb36c5/hostname",
        "HostsPath": "/var/docker/containers/051176bc43d27e968050d65afc78d8f53c3dc46fc01b2e3739f0c3b6d4bb36c5/hosts",
        "LogPath": "/var/docker/containers/051176bc43d27e968050d65afc78d8f53c3dc46fc01b2e3739f0c3b6d4bb36c5/051176bc43d27e968050d65afc78d8f53c3dc46fc01b2e3739f0c3b6d4bb36c5-json.l                          og",
        "Name": "/backend",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {
                    "max-file": "3",
                    "max-size": "10m"
                }
            },
            "NetworkMode": "project-1_dev",
            "PortBindings": {
                "8080/tcp": [
                    {
                        "HostIp": "",
                        "HostPort": "8080"
                    }
                ]
            },
            "RestartPolicy": {
                "Name": "unless-stopped",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                0,
                0
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": null,
            "DnsOptions": null,
            "DnsSearch": null,
            "ExtraHosts": [],
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": null,
            "BlkioDeviceReadBps": null,
            "BlkioDeviceWriteBps": null,
            "BlkioDeviceReadIOps": null,
            "BlkioDeviceWriteIOps": null,
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": null,
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": null,
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/docker/overlay2/1be3349a4234a50d71601f5280c326cdac4d2ad468c35b9ff30f5d3cb67c8c3d-init/diff:/var/docker/overlay2/vagfda0tubzr8par12vagicfu/diff:/v                          ar/docker/overlay2/vojcuyk9oshslf3n4y8ed9bwc/diff:/var/docker/overlay2/949c87698567a9f85398055968f1351defafb4316c3556e576b8cf3ce519b5c8/diff:/var/docker/overlay2/52fda2c17ec739acb                          cb58fc7401b2a1455348c65b12e443e1e36c63f66bd30b7/diff:/var/docker/overlay2/71cb3effa395a5060f5ad2109687e063a60c00a2de3c3db268e838a4b60fa261/diff",
                "MergedDir": "/var/docker/overlay2/1be3349a4234a50d71601f5280c326cdac4d2ad468c35b9ff30f5d3cb67c8c3d/merged",
                "UpperDir": "/var/docker/overlay2/1be3349a4234a50d71601f5280c326cdac4d2ad468c35b9ff30f5d3cb67c8c3d/diff",
                "WorkDir": "/var/docker/overlay2/1be3349a4234a50d71601f5280c326cdac4d2ad468c35b9ff30f5d3cb67c8c3d/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "051176bc43d2",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": true,
            "AttachStderr": true,
            "ExposedPorts": {
                "8080/tcp": {}
            },
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": [
                "SPRING_DATASOURCE_URL=jdbc:postgresql://192.168.48.2:5432/postgres",
                "SPRING_DATASOURCE_USERNAME=postgres",
                "SPRING_DATASOURCE_PASSWORD=txtgroupadmin1234",
                "TZ=Asia/Tashkent",
                "PATH=/usr/local/openjdk-17/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin",
                "JAVA_HOME=/usr/local/openjdk-17",
                "LANG=C.UTF-8",
                "JAVA_VERSION=17.0.2"
            ],
            "Cmd": [
                "java",
                "-jar",
                "app.jar"
            ],
            "Image": "project-1-backend",
            "Volumes": null,
            "WorkingDir": "/app",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {
                "com.docker.compose.config-hash": "913411921aa0c9cbe748405f597c53c0af01e9b4f77e3fb49f819146598fea9e",
                "com.docker.compose.container-number": "1",
                "com.docker.compose.depends_on": "postgres:service_healthy:false",
                "com.docker.compose.image": "sha256:5031c2ed4efff3490aa39d8b570d93b52e68484fa8122a287930e540ec8c387b",
                "com.docker.compose.oneoff": "False",
                "com.docker.compose.project": "project-1",
                "com.docker.compose.project.config_files": "/root/projects/project-1/docker-compose.yml",
                "com.docker.compose.project.working_dir": "/root/projects/project-1",
                "com.docker.compose.service": "backend",
                "com.docker.compose.version": "2.30.3"
            }
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "84a2251735c435448f3609daff2f05645406ff955b4414816e0014dc91de25a1",
            "SandboxKey": "/var/run/docker/netns/84a2251735c4",
            "Ports": {
                "8080/tcp": [
                    {
                        "HostIp": "0.0.0.0",
                        "HostPort": "8080"
                    }
                ]
            },
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "project-1_dev": {
                    "IPAMConfig": {
                        "IPv4Address": "192.168.48.3"
                    },
                    "Links": null,
                    "Aliases": [
                        "backend",
                        "backend"
                    ],
                    "MacAddress": "02:42:c0:a8:30:03",
                    "NetworkID": "57cc3599e961faebab07ae876873579492de8fb57a47f1101b4af475a4182826",
                    "EndpointID": "29b0595a26d03f013c167c4300c9ff8884a3597ea74b41dec2e91b3c650e0c1d",
                    "Gateway": "192.168.48.1",
                    "IPAddress": "192.168.48.3",
                    "IPPrefixLen": 20,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "backend",
                        "051176bc43d2"
                    ]
                }
            }
        }
    }
]
root@txtserver:~#
root@txtserver:~# docker exec -it backend psql -h 192.168.48.2 -U postgres -d postgres
OCI runtime exec failed: exec failed: unable to start container process: exec: "psql": executable file not found in $PATH: unknown
root@txtserver:~# docker exec -it backend bash
root@051176bc43d2:/app# psql -h 192.168.48.2 -U postgres -d postgres
bash: psql: command not found
root@051176bc43d2:/app# apt update
Get:1 http://deb.debian.org/debian bullseye InRelease [116 kB]
Get:2 http://security.debian.org/debian-security bullseye-security InRelease [27.2 kB]
Get:3 http://deb.debian.org/debian bullseye-updates InRelease [44.1 kB]
Get:4 http://security.debian.org/debian-security bullseye-security/main amd64 Packages [317 kB]
Get:5 http://deb.debian.org/debian bullseye/main amd64 Packages [8066 kB]
Get:6 http://deb.debian.org/debian bullseye-updates/main amd64 Packages [18.8 kB]
Fetched 8589 kB in 2s (4202 kB/s)
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
44 packages can be upgraded. Run 'apt list --upgradable' to see them.
root@051176bc43d2:/app# apt install postgresql-client
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libldap-2.4-2 libldap-common libpq5 libreadline8 libsasl2-2 libsasl2-modules libsasl2-modules-db netbase postgresql-client-13 postgresql-client-common readline-common
  sensible-utils
Suggested packages:
  libsasl2-modules-gssapi-mit | libsasl2-modules-gssapi-heimdal libsasl2-modules-ldap libsasl2-modules-otp libsasl2-modules-sql postgresql-13 postgresql-doc-13 readline-doc
The following NEW packages will be installed:
  libldap-2.4-2 libldap-common libpq5 libreadline8 libsasl2-2 libsasl2-modules libsasl2-modules-db netbase postgresql-client postgresql-client-13 postgresql-client-common
  readline-common sensible-utils
0 upgraded, 13 newly installed, 0 to remove and 44 not upgraded.
Need to get 2739 kB of archives.
After this operation, 9620 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://deb.debian.org/debian bullseye/main amd64 readline-common all 8.1-1 [73.7 kB]
Get:2 http://security.debian.org/debian-security bullseye-security/main amd64 libpq5 amd64 13.18-0+deb11u1 [184 kB]
Get:3 http://deb.debian.org/debian bullseye/main amd64 libreadline8 amd64 8.1-1 [169 kB]
Get:4 http://security.debian.org/debian-security bullseye-security/main amd64 postgresql-client-13 amd64 13.18-0+deb11u1 [1517 kB]
Get:5 http://deb.debian.org/debian bullseye/main amd64 netbase all 6.3 [19.9 kB]
Get:6 http://deb.debian.org/debian bullseye/main amd64 sensible-utils all 0.0.14 [14.8 kB]
Get:7 http://deb.debian.org/debian bullseye/main amd64 libsasl2-modules-db amd64 2.1.27+dfsg-2.1+deb11u1 [69.1 kB]
Get:8 http://deb.debian.org/debian bullseye/main amd64 libsasl2-2 amd64 2.1.27+dfsg-2.1+deb11u1 [106 kB]
Get:9 http://deb.debian.org/debian bullseye/main amd64 libldap-2.4-2 amd64 2.4.57+dfsg-3+deb11u1 [232 kB]
Get:10 http://deb.debian.org/debian bullseye/main amd64 libldap-common all 2.4.57+dfsg-3+deb11u1 [95.8 kB]
Get:11 http://deb.debian.org/debian bullseye/main amd64 libsasl2-modules amd64 2.1.27+dfsg-2.1+deb11u1 [104 kB]
Get:12 http://deb.debian.org/debian bullseye/main amd64 postgresql-client-common all 225+deb11u1 [89.4 kB]
Get:13 http://deb.debian.org/debian bullseye/main amd64 postgresql-client all 13+225+deb11u1 [64.9 kB]
Fetched 2739 kB in 1s (3678 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package readline-common.
(Reading database ... 7063 files and directories currently installed.)
Preparing to unpack .../00-readline-common_8.1-1_all.deb ...
Unpacking readline-common (8.1-1) ...
Selecting previously unselected package libreadline8:amd64.
Preparing to unpack .../01-libreadline8_8.1-1_amd64.deb ...
Unpacking libreadline8:amd64 (8.1-1) ...
Selecting previously unselected package netbase.
Preparing to unpack .../02-netbase_6.3_all.deb ...
Unpacking netbase (6.3) ...
Selecting previously unselected package sensible-utils.
Preparing to unpack .../03-sensible-utils_0.0.14_all.deb ...
Unpacking sensible-utils (0.0.14) ...
Selecting previously unselected package libsasl2-modules-db:amd64.
Preparing to unpack .../04-libsasl2-modules-db_2.1.27+dfsg-2.1+deb11u1_amd64.deb ...
Unpacking libsasl2-modules-db:amd64 (2.1.27+dfsg-2.1+deb11u1) ...
Selecting previously unselected package libsasl2-2:amd64.
Preparing to unpack .../05-libsasl2-2_2.1.27+dfsg-2.1+deb11u1_amd64.deb ...
Unpacking libsasl2-2:amd64 (2.1.27+dfsg-2.1+deb11u1) ...
Selecting previously unselected package libldap-2.4-2:amd64.
Preparing to unpack .../06-libldap-2.4-2_2.4.57+dfsg-3+deb11u1_amd64.deb ...
Unpacking libldap-2.4-2:amd64 (2.4.57+dfsg-3+deb11u1) ...
Selecting previously unselected package libldap-common.
Preparing to unpack .../07-libldap-common_2.4.57+dfsg-3+deb11u1_all.deb ...
Unpacking libldap-common (2.4.57+dfsg-3+deb11u1) ...
Selecting previously unselected package libpq5:amd64.
Preparing to unpack .../08-libpq5_13.18-0+deb11u1_amd64.deb ...
Unpacking libpq5:amd64 (13.18-0+deb11u1) ...
Selecting previously unselected package libsasl2-modules:amd64.
Preparing to unpack .../09-libsasl2-modules_2.1.27+dfsg-2.1+deb11u1_amd64.deb ...
Unpacking libsasl2-modules:amd64 (2.1.27+dfsg-2.1+deb11u1) ...
Selecting previously unselected package postgresql-client-common.
Preparing to unpack .../10-postgresql-client-common_225+deb11u1_all.deb ...
Unpacking postgresql-client-common (225+deb11u1) ...
Selecting previously unselected package postgresql-client-13.
Preparing to unpack .../11-postgresql-client-13_13.18-0+deb11u1_amd64.deb ...
Unpacking postgresql-client-13 (13.18-0+deb11u1) ...
Selecting previously unselected package postgresql-client.
Preparing to unpack .../12-postgresql-client_13+225+deb11u1_all.deb ...
Unpacking postgresql-client (13+225+deb11u1) ...
Setting up libsasl2-modules:amd64 (2.1.27+dfsg-2.1+deb11u1) ...
Setting up libldap-common (2.4.57+dfsg-3+deb11u1) ...
Setting up libsasl2-modules-db:amd64 (2.1.27+dfsg-2.1+deb11u1) ...
Setting up libsasl2-2:amd64 (2.1.27+dfsg-2.1+deb11u1) ...
Setting up sensible-utils (0.0.14) ...
Setting up netbase (6.3) ...
Setting up readline-common (8.1-1) ...
Setting up postgresql-client-common (225+deb11u1) ...
Setting up libreadline8:amd64 (8.1-1) ...
Setting up libldap-2.4-2:amd64 (2.4.57+dfsg-3+deb11u1) ...
Setting up libpq5:amd64 (13.18-0+deb11u1) ...
Setting up postgresql-client-13 (13.18-0+deb11u1) ...
update-alternatives: using /usr/share/postgresql/13/man/man1/psql.1.gz to provide /usr/share/man/man1/psql.1.gz (psql.1.gz) in auto mode
Setting up postgresql-client (13+225+deb11u1) ...
Processing triggers for libc-bin (2.31-13+deb11u3) ...
root@051176bc43d2:/app# psql -h 192.168.48.2 -U postgres -d postgres
Password for user postgres:
psql (13.18 (Debian 13.18-0+deb11u1), server 16.6 (Debian 16.6-1.pgdg120+1))
WARNING: psql major version 13, server major version 16.
         Some psql features might not work.
Type "help" for help.

postgres=# \д
invalid command \д
Try \? for help.
postgres=# \l
                                 List of databases
   Name    |  Owner   | Encoding |  Collate   |   Ctype    |   Access privileges
-----------+----------+----------+------------+------------+-----------------------
 postgres  | postgres | UTF8     | en_US.utf8 | en_US.utf8 |
 template0 | postgres | UTF8     | en_US.utf8 | en_US.utf8 | =c/postgres          +
           |          |          |            |            | postgres=CTc/postgres
 template1 | postgres | UTF8     | en_US.utf8 | en_US.utf8 | =c/postgres          +
           |          |          |            |            | postgres=CTc/postgres
(3 rows)

postgres=# \q
root@051176bc43d2:/app# exit
exit
root@txtserver:~# docker exec backend printenv | grep SPRING_DATASOURCE
SPRING_DATASOURCE_URL=jdbc:postgresql://192.168.48.2:5432/postgres
SPRING_DATASOURCE_USERNAME=postgres
SPRING_DATASOURCE_PASSWORD=txtgroupadmin1234
root@txtserver:~# docker exec -it backend bash
root@051176bc43d2:/app# find /app -name "*.properties" -o -name "*.yml"
root@051176bc43d2:/app# ls /app/app.jar
/app/app.jar
root@051176bc43d2:/app# ls
app.jar
root@051176bc43d2:/app# apt nano
E: Invalid operation nano
root@051176bc43d2:/app# nano app.jar
bash: nano: command not found
root@051176bc43d2:/app# cd
root@051176bc43d2:~# apt install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6 libtinfo6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
The following packages will be upgraded:
  libtinfo6
1 upgraded, 3 newly installed, 0 to remove and 43 not upgraded.
Need to get 1166 kB of archives.
After this operation, 3088 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://deb.debian.org/debian bullseye/main amd64 libtinfo6 amd64 6.2+20201114-2+deb11u2 [342 kB]
Get:2 http://deb.debian.org/debian bullseye/main amd64 libncursesw6 amd64 6.2+20201114-2+deb11u2 [132 kB]
Get:3 http://deb.debian.org/debian bullseye/main amd64 nano amd64 5.4-2+deb11u3 [657 kB]
Get:4 http://deb.debian.org/debian bullseye/main amd64 libgpm2 amd64 1.20.7-8 [35.6 kB]
Fetched 1166 kB in 1s (1321 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
(Reading database ... 7565 files and directories currently installed.)
Preparing to unpack .../libtinfo6_6.2+20201114-2+deb11u2_amd64.deb ...
Unpacking libtinfo6:amd64 (6.2+20201114-2+deb11u2) over (6.2+20201114-2) ...
Setting up libtinfo6:amd64 (6.2+20201114-2+deb11u2) ...
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 7565 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.2+20201114-2+deb11u2_amd64.deb ...
Unpacking libncursesw6:amd64 (6.2+20201114-2+deb11u2) ...
Selecting previously unselected package nano.
Preparing to unpack .../nano_5.4-2+deb11u3_amd64.deb ...
Unpacking nano (5.4-2+deb11u3) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-8_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-8) ...
Setting up libgpm2:amd64 (1.20.7-8) ...
Setting up libncursesw6:amd64 (6.2+20201114-2+deb11u2) ...
Setting up nano (5.4-2+deb11u3) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: warning: skip creation of /usr/share/man/man1/editor.1.gz because associated file /usr/share/man/man1/nano.1.gz (of link group editor) doesn't exist
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
update-alternatives: warning: skip creation of /usr/share/man/man1/pico.1.gz because associated file /usr/share/man/man1/nano.1.gz (of link group pico) doesn't exist
Processing triggers for libc-bin (2.31-13+deb11u3) ...
root@051176bc43d2:~# find / -name "*.properties" -o -name "*.yml"
/usr/local/openjdk-17/lib/psfontj2d.properties
/usr/local/openjdk-17/conf/logging.properties
/usr/local/openjdk-17/conf/net.properties
/usr/local/openjdk-17/conf/sound.properties
/usr/local/openjdk-17/conf/management/management.properties
root@051176bc43d2:~# find -name "*.properties" -o -name "*.yml"
root@051176bc43d2:~# nano /app/app.jar .
./             ../            .bash_history  .bashrc        .profile       .psql_history
root@051176bc43d2:~# nano /app/app.jar
root@051176bc43d2:~# nano /tmp/
hsperfdata_root/                         tomcat-docbase.8080.1334056451459272658/ tomcat.8080.18381895924593768860/        tomcat.8080.1988763232020794301/
root@051176bc43d2:~# apt install unzip
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Suggested packages:
  zip
The following NEW packages will be installed:
  unzip
0 upgraded, 1 newly installed, 0 to remove and 43 not upgraded.
Need to get 172 kB of archives.
After this operation, 393 kB of additional disk space will be used.
Get:1 http://deb.debian.org/debian bullseye/main amd64 unzip amd64 6.0-26+deb11u1 [172 kB]
Fetched 172 kB in 6s (28.4 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package unzip.
(Reading database ... 7687 files and directories currently installed.)
Preparing to unpack .../unzip_6.0-26+deb11u1_amd64.deb ...
Unpacking unzip (6.0-26+deb11u1) ...
Setting up unzip (6.0-26+deb11u1) ...
root@051176bc43d2:~# ls /app/*.jar
/app/app.jar
root@051176bc43d2:~# mkdir /tmp/jar-content
unzip /app/app.jar -d /tmp/jar-content
Archive:  /app/app.jar
   creating: /tmp/jar-content/META-INF/
  inflating: /tmp/jar-content/META-INF/MANIFEST.MF
   creating: /tmp/jar-content/META-INF/services/
  inflating: /tmp/jar-content/META-INF/services/java.nio.file.spi.FileSystemProvider
   creating: /tmp/jar-content/org/
   creating: /tmp/jar-content/org/springframework/
   creating: /tmp/jar-content/org/springframework/boot/
   creating: /tmp/jar-content/org/springframework/boot/loader/
   creating: /tmp/jar-content/org/springframework/boot/loader/jar/
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/JarEntriesStream$InputStreamSupplier.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/JarEntriesStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/ManifestInfo.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/MetaInfVersionsInfo.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFile$JarEntriesEnumeration.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFile$JarEntryInflaterInputStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFile$JarEntryInputStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFile$NestedJarEntry.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFile$RawZipDataInputStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFile$ZipContentEntriesSpliterator.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFile.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/NestedJarFileResources.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/SecurityInfo.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/jar/ZipInflaterInputStream.class
   creating: /tmp/jar-content/org/springframework/boot/loader/jarmode/
  inflating: /tmp/jar-content/org/springframework/boot/loader/jarmode/JarMode.class
   creating: /tmp/jar-content/org/springframework/boot/loader/launch/
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/Archive$Entry.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/Archive.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/ClassPathIndexFile.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/ExecutableArchiveLauncher.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/ExplodedArchive$FileArchiveEntry.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/ExplodedArchive.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/JarFileArchive$JarArchiveEntry.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/JarFileArchive.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/JarLauncher.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/JarModeRunner.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/LaunchedClassLoader$DefinePackageCallType.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/LaunchedClassLoader.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/Launcher.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/PropertiesLauncher$Instantiator$Using.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/PropertiesLauncher$Instantiator.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/PropertiesLauncher.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/SystemPropertyUtils.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/launch/WarLauncher.class
   creating: /tmp/jar-content/org/springframework/boot/loader/log/
  inflating: /tmp/jar-content/org/springframework/boot/loader/log/DebugLogger$DisabledDebugLogger.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/log/DebugLogger$SystemErrDebugLogger.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/log/DebugLogger.class
   creating: /tmp/jar-content/org/springframework/boot/loader/net/
   creating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/Handlers.class
   creating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/Canonicalizer.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/Handler.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/JarFileUrlKey.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/JarUrl.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/JarUrlClassLoader$OptimizedEnumeration.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/JarUrlClassLoader.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/JarUrlConnection$ConnectionInputStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/JarUrlConnection$EmptyUrlStreamHandler.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/JarUrlConnection.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/LazyDelegatingInputStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/Optimizations.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlJarEntry.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlJarFile.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlJarFileFactory.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlJarFiles$Cache.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlJarFiles.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlJarManifest$ManifestSupplier.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlJarManifest.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/jar/UrlNestedJarFile.class
   creating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/nested/
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/nested/Handler.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/nested/NestedLocation.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/nested/NestedUrlConnection$ConnectionInputStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/nested/NestedUrlConnection.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/protocol/nested/NestedUrlConnectionResources.class
   creating: /tmp/jar-content/org/springframework/boot/loader/net/util/
  inflating: /tmp/jar-content/org/springframework/boot/loader/net/util/UrlDecoder.class
   creating: /tmp/jar-content/org/springframework/boot/loader/nio/
   creating: /tmp/jar-content/org/springframework/boot/loader/nio/file/
  inflating: /tmp/jar-content/org/springframework/boot/loader/nio/file/NestedByteChannel$Resources.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/nio/file/NestedByteChannel.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/nio/file/NestedFileStore.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/nio/file/NestedFileSystem.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/nio/file/NestedFileSystemProvider.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/nio/file/NestedPath.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/nio/file/UriPathEncoder.class
   creating: /tmp/jar-content/org/springframework/boot/loader/ref/
  inflating: /tmp/jar-content/org/springframework/boot/loader/ref/Cleaner.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/ref/DefaultCleaner.class
   creating: /tmp/jar-content/org/springframework/boot/loader/zip/
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ByteArrayDataBlock.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/CloseableDataBlock.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/DataBlock.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/DataBlockInputStream.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/FileDataBlock$FileAccess.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/FileDataBlock$Tracker$1.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/FileDataBlock$Tracker.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/FileDataBlock.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/NameOffsetLookups.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/VirtualDataBlock.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/VirtualZipDataBlock$DataPart.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/VirtualZipDataBlock.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/Zip64EndOfCentralDirectoryLocator.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/Zip64EndOfCentralDirectoryRecord.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipCentralDirectoryFileHeaderRecord.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipContent$Entry.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipContent$Kind.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipContent$Loader.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipContent$Source.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipContent.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipDataDescriptorRecord.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipEndOfCentralDirectoryRecord$Located.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipEndOfCentralDirectoryRecord.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipLocalFileHeaderRecord.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipString$CompareType.class
  inflating: /tmp/jar-content/org/springframework/boot/loader/zip/ZipString.class
   creating: /tmp/jar-content/BOOT-INF/
   creating: /tmp/jar-content/BOOT-INF/classes/
   creating: /tmp/jar-content/BOOT-INF/classes/db/
   creating: /tmp/jar-content/BOOT-INF/classes/db/scripts/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/config/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/supply/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/user/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/salary/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/menu/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/building/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/warehouse/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/handlers/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/utils/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/exception/
   creating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/security/
   creating: /tmp/jar-content/META-INF/maven/
   creating: /tmp/jar-content/META-INF/maven/uz/
   creating: /tmp/jar-content/META-INF/maven/uz/txtgroup/
  inflating: /tmp/jar-content/BOOT-INF/classes/application-dev.yml
  inflating: /tmp/jar-content/BOOT-INF/classes/application-dev.yml.save
  inflating: /tmp/jar-content/BOOT-INF/classes/application-prod.yml
  inflating: /tmp/jar-content/BOOT-INF/classes/db/changeLog.yaml
  inflating: /tmp/jar-content/BOOT-INF/classes/db/initial_migration.sql
  inflating: /tmp/jar-content/BOOT-INF/classes/db/scripts/001-exceptions_log.sql
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/PingController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/ReceiptController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/CashTransferController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/ProjectController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/UnitController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/CategoryController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/TransactionController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/ContragentController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/SupplierController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/CashController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/SupplyController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/MaterialController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/AuthenticationController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/FinanceReportController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/EndpointsListener.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/WarehouseController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/PaymentController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/PaymentMethodController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/UserController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/MenuController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/CurrencyController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/RoleController.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/controller/EndpointsListener$Endpoint.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/config/DataLoadaer.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/config/HttpSecurityConfig.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/MaterialCategoryService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/ProjectService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/CashReportService$1.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/UnitService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/TransactionService$1.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/SupplierService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/CashTransferService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/ContragentService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/FinanceReportService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/UserService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/PaymentMethodService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/CategoryService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/MenuService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/MaterialService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/TransactionService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/ReceiptService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/CashReportService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/RoleService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/CashService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/CurrencyService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/AuthenticationService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/service/BalanceInfoService.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashTransferDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashTransferDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CurrencyDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ProjectDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UnitDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CategoryDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MaterialDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CategoryDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UserDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/SupplierDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UserDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ContragentDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UnitDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashTransferDto$Report.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ProjectDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashReportRequestDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UnitDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashReportRequestDto$Filed.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/TransactionDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto$Item.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MaterialCategoryDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CategoryDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/SupplierDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/RoleDto$CurrentRole.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MenuDto$SubMenu.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto$ItemAdd.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/TransactionDto$Transfer.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/RoleDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/WarehouseDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashDto$Balance.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/AuthenticationDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/SupplierDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MenuDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/RoleDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UnitGroupDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ProjectDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/SupplierDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MenuDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto$ItemEdit.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/RoleDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/PaymentMethodDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ContragentDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UserDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MenuDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UserDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MenuDto$Action.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/AuthenticationDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/SupplierDto$Search.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ContragentDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MaterialDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UserDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UserDto$CurrentUser.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CurrencyDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/TransactionDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashDto$Info.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/ApiStatus.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/PageableDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/ApiResponse$Builder.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/PageableDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/PageableDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/ApiResponse.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/api/PageableDto$OrderType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/SupplierDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MaterialCategoryDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ReceiptDto$Pageable.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ProjectDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/TransactionDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/TransactionDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/PaymentMethodDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UnitDto$GroupUpdate.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashTransferDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashReportRequestDto$ConditionType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CurrencyDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UnitDto$GroupCreate.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MaterialCategoryDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/CashDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/UnitDto$Request.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/AuthenticationDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/PaymentMethodDto$Create.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MaterialDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/ProjectDto$Update.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/TransactionDto$Response.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/MenuDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/dto/RoleDto.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/ExceptionLogRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/UnitGroupRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/OurRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/MenuRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/ReceiptRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/UserRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/CategoryRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/MaterialCategoryRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/WarehouseRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/RoleRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/MaterialRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/UnitRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/SubMenuRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/PaymentMethodRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/ProjectRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/CashRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/SupplierRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/ContragentRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/TransactionRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/CurrencyRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/ActionsRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/repo/CashTransferRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/Restrictions$2.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/BaseEntityWithId.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/BaseEntityWithId$BaseEntityWithIdBuilder.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/Restrictions$Conn.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/RequestLog.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/Restrictions$Condition.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/EntityChangeLogging.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/Restrictions$1.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/DomainMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/ExceptionLog.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/Restrictions$ConditionType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Utils/Restrictions.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Unit.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/supply/Receipt.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/supply/Supplier.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/supply/ReceiptItem.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/supply/ReceiptItemRepo.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Department.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/user/User.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/user/Role.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Project.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/UnitGroup.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Block.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/ContragentType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/PaymentMethod.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/Currency.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/CategoryType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/Our.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/Transaction.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/Category.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/CashTransfer.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/Cash.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/finance/TransactionType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/Contragent.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/salary/CalendarDate.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/salary/Salary.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/salary/Employee.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/salary/Attendance.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/salary/Payroll.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/menu/Action.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/menu/SubMenu.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/menu/Menu.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/building/Work.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/building/WorkType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/building/Worker.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/warehouse/WarehouseOperation.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/warehouse/MaterialCategory.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/warehouse/Warehouse.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/warehouse/Inventory.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/warehouse/OperationType.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/model/warehouse/Material.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/handlers/CustomExceptionHandler.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/handlers/CustomAccessDeniedHandler.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/Application.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/utils/TupleConverter.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/utils/CollectClass.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/utils/RepoUtil.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/UnitMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CashTransferMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/MaterialMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/TransactionMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/RoleMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/PaymentMethodMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CurrencyMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CategoryMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/RoleMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/SupplierMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/ProjectMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/ReceiptMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/UserDtoMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/UnitGroupMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/ProjectMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/MaterialMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/ReceiptMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CurrencyMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/SupplierMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/MaterialCategoryMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/TransactionMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CashMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/MaterialCategoryMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/MenuMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CashTransferMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/UnitMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/MenuMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/WarehouseMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/UnitGroupMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CashMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/WarehouseMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/UserDtoMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/ContragentMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/CategoryMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/ContragentMapper.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/mapper/PaymentMethodMapperImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/exception/NotFoundException.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/security/UserDetailsServiceImpl.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/security/CustomUserDetails.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/security/JwtTokenFilter.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/security/CustomAuthenticationEntryPoint.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/security/JwtAuthenticationException.class
  inflating: /tmp/jar-content/BOOT-INF/classes/uz/txtgroup/security/JwtTokenProvider.class
  inflating: /tmp/jar-content/BOOT-INF/classes/application.yml
  inflating: /tmp/jar-content/META-INF/maven/uz/txtgroup/pom.xml
  inflating: /tmp/jar-content/META-INF/maven/uz/txtgroup/pom.properties
   creating: /tmp/jar-content/BOOT-INF/lib/
 extracting: /tmp/jar-content/BOOT-INF/lib/aspectjweaver-1.9.22.1.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/HikariCP-5.1.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-jdbc-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/hibernate-core-6.5.3.Final.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jakarta.persistence-api-3.1.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jakarta.transaction-api-2.0.1.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jboss-logging-3.5.3.Final.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/hibernate-commons-annotations-6.0.6.Final.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jandex-3.1.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/classmate-1.7.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/byte-buddy-1.14.19.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jaxb-runtime-4.0.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jaxb-core-4.0.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/angus-activation-2.0.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/txw2-4.0.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/istack-commons-runtime-4.1.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jakarta.inject-api-2.0.1.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/antlr4-runtime-4.13.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-data-jpa-3.3.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-data-commons-3.3.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-orm-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-context-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-tx-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-beans-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jakarta.annotation-api-2.1.1.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/slf4j-api-2.0.16.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-aspects-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-boot-3.3.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-boot-autoconfigure-3.3.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/logback-classic-1.5.11.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/logback-core-1.5.11.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/log4j-to-slf4j-2.23.1.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/log4j-api-2.23.1.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jul-to-slf4j-2.0.16.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-aop-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-security-config-6.3.4.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-security-core-6.3.4.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-security-crypto-6.3.4.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-security-web-6.3.4.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-expression-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jackson-datatype-jdk8-2.17.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jackson-datatype-jsr310-2.17.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jackson-module-parameter-names-2.17.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/tomcat-embed-core-10.1.31.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/tomcat-embed-websocket-10.1.31.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-web-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/micrometer-observation-1.13.6.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/micrometer-commons-1.13.6.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-webmvc-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/tomcat-embed-el-10.1.31.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/hibernate-validator-8.0.1.Final.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/postgresql-42.7.3.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/checker-qual-3.42.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/mapstruct-1.5.5.Final.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jakarta.validation-api-3.1.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jjwt-api-0.11.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jjwt-impl-0.11.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jjwt-jackson-0.11.5.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jackson-databind-2.17.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jackson-annotations-2.17.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jackson-core-2.17.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jakarta.xml.bind-api-4.0.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jakarta.activation-api-2.1.3.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-core-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-jcl-6.1.14.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/commons-lang3-3.12.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/liquibase-core-4.25.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/opencsv-5.8.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/commons-text-1.10.0.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/commons-collections4-4.4.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/snakeyaml-2.2.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/jaxb-api-2.3.1.jar
 extracting: /tmp/jar-content/BOOT-INF/lib/spring-boot-jarmode-tools-3.3.5.jar
  inflating: /tmp/jar-content/BOOT-INF/classpath.idx
  inflating: /tmp/jar-content/BOOT-INF/layers.idx
root@051176bc43d2:~# find /tmp/jar-content -name "*.properties" -o -name "*.yml"
/tmp/jar-content/META-INF/maven/uz/txtgroup/pom.properties
/tmp/jar-content/BOOT-INF/classes/application-dev.yml
/tmp/jar-content/BOOT-INF/classes/application-prod.yml
/tmp/jar-content/BOOT-INF/classes/application.yml
root@051176bc43d2:~# printenv | grep SPRING_PROFILES_ACTIVE
root@051176bc43d2:~# nano /tmp/jar-content/BOOT-INF/classes/application-dev.yml
root@051176bc43d2:~# ping
bash: ping: command not found
root@051176bc43d2:~# apt install ping
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Package ping is a virtual package provided by:
  iputils-ping 3:20210202-1
  inetutils-ping 2:2.0-1+deb11u2
You should explicitly select one to install.

E: Package 'ping' has no installation candidate
root@051176bc43d2:~# exit
exit
root@txtserver:~# docker logs backend
2024-11-30T17:42:08.935+05:00  INFO 1 --- [txtgroup] [           main] uz.txtgroup.Application                  : Starting Application v0.0.1-SNAPSHOT using Java 17.0.2 with PID 1                           (/app/app.jar started by root in /app)
2024-11-30T17:42:08.937+05:00  INFO 1 --- [txtgroup] [           main] uz.txtgroup.Application                  : The following 1 profile is active: "dev"
2024-11-30T17:42:09.304+05:00  INFO 1 --- [txtgroup] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2024-11-30T17:42:09.363+05:00  INFO 1 --- [txtgroup] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 55 ms. Found 23 JPA r                          epository interfaces.
2024-11-30T17:42:09.678+05:00  INFO 1 --- [txtgroup] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2024-11-30T17:42:09.685+05:00  INFO 1 --- [txtgroup] [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2024-11-30T17:42:09.685+05:00  INFO 1 --- [txtgroup] [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.31]
2024-11-30T17:42:09.703+05:00  INFO 1 --- [txtgroup] [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2024-11-30T17:42:09.704+05:00  INFO 1 --- [txtgroup] [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 747 ms
2024-11-30T17:42:09.944+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Reading resource: db/scripts/001-exceptions_log.sql
2024-11-30T17:42:09.969+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Creating database history table with name: public.databasechangel                          og
2024-11-30T17:42:10.185+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Reading from public.databasechangelog
2024-11-30T17:42:10.622+05:00  INFO 1 --- [txtgroup] [           main] liquibase.lockservice                    : Successfully acquired change log lock
2024-11-30T17:42:10.623+05:00  INFO 1 --- [txtgroup] [           main] liquibase.command                        : Using deploymentId: 2970530623
2024-11-30T17:42:10.624+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Reading from public.databasechangelog
2024-11-30T17:42:10.642+05:00  INFO 1 --- [txtgroup] [           main] liquibase.ui                             : Running Changeset: db/scripts/001-exceptions_log.sql::001::Kamoli                          ddin
2024-11-30T17:42:10.965+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Custom SQL executed
2024-11-30T17:42:10.981+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : ChangeSet db/scripts/001-exceptions_log.sql::001::Kamoliddin ran                           successfully in 338ms
2024-11-30T17:42:11.005+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : UPDATE SUMMARY
2024-11-30T17:42:11.005+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Run:                          1
2024-11-30T17:42:11.005+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Previously run:               0
2024-11-30T17:42:11.005+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Filtered out:                 0
2024-11-30T17:42:11.005+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : -------------------------------
2024-11-30T17:42:11.005+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Total change sets:            1
2024-11-30T17:42:11.005+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Update summary generated
2024-11-30T17:42:11.007+05:00  INFO 1 --- [txtgroup] [           main] liquibase.command                        : Update command completed successfully.
2024-11-30T17:42:11.007+05:00  INFO 1 --- [txtgroup] [           main] liquibase.ui                             : Liquibase: Update has been successful. Rows affected: 1
2024-11-30T17:42:11.018+05:00  INFO 1 --- [txtgroup] [           main] liquibase.lockservice                    : Successfully released change log lock
2024-11-30T17:42:11.018+05:00  INFO 1 --- [txtgroup] [           main] liquibase.command                        : Command execution complete
2024-11-30T17:42:11.051+05:00  INFO 1 --- [txtgroup] [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2024-11-30T17:42:11.073+05:00  INFO 1 --- [txtgroup] [           main] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 6.5.3.Final
2024-11-30T17:42:11.087+05:00  INFO 1 --- [txtgroup] [           main] o.h.c.internal.RegionFactoryInitiator    : HHH000026: Second-level cache disabled
2024-11-30T17:42:11.205+05:00  INFO 1 --- [txtgroup] [           main] o.s.o.j.p.SpringPersistenceUnitInfo      : No LoadTimeWeaver setup: ignoring JPA class transformer
2024-11-30T17:42:11.217+05:00  INFO 1 --- [txtgroup] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2024-11-30T17:42:11.228+05:00  INFO 1 --- [txtgroup] [           main] com.zaxxer.hikari.pool.HikariPool        : HikariPool-1 - Added connection org.postgresql.jdbc.PgConnection@                          432eb882
2024-11-30T17:42:11.228+05:00  INFO 1 --- [txtgroup] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2024-11-30T17:42:11.243+05:00  WARN 1 --- [txtgroup] [           main] org.hibernate.orm.deprecation            : HHH90000025: PostgreSQLDialect does not need to be specified expl                          icitly using 'hibernate.dialect' (remove the property setting and it will be selected by default)
2024-11-30T17:42:11.842+05:00  INFO 1 --- [txtgroup] [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000489: No JTA platform available (set 'hibernate.transaction.                          jta.platform' to enable JTA platform integration)
Hibernate:
    create table actions (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        path varchar(255),
        "sub-menu-id" bigint,
        primary key (id)
    )
Hibernate:
    create table attendances (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        total_working_days_in_month integer not null,
        salary_id bigint,
        primary key (id)
    )
Hibernate:
    create table blocks (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(50),
        title varchar(50),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table calendar_dates (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        attendance_rate float(53) not null,
        date date,
        attendance_id bigint,
        primary key (id)
    )
Hibernate:
    create table cash_transfer (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount float(53),
        comment varchar(100),
        date date,
        description varchar(100),
        exchange_rate float(53),
        is_completed boolean,
        is_declined boolean,
        is_exchange_payment boolean,
        transaction_type varchar(50) check (transaction_type in ('INCOME','EXPENSE','TRANSFER_IN','TRANSFER_OUT')),
        cash_id bigint,
        category_id bigint,
        contragent_id bigint,
        couple_id bigint,
        currency_id bigint,
        payment_method_id bigint,
        user_id bigint,
        primary key (id)
    )
Hibernate:
    create table cash_users (
        cash_id bigint not null,
        user_id bigint not null
    )
Hibernate:
    create table cashes (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table categories (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table contragents (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        type varchar(255) check (type in ('SUPPLIER','WORKER','EMPLOYEE','CASH','INVESTOR','BANK')),
        primary key (id)
    )
Hibernate:
    create table currencies (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table departments (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(255),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table employees (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        contragent_id bigint,
        department_id bigint,
        project_id bigint,
        primary key (id)
    )
Hibernate:
    alter table if exists exceptions_log
       alter column exception_text set data type TEXT
Hibernate:
    alter table if exists exceptions_log
       alter column message set data type TEXT
Hibernate:
    create table material_categories (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table materials (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        code varchar(50),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        unit_price float(53) not null,
        category_id bigint,
        unit_id bigint,
        primary key (id)
    )
Hibernate:
    create table menus (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table ours (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        cash_id bigint,
        contragent_id bigint,
        primary key (id)
    )
Hibernate:
    create table payment_methods (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table payrolls (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        date timestamp(6),
        cashier_id bigint,
        salary_id bigint,
        transaction_id bigint,
        primary key (id)
    )
Hibernate:
    create table projects (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table receipt (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        code varchar(100),
        comment varchar(100),
        date date,
        description varchar(100),
        quantity integer,
        total_price float(53),
        project_id bigint,
        supplier_id bigint,
        user_id bigint,
        warehouse_id bigint,
        primary key (id)
    )
Hibernate:
    create table receipt_item (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount integer,
        total_price float(53),
        unit_price float(53),
        currency_id bigint,
        material_id bigint,
        receipt_id bigint,
        unit_id bigint,
        primary key (id)
    )
Hibernate:
    create table role_actions (
        role_id bigint not null,
        action_id bigint not null
    )
Hibernate:
    create table role_menus (
        role_id bigint not null,
        menu_id bigint not null
    )
Hibernate:
    create table role_submenus (
        role_id bigint not null,
        sub_menu_id bigint not null
    )
Hibernate:
    create table roles (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(255),
        name varchar(100),
        primary key (id)
    )
Hibernate:
    create table salaries (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount float(53) not null,
        daily_rate float(53) not null,
        month varchar(255) check (month in ('JANUARY','FEBRUARY','MARCH','APRIL','MAY','JUNE','JULY','AUGUST','SEPTEMBER','OCTOBER','NOVEMBER','DECEMBER')),
        total_salary float(53) not null,
        year_month bytea,
        employee_id bigint,
        primary key (id)
    )
Hibernate:
    create table "sub-menus" (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        menu_id bigint,
        primary key (id)
    )
Hibernate:
    create table suppliers (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        city varchar(255),
        country varchar(255),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        phone varchar(255),
        region varchar(255),
        contragent_id bigint,
        primary key (id)
    )
Hibernate:
    create table transactions (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount float(53),
        comment varchar(100),
        date date,
        description varchar(300),
        exchange_rate float(53),
        is_exchange_payment boolean,
        transaction_type varchar(50) check (transaction_type in ('INCOME','EXPENSE','TRANSFER_IN','TRANSFER_OUT')),
        cash_id bigint,
        category_id bigint,
        contragent_id bigint,
        currency_id bigint,
        payment_method_id bigint,
        user_id bigint,
        primary key (id)
    )
Hibernate:
    create table unit_groups (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table units (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        is_active boolean,
        is_checked boolean,
        is_piece boolean,
        name varchar(50),
        group_id bigint,
        primary key (id)
    )
Hibernate:
    create table users (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        email varchar(255) not null,
        first_name varchar(255),
        is_active boolean,
        last_name varchar(255),
        password varchar(255),
        patronymic varchar(255),
        phone varchar(255),
        username varchar(255) not null,
        role_id bigint,
        primary key (id)
    )
Hibernate:
    create table users_actions (
        user_id bigint not null,
        action_id bigint not null
    )
Hibernate:
    create table warehouse_operations (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        date timestamp(6),
        operation_type varchar(255) check (operation_type in ('BUY','TRANSFER','RASXOD','BRAK')),
        quantity integer not null,
        reason varchar(255),
        contragent_id bigint,
        product_id bigint,
        warehouse_id bigint,
        primary key (id)
    )
Hibernate:
    create table warehouses (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table warehouses_users (
        warehouse_id bigint not null,
        users_id bigint not null
    )
Hibernate:
    create table work_types (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        barter_percent integer,
        description varchar(255),
        sum float(53) not null,
        title varchar(255),
        unit_price integer,
        currency_id bigint,
        unit_id bigint,
        primary key (id)
    )
Hibernate:
    create table workers (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(255) not null,
        contragent_id bigint,
        primary key (id)
    )
Hibernate:
    create table works (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount integer,
        barter_percent integer,
        date date,
        description varchar(255),
        sum float(53) not null,
        title varchar(255),
        unit_price integer,
        block_id bigint,
        currency_id bigint,
        project_id bigint,
        unit_id bigint,
        work_type_id bigint,
        worker_id bigint,
        primary key (id)
    )
Hibernate:
    alter table if exists attendances
       drop constraint if exists UK9uqla57ds8p87c3lr17grx506
2024-11-30T17:42:14.892+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:14.892+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk9uqla57ds8p87c3lr17grx506" of relation "attendances                          " does not exist, skipping
Hibernate:
    alter table if exists attendances
       add constraint UK9uqla57ds8p87c3lr17grx506 unique (salary_id)
Hibernate:
    alter table if exists cash_transfer
       drop constraint if exists UKr4g1kihcdqxe5nfrhj3at4bb5
2024-11-30T17:42:15.008+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.008+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukr4g1kihcdqxe5nfrhj3at4bb5" of relation "cash_transf                          er" does not exist, skipping
Hibernate:
    alter table if exists cash_transfer
       add constraint UKr4g1kihcdqxe5nfrhj3at4bb5 unique (couple_id)
Hibernate:
    alter table if exists cashes
       drop constraint if exists UKp76dfw9wf1v5civobd0nrfvau
2024-11-30T17:42:15.066+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.067+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukp76dfw9wf1v5civobd0nrfvau" of relation "cashes" doe                          s not exist, skipping
Hibernate:
    alter table if exists cashes
       add constraint UKp76dfw9wf1v5civobd0nrfvau unique (project_id)
Hibernate:
    alter table if exists employees
       drop constraint if exists UKho19fq2q6i0pp9ict57mlfsyn
2024-11-30T17:42:15.189+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.189+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukho19fq2q6i0pp9ict57mlfsyn" of relation "employees"                           does not exist, skipping
Hibernate:
    alter table if exists employees
       add constraint UKho19fq2q6i0pp9ict57mlfsyn unique (contragent_id)
Hibernate:
    alter table if exists ours
       drop constraint if exists UKdt25cl4y7fixg01mlkuwebxue
2024-11-30T17:42:15.258+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.258+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukdt25cl4y7fixg01mlkuwebxue" of relation "ours" does                           not exist, skipping
Hibernate:
    alter table if exists ours
       add constraint UKdt25cl4y7fixg01mlkuwebxue unique (cash_id)
Hibernate:
    alter table if exists ours
       drop constraint if exists UKq8o67l8k9b1fcc8om4aw154b6
2024-11-30T17:42:15.400+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.401+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukq8o67l8k9b1fcc8om4aw154b6" of relation "ours" does                           not exist, skipping
Hibernate:
    alter table if exists ours
       add constraint UKq8o67l8k9b1fcc8om4aw154b6 unique (contragent_id)
Hibernate:
    alter table if exists payrolls
       drop constraint if exists UK2k5xn41xno2n4m746y15toyhn
2024-11-30T17:42:15.466+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.467+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk2k5xn41xno2n4m746y15toyhn" of relation "payrolls" d                          oes not exist, skipping
Hibernate:
    alter table if exists payrolls
       add constraint UK2k5xn41xno2n4m746y15toyhn unique (cashier_id)
Hibernate:
    alter table if exists payrolls
       drop constraint if exists UKbx1q65g83chdun7omr5u166li
2024-11-30T17:42:15.533+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.533+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukbx1q65g83chdun7omr5u166li" of relation "payrolls" d                          oes not exist, skipping
Hibernate:
    alter table if exists payrolls
       add constraint UKbx1q65g83chdun7omr5u166li unique (transaction_id)
Hibernate:
    alter table if exists roles
       drop constraint if exists UK2op45rew8nnd6adyi86qeqk50
2024-11-30T17:42:15.658+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.659+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk2op45rew8nnd6adyi86qeqk50" of relation "roles" does                           not exist, skipping
Hibernate:
    alter table if exists roles
       add constraint UK2op45rew8nnd6adyi86qeqk50 unique (description)
Hibernate:
    alter table if exists roles
       drop constraint if exists UKofx66keruapi6vyqpv6f2or37
2024-11-30T17:42:15.733+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.734+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukofx66keruapi6vyqpv6f2or37" of relation "roles" does                           not exist, skipping
Hibernate:
    alter table if exists roles
       add constraint UKofx66keruapi6vyqpv6f2or37 unique (name)
Hibernate:
    alter table if exists suppliers
       drop constraint if exists UKkvvm4jgvhg80jracbiyj3cw3g
2024-11-30T17:42:15.847+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.847+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukkvvm4jgvhg80jracbiyj3cw3g" of relation "suppliers"                           does not exist, skipping
Hibernate:
    alter table if exists suppliers
       add constraint UKkvvm4jgvhg80jracbiyj3cw3g unique (contragent_id)
Hibernate:
    alter table if exists users
       drop constraint if exists UK6dotkott2kjsp8vw4d0m25fb7
2024-11-30T17:42:15.908+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:15.908+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk6dotkott2kjsp8vw4d0m25fb7" of relation "users" does                           not exist, skipping
Hibernate:
    alter table if exists users
       add constraint UK6dotkott2kjsp8vw4d0m25fb7 unique (email)
Hibernate:
    alter table if exists users
       drop constraint if exists UKr43af9ap4edm43mmtq01oddj6
2024-11-30T17:42:16.041+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:16.042+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukr43af9ap4edm43mmtq01oddj6" of relation "users" does                           not exist, skipping
Hibernate:
    alter table if exists users
       add constraint UKr43af9ap4edm43mmtq01oddj6 unique (username)
Hibernate:
    alter table if exists warehouses
       drop constraint if exists UKsbr93wopoiv4vddj3tovg0h22
2024-11-30T17:42:16.100+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:16.100+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uksbr93wopoiv4vddj3tovg0h22" of relation "warehouses"                           does not exist, skipping
Hibernate:
    alter table if exists warehouses
       add constraint UKsbr93wopoiv4vddj3tovg0h22 unique (project_id)
Hibernate:
    alter table if exists warehouses_users
       drop constraint if exists UKaqi3e2i6gmuvpfeehg1dqc4ie
2024-11-30T17:42:16.208+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:16.209+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukaqi3e2i6gmuvpfeehg1dqc4ie" of relation "warehouses_                          users" does not exist, skipping
Hibernate:
    alter table if exists warehouses_users
       add constraint UKaqi3e2i6gmuvpfeehg1dqc4ie unique (users_id)
Hibernate:
    alter table if exists workers
       drop constraint if exists UKc1jotu7v5buv6dh7m1vm146mh
2024-11-30T17:42:16.275+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:16.275+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukc1jotu7v5buv6dh7m1vm146mh" of relation "workers" do                          es not exist, skipping
Hibernate:
    alter table if exists workers
       add constraint UKc1jotu7v5buv6dh7m1vm146mh unique (name)
Hibernate:
    alter table if exists workers
       drop constraint if exists UKckobiucr0dustyha168ybkybx
2024-11-30T17:42:16.333+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:42:16.333+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukckobiucr0dustyha168ybkybx" of relation "workers" do                          es not exist, skipping
Hibernate:
    alter table if exists workers
       add constraint UKckobiucr0dustyha168ybkybx unique (contragent_id)
Hibernate:
    alter table if exists actions
       add constraint FKkd5p89q8rsly0mt87hxkma30e
       foreign key ("sub-menu-id")
       references "sub-menus"
Hibernate:
    alter table if exists attendances
       add constraint FK7f87sy697hma8gq2f0qo3clw4
       foreign key (salary_id)
       references salaries
Hibernate:
    alter table if exists blocks
       add constraint FKaosgy5ytw4k6itrwxojh50wkl
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists calendar_dates
       add constraint FKmxdk25v8ypm01lybi7usaef0t
       foreign key (attendance_id)
       references attendances
Hibernate:
    alter table if exists cash_transfer
       add constraint FKdfifo0rid3cs0kfj7kfvl2cc3
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists cash_transfer
       add constraint FKp328unibs5t1p0bj8ub1akpuj
       foreign key (category_id)
       references categories
Hibernate:
    alter table if exists cash_transfer
       add constraint FKhnbbtg6hbqt2p8hrtv8hx0jl8
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists cash_transfer
       add constraint FKqic1830fvdeljrc9jvhwxnrlb
       foreign key (couple_id)
       references cash_transfer
Hibernate:
    alter table if exists cash_transfer
       add constraint FKcl4i1suneb71mwtiivym8dpu7
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists cash_transfer
       add constraint FKinha5tf37mj9rvkwvf90bexs3
       foreign key (payment_method_id)
       references payment_methods
Hibernate:
    alter table if exists cash_transfer
       add constraint FKi8fvoi77949l13vds7be69d32
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists cash_users
       add constraint FKk5qdaa801v8rawi5fgu4g2gb2
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists cash_users
       add constraint FKoqemugcbs608n2vcs9fv6df1b
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists cashes
       add constraint FKacgm578496dexs369ah8yfa92
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists departments
       add constraint FKae8h4nwnqpfcr5078n17b0lgo
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists employees
       add constraint FKk9gb9t00aafpxlnj1c5f8p3mq
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists employees
       add constraint FKgy4qe3dnqrm3ktd76sxp7n4c2
       foreign key (department_id)
       references departments
Hibernate:
    alter table if exists employees
       add constraint FKgawtrwvxw4uu0ppt5h8w5go
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists exceptions_log
       add constraint FKevy41sy5yn6m9bo46lwhbtxfu
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists materials
       add constraint FKmknh0urg319ho0gysamyymqu1
       foreign key (category_id)
       references material_categories
Hibernate:
    alter table if exists materials
       add constraint FKg5md9qacf6ygyn3e4kje520jb
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists ours
       add constraint FKn5qrkl2yp5qglvlwxuwn1568g
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists ours
       add constraint FKmea8wtb9ngp0lbb2ys85un9hi
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists payrolls
       add constraint FK9c6eobekwp3xid6a47fiiqlad
       foreign key (cashier_id)
       references users
Hibernate:
    alter table if exists payrolls
       add constraint FKpwns56h96myk8agf1wyeeehna
       foreign key (salary_id)
       references salaries
Hibernate:
    alter table if exists payrolls
       add constraint FKbgga2c4a5q28olvop4nv75tq4
       foreign key (transaction_id)
       references transactions
Hibernate:
    alter table if exists receipt
       add constraint FKf00gy6ei09qby0kpsjcu71ho0
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists receipt
       add constraint FKcw8tpu3mls155d4rxfe0wdqj8
       foreign key (supplier_id)
       references suppliers
Hibernate:
    alter table if exists receipt
       add constraint FK9llbb4mj9qe5l0krj2ro35u51
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists receipt
       add constraint FKoph7vxqnol9dqc6m8n8vpkgo
       foreign key (warehouse_id)
       references warehouses
Hibernate:
    alter table if exists receipt_item
       add constraint FKkhkp2ftva7u0qx4kg3d155orp
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists receipt_item
       add constraint FKnbwpfcho1gi58cd8xqo6d6t9i
       foreign key (material_id)
       references materials
Hibernate:
    alter table if exists receipt_item
       add constraint FKsohgmt8ntavcgj10ha2duc8la
       foreign key (receipt_id)
       references receipt
Hibernate:
    alter table if exists receipt_item
       add constraint FK5riommiv7t27rc8ntqe0brc8x
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists role_actions
       add constraint FK4581swvrx51fb6xess0vrouyf
       foreign key (action_id)
       references actions
Hibernate:
    alter table if exists role_actions
       add constraint FKiqm6ohr1ks84kwg1fungt6pmp
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists role_menus
       add constraint FKo7blfgcetl84km46ayoybmkvm
       foreign key (menu_id)
       references menus
Hibernate:
    alter table if exists role_menus
       add constraint FK8w16n9supii3exa5gnfdey3vu
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists role_submenus
       add constraint FKxnuiglsoer0r7gq3vbb8tq4q
       foreign key (sub_menu_id)
       references "sub-menus"
Hibernate:
    alter table if exists role_submenus
       add constraint FKkojsnj5gf3d3y83er605jofrd
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists salaries
       add constraint FK1utmvufusgyktdtbmo4xfas10
       foreign key (employee_id)
       references employees
Hibernate:
    alter table if exists "sub-menus"
       add constraint FKnq4jqab43ibxovnjjcun1rl2r
       foreign key (menu_id)
       references menus
Hibernate:
    alter table if exists suppliers
       add constraint FKsdk7mg1sxh3phs6jbwq973fg7
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists transactions
       add constraint FK3xjphv8luajr16jpm3ikypv3k
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists transactions
       add constraint FKsqqi7sneo04kast0o138h19mv
       foreign key (category_id)
       references categories
Hibernate:
    alter table if exists transactions
       add constraint FK73dgh9kq6sqey6up4507k5xwb
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists transactions
       add constraint FK812edr8o27pte306gvbmypytx
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists transactions
       add constraint FK566q0xeai5k115ya39d776f3w
       foreign key (payment_method_id)
       references payment_methods
Hibernate:
    alter table if exists transactions
       add constraint FKqwv7rmvc8va8rep7piikrojds
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists units
       add constraint FKbp8ca2wue8clkqsfsxc1bpvfr
       foreign key (group_id)
       references unit_groups
Hibernate:
    alter table if exists users
       add constraint FKp56c1712k691lhsyewcssf40f
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists users_actions
       add constraint FKn2nrr0jotbch4dc0xe9y02ryd
       foreign key (action_id)
       references actions
Hibernate:
    alter table if exists users_actions
       add constraint FKf469hk2si31ox0ly8v81lbmys
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists warehouse_operations
       add constraint FKja79uhrw7hxwklj2u3f3002vw
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists warehouse_operations
       add constraint FK8cat5e6dfmqrdncuwxw62mw
       foreign key (product_id)
       references materials
Hibernate:
    alter table if exists warehouse_operations
       add constraint FKervq6jvj70oe7lg17fw1w33f0
       foreign key (warehouse_id)
       references warehouses
Hibernate:
    alter table if exists warehouses
       add constraint FK49wpwtmstd4xidmnuux0a1cjp
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists warehouses_users
       add constraint FKn3ilqebpig3mqaxqqjx99p41e
       foreign key (users_id)
       references users
Hibernate:
    alter table if exists warehouses_users
       add constraint FKqn8wea4lk2l9yiawuxlc5mt82
       foreign key (warehouse_id)
       references warehouses
Hibernate:
    alter table if exists work_types
       add constraint FKdmiqyvtldl8t82rmch3i3v3lp
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists work_types
       add constraint FKsyg6v8jeoql6cvqvs9o7h7ev4
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists workers
       add constraint FKagsd3git2vs5coeevvct2x0mi
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists works
       add constraint FK3qscfr9kh0siyx5gnt2wx9rb0
       foreign key (block_id)
       references blocks
Hibernate:
    alter table if exists works
       add constraint FKq2bgpd0wdsxg10e9oje9hv9mn
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists works
       add constraint FKlcit1y5qreemmsiwghc2b2o8k
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists works
       add constraint FKmwhy8mm74j7cw4t8fc9g6ovft
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists works
       add constraint FKq6fv1dvvc98iyvouvvsvlxx2g
       foreign key (work_type_id)
       references work_types
Hibernate:
    alter table if exists works
       add constraint FKjr4h8vtlv5r2litq2qhno5ri1
       foreign key (worker_id)
       references workers
2024-11-30T17:42:17.030+05:00  INFO 1 --- [txtgroup] [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'defaul                          t'
2024-11-30T17:42:17.171+05:00  INFO 1 --- [txtgroup] [           main] o.s.d.j.r.query.QueryEnhancerFactory     : Hibernate is in classpath; If applicable, HQL parser will be used                          .
2024-11-30T17:42:17.489+05:00  INFO 1 --- [txtgroup] [           main] r$InitializeUserDetailsManagerConfigurer : Global AuthenticationManager configured with UserDetailsService b                          ean with name userDetailsServiceImpl
2024-11-30T17:42:17.543+05:00  WARN 1 --- [txtgroup] [           main] JpaBaseConfiguration$JpaWebConfiguration : spring.jpa.open-in-view is enabled by default. Therefore, databas                          e queries may be performed during view rendering. Explicitly configure spring.jpa.open-in-view to disable this warning
2024-11-30T17:42:17.821+05:00  INFO 1 --- [txtgroup] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port 8080 (http) with context path '/'
2024-11-30T17:42:17.826+05:00  INFO 1 --- [txtgroup] [           main] uz.txtgroup.Application                  : Started Application in 9.106 seconds (process running for 9.337)
2024-11-30T17:42:17.874+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select r1_0.id,r1_0.creat                          ed_date,r1_0.description,r1_0.name,r1_0.updated_date from roles r1_0
Hibernate:
    select
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date
    from
        roles r1_0
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
2024-11-30T17:42:18.068+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select r1_0.id,r1_0.creat                          ed_date,r1_0.description,r1_0.name,r1_0.updated_date from roles r1_0
Hibernate:
    select
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date
    from
        roles r1_0
2024-11-30T17:42:18.124+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select u1_0.id,u1_0.creat                          ed_date,u1_0.email,u1_0.first_name,u1_0.is_active,u1_0.last_name,u1_0.password,u1_0.patronymic,u1_0.phone,r1_0.id,r1_0.created_date,r1_0.description,r1_0.name,r1_0.updated_date,u1                          _0.updated_date,u1_0.username from users u1_0 left join roles r1_0 on r1_0.id=u1_0.role_id where u1_0.email=?
Hibernate:
    select
        u1_0.id,
        u1_0.created_date,
        u1_0.email,
        u1_0.first_name,
        u1_0.is_active,
        u1_0.last_name,
        u1_0.password,
        u1_0.patronymic,
        u1_0.phone,
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date,
        u1_0.updated_date,
        u1_0.username
    from
        users u1_0
    left join
        roles r1_0
            on r1_0.id=u1_0.role_id
    where
        u1_0.email=?
2024-11-30T17:42:18.127+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select u1_0.id,u1_0.creat                          ed_date,u1_0.email,u1_0.first_name,u1_0.is_active,u1_0.last_name,u1_0.password,u1_0.patronymic,u1_0.phone,r1_0.id,r1_0.created_date,r1_0.description,r1_0.name,r1_0.updated_date,u1                          _0.updated_date,u1_0.username from users u1_0 left join roles r1_0 on r1_0.id=u1_0.role_id where u1_0.email=?
Hibernate:
    select
        u1_0.id,
        u1_0.created_date,
        u1_0.email,
        u1_0.first_name,
        u1_0.is_active,
        u1_0.last_name,
        u1_0.password,
        u1_0.patronymic,
        u1_0.phone,
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date,
        u1_0.updated_date,
        u1_0.username
    from
        users u1_0
    left join
        roles r1_0
            on r1_0.id=u1_0.role_id
    where
        u1_0.email=?
2024-11-30T17:42:18.128+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select u1_0.id,u1_0.creat                          ed_date,u1_0.email,u1_0.first_name,u1_0.is_active,u1_0.last_name,u1_0.password,u1_0.patronymic,u1_0.phone,r1_0.id,r1_0.created_date,r1_0.description,r1_0.name,r1_0.updated_date,u1                          _0.updated_date,u1_0.username from users u1_0 left join roles r1_0 on r1_0.id=u1_0.role_id where u1_0.email=?
Hibernate:
    select
        u1_0.id,
        u1_0.created_date,
        u1_0.email,
        u1_0.first_name,
        u1_0.is_active,
        u1_0.last_name,
        u1_0.password,
        u1_0.patronymic,
        u1_0.phone,
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date,
        u1_0.updated_date,
        u1_0.username
    from
        users u1_0
    left join
        roles r1_0
            on r1_0.id=u1_0.role_id
    where
        u1_0.email=?
Hibernate:
    insert
    into
        users
        (created_date, email, first_name, is_active, last_name, password, patronymic, phone, role_id, updated_date, username)
    values
        (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        users
        (created_date, email, first_name, is_active, last_name, password, patronymic, phone, role_id, updated_date, username)
    values
        (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        users
        (created_date, email, first_name, is_active, last_name, password, patronymic, phone, role_id, updated_date, username)
    values
        (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)
    returning id
2024-11-30T17:42:18.308+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select c1_0.id,c1_0.creat                          ed_date,c1_0.is_active,c1_0.name,c1_0.updated_date from currencies c1_0 where c1_0.name=?
Hibernate:
    select
        c1_0.id,
        c1_0.created_date,
        c1_0.is_active,
        c1_0.name,
        c1_0.updated_date
    from
        currencies c1_0
    where
        c1_0.name=?
2024-11-30T17:42:18.309+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select c1_0.id,c1_0.creat                          ed_date,c1_0.name,c1_0.type,c1_0.updated_date from contragents c1_0 where c1_0.type=?
Hibernate:
    select
        c1_0.id,
        c1_0.created_date,
        c1_0.name,
        c1_0.type,
        c1_0.updated_date
    from
        contragents c1_0
    where
        c1_0.type=?
2024-11-30T17:42:18.310+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select c1_0.id,c1_0.creat                          ed_date,c1_0.description,c1_0.is_active,c1_0.name,c1_0.updated_date from categories c1_0 where c1_0.name=?
Hibernate:
    select
        c1_0.id,
        c1_0.created_date,
        c1_0.description,
        c1_0.is_active,
        c1_0.name,
        c1_0.updated_date
    from
        categories c1_0
    where
        c1_0.name=?
2024-11-30T17:42:18.312+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select pm1_0.id,pm1_0.cre                          ated_date,pm1_0.description,pm1_0.is_active,pm1_0.name,pm1_0.updated_date from payment_methods pm1_0 where pm1_0.name=?
Hibernate:
    select
        pm1_0.id,
        pm1_0.created_date,
        pm1_0.description,
        pm1_0.is_active,
        pm1_0.name,
        pm1_0.updated_date
    from
        payment_methods pm1_0
    where
        pm1_0.name=?
Hibernate:
    insert
    into
        payment_methods
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        payment_methods
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        currencies
        (created_date, is_active, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        currencies
        (created_date, is_active, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        contragents
        (created_date, name, type, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        contragents
        (created_date, name, type, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        categories
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        categories
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
2024-11-30T17:47:20.212+05:00  INFO 1 --- [txtgroup] [ionShutdownHook] j.LocalContainerEntityManagerFactoryBean : Closing JPA EntityManagerFactory for persistence unit 'default'
2024-11-30T17:47:20.213+05:00  INFO 1 --- [txtgroup] [ionShutdownHook] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown initiated...
2024-11-30T17:47:20.215+05:00  INFO 1 --- [txtgroup] [ionShutdownHook] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown completed.
2024-11-30T17:49:51.290+05:00  INFO 1 --- [txtgroup] [           main] uz.txtgroup.Application                  : Starting Application v0.0.1-SNAPSHOT using Java 17.0.2 with PID 1                           (/app/app.jar started by root in /app)
2024-11-30T17:49:51.292+05:00  INFO 1 --- [txtgroup] [           main] uz.txtgroup.Application                  : The following 1 profile is active: "dev"
2024-11-30T17:49:51.656+05:00  INFO 1 --- [txtgroup] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2024-11-30T17:49:51.713+05:00  INFO 1 --- [txtgroup] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 52 ms. Found 23 JPA r                          epository interfaces.
2024-11-30T17:49:52.033+05:00  INFO 1 --- [txtgroup] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2024-11-30T17:49:52.040+05:00  INFO 1 --- [txtgroup] [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2024-11-30T17:49:52.040+05:00  INFO 1 --- [txtgroup] [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.31]
2024-11-30T17:49:52.059+05:00  INFO 1 --- [txtgroup] [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2024-11-30T17:49:52.059+05:00  INFO 1 --- [txtgroup] [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 746 ms
2024-11-30T17:49:52.301+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Reading resource: db/scripts/001-exceptions_log.sql
2024-11-30T17:49:52.325+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Creating database history table with name: public.databasechangel                          og
2024-11-30T17:49:52.379+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Reading from public.databasechangelog
2024-11-30T17:49:52.409+05:00  INFO 1 --- [txtgroup] [           main] liquibase.lockservice                    : Successfully acquired change log lock
2024-11-30T17:49:52.410+05:00  INFO 1 --- [txtgroup] [           main] liquibase.command                        : Using deploymentId: 2970992410
2024-11-30T17:49:52.411+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Reading from public.databasechangelog
2024-11-30T17:49:52.431+05:00  INFO 1 --- [txtgroup] [           main] liquibase.ui                             : Running Changeset: db/scripts/001-exceptions_log.sql::001::Kamoli                          ddin
2024-11-30T17:49:52.443+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : Custom SQL executed
2024-11-30T17:49:52.445+05:00  INFO 1 --- [txtgroup] [           main] liquibase.changelog                      : ChangeSet db/scripts/001-exceptions_log.sql::001::Kamoliddin ran                           successfully in 14ms
2024-11-30T17:49:52.450+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : UPDATE SUMMARY
2024-11-30T17:49:52.450+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Run:                          1
2024-11-30T17:49:52.450+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Previously run:               0
2024-11-30T17:49:52.450+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Filtered out:                 0
2024-11-30T17:49:52.450+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : -------------------------------
2024-11-30T17:49:52.450+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Total change sets:            1
2024-11-30T17:49:52.450+05:00  INFO 1 --- [txtgroup] [           main] liquibase.util                           : Update summary generated
2024-11-30T17:49:52.451+05:00  INFO 1 --- [txtgroup] [           main] liquibase.command                        : Update command completed successfully.
2024-11-30T17:49:52.451+05:00  INFO 1 --- [txtgroup] [           main] liquibase.ui                             : Liquibase: Update has been successful. Rows affected: 1
2024-11-30T17:49:52.453+05:00  INFO 1 --- [txtgroup] [           main] liquibase.lockservice                    : Successfully released change log lock
2024-11-30T17:49:52.453+05:00  INFO 1 --- [txtgroup] [           main] liquibase.command                        : Command execution complete
2024-11-30T17:49:52.485+05:00  INFO 1 --- [txtgroup] [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2024-11-30T17:49:52.508+05:00  INFO 1 --- [txtgroup] [           main] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 6.5.3.Final
2024-11-30T17:49:52.523+05:00  INFO 1 --- [txtgroup] [           main] o.h.c.internal.RegionFactoryInitiator    : HHH000026: Second-level cache disabled
2024-11-30T17:49:52.634+05:00  INFO 1 --- [txtgroup] [           main] o.s.o.j.p.SpringPersistenceUnitInfo      : No LoadTimeWeaver setup: ignoring JPA class transformer
2024-11-30T17:49:52.645+05:00  INFO 1 --- [txtgroup] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2024-11-30T17:49:52.657+05:00  INFO 1 --- [txtgroup] [           main] com.zaxxer.hikari.pool.HikariPool        : HikariPool-1 - Added connection org.postgresql.jdbc.PgConnection@                          577cf459
2024-11-30T17:49:52.658+05:00  INFO 1 --- [txtgroup] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2024-11-30T17:49:52.676+05:00  WARN 1 --- [txtgroup] [           main] org.hibernate.orm.deprecation            : HHH90000025: PostgreSQLDialect does not need to be specified expl                          icitly using 'hibernate.dialect' (remove the property setting and it will be selected by default)
2024-11-30T17:49:53.288+05:00  INFO 1 --- [txtgroup] [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000489: No JTA platform available (set 'hibernate.transaction.                          jta.platform' to enable JTA platform integration)
Hibernate:
    create table actions (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        path varchar(255),
        "sub-menu-id" bigint,
        primary key (id)
    )
Hibernate:
    create table attendances (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        total_working_days_in_month integer not null,
        salary_id bigint,
        primary key (id)
    )
Hibernate:
    create table blocks (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(50),
        title varchar(50),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table calendar_dates (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        attendance_rate float(53) not null,
        date date,
        attendance_id bigint,
        primary key (id)
    )
Hibernate:
    create table cash_transfer (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount float(53),
        comment varchar(100),
        date date,
        description varchar(100),
        exchange_rate float(53),
        is_completed boolean,
        is_declined boolean,
        is_exchange_payment boolean,
        transaction_type varchar(50) check (transaction_type in ('INCOME','EXPENSE','TRANSFER_IN','TRANSFER_OUT')),
        cash_id bigint,
        category_id bigint,
        contragent_id bigint,
        couple_id bigint,
        currency_id bigint,
        payment_method_id bigint,
        user_id bigint,
        primary key (id)
    )
Hibernate:
    create table cash_users (
        cash_id bigint not null,
        user_id bigint not null
    )
Hibernate:
    create table cashes (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table categories (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table contragents (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        type varchar(255) check (type in ('SUPPLIER','WORKER','EMPLOYEE','CASH','INVESTOR','BANK')),
        primary key (id)
    )
Hibernate:
    create table currencies (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table departments (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(255),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table employees (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        contragent_id bigint,
        department_id bigint,
        project_id bigint,
        primary key (id)
    )
Hibernate:
    alter table if exists exceptions_log
       alter column exception_text set data type TEXT
Hibernate:
    alter table if exists exceptions_log
       alter column message set data type TEXT
Hibernate:
    create table material_categories (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table materials (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        code varchar(50),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        unit_price float(53) not null,
        category_id bigint,
        unit_id bigint,
        primary key (id)
    )
Hibernate:
    create table menus (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table ours (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        cash_id bigint,
        contragent_id bigint,
        primary key (id)
    )
Hibernate:
    create table payment_methods (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table payrolls (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        date timestamp(6),
        cashier_id bigint,
        salary_id bigint,
        transaction_id bigint,
        primary key (id)
    )
Hibernate:
    create table projects (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table receipt (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        code varchar(100),
        comment varchar(100),
        date date,
        description varchar(100),
        quantity integer,
        total_price float(53),
        project_id bigint,
        supplier_id bigint,
        user_id bigint,
        warehouse_id bigint,
        primary key (id)
    )
Hibernate:
    create table receipt_item (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount integer,
        total_price float(53),
        unit_price float(53),
        currency_id bigint,
        material_id bigint,
        receipt_id bigint,
        unit_id bigint,
        primary key (id)
    )
Hibernate:
    create table role_actions (
        role_id bigint not null,
        action_id bigint not null
    )
Hibernate:
    create table role_menus (
        role_id bigint not null,
        menu_id bigint not null
    )
Hibernate:
    create table role_submenus (
        role_id bigint not null,
        sub_menu_id bigint not null
    )
Hibernate:
    create table roles (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        description varchar(255),
        name varchar(100),
        primary key (id)
    )
Hibernate:
    create table salaries (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount float(53) not null,
        daily_rate float(53) not null,
        month varchar(255) check (month in ('JANUARY','FEBRUARY','MARCH','APRIL','MAY','JUNE','JULY','AUGUST','SEPTEMBER','OCTOBER','NOVEMBER','DECEMBER')),
        total_salary float(53) not null,
        year_month bytea,
        employee_id bigint,
        primary key (id)
    )
Hibernate:
    create table "sub-menus" (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        menu_id bigint,
        primary key (id)
    )
Hibernate:
    create table suppliers (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        city varchar(255),
        country varchar(255),
        description varchar(100),
        is_active boolean,
        name varchar(50),
        phone varchar(255),
        region varchar(255),
        contragent_id bigint,
        primary key (id)
    )
Hibernate:
    create table transactions (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount float(53),
        comment varchar(100),
        date date,
        description varchar(300),
        exchange_rate float(53),
        is_exchange_payment boolean,
        transaction_type varchar(50) check (transaction_type in ('INCOME','EXPENSE','TRANSFER_IN','TRANSFER_OUT')),
        cash_id bigint,
        category_id bigint,
        contragent_id bigint,
        currency_id bigint,
        payment_method_id bigint,
        user_id bigint,
        primary key (id)
    )
Hibernate:
    create table unit_groups (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        is_active boolean,
        name varchar(50),
        primary key (id)
    )
Hibernate:
    create table units (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        is_active boolean,
        is_checked boolean,
        is_piece boolean,
        name varchar(50),
        group_id bigint,
        primary key (id)
    )
Hibernate:
    create table users (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        email varchar(255) not null,
        first_name varchar(255),
        is_active boolean,
        last_name varchar(255),
        password varchar(255),
        patronymic varchar(255),
        phone varchar(255),
        username varchar(255) not null,
        role_id bigint,
        primary key (id)
    )
Hibernate:
    create table users_actions (
        user_id bigint not null,
        action_id bigint not null
    )
Hibernate:
    create table warehouse_operations (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        date timestamp(6),
        operation_type varchar(255) check (operation_type in ('BUY','TRANSFER','RASXOD','BRAK')),
        quantity integer not null,
        reason varchar(255),
        contragent_id bigint,
        product_id bigint,
        warehouse_id bigint,
        primary key (id)
    )
Hibernate:
    create table warehouses (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(50),
        project_id bigint,
        primary key (id)
    )
Hibernate:
    create table warehouses_users (
        warehouse_id bigint not null,
        users_id bigint not null
    )
Hibernate:
    create table work_types (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        barter_percent integer,
        description varchar(255),
        sum float(53) not null,
        title varchar(255),
        unit_price integer,
        currency_id bigint,
        unit_id bigint,
        primary key (id)
    )
Hibernate:
    create table workers (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        name varchar(255) not null,
        contragent_id bigint,
        primary key (id)
    )
Hibernate:
    create table works (
        id bigint generated by default as identity,
        created_date timestamp(6),
        updated_date timestamp(6),
        amount integer,
        barter_percent integer,
        date date,
        description varchar(255),
        sum float(53) not null,
        title varchar(255),
        unit_price integer,
        block_id bigint,
        currency_id bigint,
        project_id bigint,
        unit_id bigint,
        work_type_id bigint,
        worker_id bigint,
        primary key (id)
    )
Hibernate:
    alter table if exists attendances
       drop constraint if exists UK9uqla57ds8p87c3lr17grx506
2024-11-30T17:49:53.451+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.451+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk9uqla57ds8p87c3lr17grx506" of relation "attendances                          " does not exist, skipping
Hibernate:
    alter table if exists attendances
       add constraint UK9uqla57ds8p87c3lr17grx506 unique (salary_id)
Hibernate:
    alter table if exists cash_transfer
       drop constraint if exists UKr4g1kihcdqxe5nfrhj3at4bb5
2024-11-30T17:49:53.458+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.458+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukr4g1kihcdqxe5nfrhj3at4bb5" of relation "cash_transf                          er" does not exist, skipping
Hibernate:
    alter table if exists cash_transfer
       add constraint UKr4g1kihcdqxe5nfrhj3at4bb5 unique (couple_id)
Hibernate:
    alter table if exists cashes
       drop constraint if exists UKp76dfw9wf1v5civobd0nrfvau
2024-11-30T17:49:53.464+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.465+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukp76dfw9wf1v5civobd0nrfvau" of relation "cashes" doe                          s not exist, skipping
Hibernate:
    alter table if exists cashes
       add constraint UKp76dfw9wf1v5civobd0nrfvau unique (project_id)
Hibernate:
    alter table if exists employees
       drop constraint if exists UKho19fq2q6i0pp9ict57mlfsyn
2024-11-30T17:49:53.471+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.471+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukho19fq2q6i0pp9ict57mlfsyn" of relation "employees"                           does not exist, skipping
Hibernate:
    alter table if exists employees
       add constraint UKho19fq2q6i0pp9ict57mlfsyn unique (contragent_id)
Hibernate:
    alter table if exists ours
       drop constraint if exists UKdt25cl4y7fixg01mlkuwebxue
2024-11-30T17:49:53.477+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.477+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukdt25cl4y7fixg01mlkuwebxue" of relation "ours" does                           not exist, skipping
Hibernate:
    alter table if exists ours
       add constraint UKdt25cl4y7fixg01mlkuwebxue unique (cash_id)
Hibernate:
    alter table if exists ours
       drop constraint if exists UKq8o67l8k9b1fcc8om4aw154b6
2024-11-30T17:49:53.485+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.485+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukq8o67l8k9b1fcc8om4aw154b6" of relation "ours" does                           not exist, skipping
Hibernate:
    alter table if exists ours
       add constraint UKq8o67l8k9b1fcc8om4aw154b6 unique (contragent_id)
Hibernate:
    alter table if exists payrolls
       drop constraint if exists UK2k5xn41xno2n4m746y15toyhn
2024-11-30T17:49:53.492+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.492+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk2k5xn41xno2n4m746y15toyhn" of relation "payrolls" d                          oes not exist, skipping
Hibernate:
    alter table if exists payrolls
       add constraint UK2k5xn41xno2n4m746y15toyhn unique (cashier_id)
Hibernate:
    alter table if exists payrolls
       drop constraint if exists UKbx1q65g83chdun7omr5u166li
2024-11-30T17:49:53.498+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.499+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukbx1q65g83chdun7omr5u166li" of relation "payrolls" d                          oes not exist, skipping
Hibernate:
    alter table if exists payrolls
       add constraint UKbx1q65g83chdun7omr5u166li unique (transaction_id)
Hibernate:
    alter table if exists roles
       drop constraint if exists UK2op45rew8nnd6adyi86qeqk50
2024-11-30T17:49:53.504+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.505+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk2op45rew8nnd6adyi86qeqk50" of relation "roles" does                           not exist, skipping
Hibernate:
    alter table if exists roles
       add constraint UK2op45rew8nnd6adyi86qeqk50 unique (description)
Hibernate:
    alter table if exists roles
       drop constraint if exists UKofx66keruapi6vyqpv6f2or37
2024-11-30T17:49:53.510+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.510+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukofx66keruapi6vyqpv6f2or37" of relation "roles" does                           not exist, skipping
Hibernate:
    alter table if exists roles
       add constraint UKofx66keruapi6vyqpv6f2or37 unique (name)
Hibernate:
    alter table if exists suppliers
       drop constraint if exists UKkvvm4jgvhg80jracbiyj3cw3g
2024-11-30T17:49:53.515+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.516+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukkvvm4jgvhg80jracbiyj3cw3g" of relation "suppliers"                           does not exist, skipping
Hibernate:
    alter table if exists suppliers
       add constraint UKkvvm4jgvhg80jracbiyj3cw3g unique (contragent_id)
Hibernate:
    alter table if exists users
       drop constraint if exists UK6dotkott2kjsp8vw4d0m25fb7
2024-11-30T17:49:53.521+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.522+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uk6dotkott2kjsp8vw4d0m25fb7" of relation "users" does                           not exist, skipping
Hibernate:
    alter table if exists users
       add constraint UK6dotkott2kjsp8vw4d0m25fb7 unique (email)
Hibernate:
    alter table if exists users
       drop constraint if exists UKr43af9ap4edm43mmtq01oddj6
2024-11-30T17:49:53.527+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.527+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukr43af9ap4edm43mmtq01oddj6" of relation "users" does                           not exist, skipping
Hibernate:
    alter table if exists users
       add constraint UKr43af9ap4edm43mmtq01oddj6 unique (username)
Hibernate:
    alter table if exists warehouses
       drop constraint if exists UKsbr93wopoiv4vddj3tovg0h22
2024-11-30T17:49:53.533+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.533+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "uksbr93wopoiv4vddj3tovg0h22" of relation "warehouses"                           does not exist, skipping
Hibernate:
    alter table if exists warehouses
       add constraint UKsbr93wopoiv4vddj3tovg0h22 unique (project_id)
Hibernate:
    alter table if exists warehouses_users
       drop constraint if exists UKaqi3e2i6gmuvpfeehg1dqc4ie
2024-11-30T17:49:53.538+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.539+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukaqi3e2i6gmuvpfeehg1dqc4ie" of relation "warehouses_                          users" does not exist, skipping
Hibernate:
    alter table if exists warehouses_users
       add constraint UKaqi3e2i6gmuvpfeehg1dqc4ie unique (users_id)
Hibernate:
    alter table if exists workers
       drop constraint if exists UKc1jotu7v5buv6dh7m1vm146mh
2024-11-30T17:49:53.544+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.545+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukc1jotu7v5buv6dh7m1vm146mh" of relation "workers" do                          es not exist, skipping
Hibernate:
    alter table if exists workers
       add constraint UKc1jotu7v5buv6dh7m1vm146mh unique (name)
Hibernate:
    alter table if exists workers
       drop constraint if exists UKckobiucr0dustyha168ybkybx
2024-11-30T17:49:53.550+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Warning Code: 0, SQLState: 00000
2024-11-30T17:49:53.550+05:00  WARN 1 --- [txtgroup] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : constraint "ukckobiucr0dustyha168ybkybx" of relation "workers" do                          es not exist, skipping
Hibernate:
    alter table if exists workers
       add constraint UKckobiucr0dustyha168ybkybx unique (contragent_id)
Hibernate:
    alter table if exists actions
       add constraint FKkd5p89q8rsly0mt87hxkma30e
       foreign key ("sub-menu-id")
       references "sub-menus"
Hibernate:
    alter table if exists attendances
       add constraint FK7f87sy697hma8gq2f0qo3clw4
       foreign key (salary_id)
       references salaries
Hibernate:
    alter table if exists blocks
       add constraint FKaosgy5ytw4k6itrwxojh50wkl
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists calendar_dates
       add constraint FKmxdk25v8ypm01lybi7usaef0t
       foreign key (attendance_id)
       references attendances
Hibernate:
    alter table if exists cash_transfer
       add constraint FKdfifo0rid3cs0kfj7kfvl2cc3
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists cash_transfer
       add constraint FKp328unibs5t1p0bj8ub1akpuj
       foreign key (category_id)
       references categories
Hibernate:
    alter table if exists cash_transfer
       add constraint FKhnbbtg6hbqt2p8hrtv8hx0jl8
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists cash_transfer
       add constraint FKqic1830fvdeljrc9jvhwxnrlb
       foreign key (couple_id)
       references cash_transfer
Hibernate:
    alter table if exists cash_transfer
       add constraint FKcl4i1suneb71mwtiivym8dpu7
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists cash_transfer
       add constraint FKinha5tf37mj9rvkwvf90bexs3
       foreign key (payment_method_id)
       references payment_methods
Hibernate:
    alter table if exists cash_transfer
       add constraint FKi8fvoi77949l13vds7be69d32
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists cash_users
       add constraint FKk5qdaa801v8rawi5fgu4g2gb2
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists cash_users
       add constraint FKoqemugcbs608n2vcs9fv6df1b
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists cashes
       add constraint FKacgm578496dexs369ah8yfa92
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists departments
       add constraint FKae8h4nwnqpfcr5078n17b0lgo
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists employees
       add constraint FKk9gb9t00aafpxlnj1c5f8p3mq
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists employees
       add constraint FKgy4qe3dnqrm3ktd76sxp7n4c2
       foreign key (department_id)
       references departments
Hibernate:
    alter table if exists employees
       add constraint FKgawtrwvxw4uu0ppt5h8w5go
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists exceptions_log
       add constraint FKevy41sy5yn6m9bo46lwhbtxfu
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists materials
       add constraint FKmknh0urg319ho0gysamyymqu1
       foreign key (category_id)
       references material_categories
Hibernate:
    alter table if exists materials
       add constraint FKg5md9qacf6ygyn3e4kje520jb
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists ours
       add constraint FKn5qrkl2yp5qglvlwxuwn1568g
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists ours
       add constraint FKmea8wtb9ngp0lbb2ys85un9hi
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists payrolls
       add constraint FK9c6eobekwp3xid6a47fiiqlad
       foreign key (cashier_id)
       references users
Hibernate:
    alter table if exists payrolls
       add constraint FKpwns56h96myk8agf1wyeeehna
       foreign key (salary_id)
       references salaries
Hibernate:
    alter table if exists payrolls
       add constraint FKbgga2c4a5q28olvop4nv75tq4
       foreign key (transaction_id)
       references transactions
Hibernate:
    alter table if exists receipt
       add constraint FKf00gy6ei09qby0kpsjcu71ho0
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists receipt
       add constraint FKcw8tpu3mls155d4rxfe0wdqj8
       foreign key (supplier_id)
       references suppliers
Hibernate:
    alter table if exists receipt
       add constraint FK9llbb4mj9qe5l0krj2ro35u51
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists receipt
       add constraint FKoph7vxqnol9dqc6m8n8vpkgo
       foreign key (warehouse_id)
       references warehouses
Hibernate:
    alter table if exists receipt_item
       add constraint FKkhkp2ftva7u0qx4kg3d155orp
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists receipt_item
       add constraint FKnbwpfcho1gi58cd8xqo6d6t9i
       foreign key (material_id)
       references materials
Hibernate:
    alter table if exists receipt_item
       add constraint FKsohgmt8ntavcgj10ha2duc8la
       foreign key (receipt_id)
       references receipt
Hibernate:
    alter table if exists receipt_item
       add constraint FK5riommiv7t27rc8ntqe0brc8x
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists role_actions
       add constraint FK4581swvrx51fb6xess0vrouyf
       foreign key (action_id)
       references actions
Hibernate:
    alter table if exists role_actions
       add constraint FKiqm6ohr1ks84kwg1fungt6pmp
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists role_menus
       add constraint FKo7blfgcetl84km46ayoybmkvm
       foreign key (menu_id)
       references menus
Hibernate:
    alter table if exists role_menus
       add constraint FK8w16n9supii3exa5gnfdey3vu
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists role_submenus
       add constraint FKxnuiglsoer0r7gq3vbb8tq4q
       foreign key (sub_menu_id)
       references "sub-menus"
Hibernate:
    alter table if exists role_submenus
       add constraint FKkojsnj5gf3d3y83er605jofrd
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists salaries
       add constraint FK1utmvufusgyktdtbmo4xfas10
       foreign key (employee_id)
       references employees
Hibernate:
    alter table if exists "sub-menus"
       add constraint FKnq4jqab43ibxovnjjcun1rl2r
       foreign key (menu_id)
       references menus
Hibernate:
    alter table if exists suppliers
       add constraint FKsdk7mg1sxh3phs6jbwq973fg7
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists transactions
       add constraint FK3xjphv8luajr16jpm3ikypv3k
       foreign key (cash_id)
       references cashes
Hibernate:
    alter table if exists transactions
       add constraint FKsqqi7sneo04kast0o138h19mv
       foreign key (category_id)
       references categories
Hibernate:
    alter table if exists transactions
       add constraint FK73dgh9kq6sqey6up4507k5xwb
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists transactions
       add constraint FK812edr8o27pte306gvbmypytx
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists transactions
       add constraint FK566q0xeai5k115ya39d776f3w
       foreign key (payment_method_id)
       references payment_methods
Hibernate:
    alter table if exists transactions
       add constraint FKqwv7rmvc8va8rep7piikrojds
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists units
       add constraint FKbp8ca2wue8clkqsfsxc1bpvfr
       foreign key (group_id)
       references unit_groups
Hibernate:
    alter table if exists users
       add constraint FKp56c1712k691lhsyewcssf40f
       foreign key (role_id)
       references roles
Hibernate:
    alter table if exists users_actions
       add constraint FKn2nrr0jotbch4dc0xe9y02ryd
       foreign key (action_id)
       references actions
Hibernate:
    alter table if exists users_actions
       add constraint FKf469hk2si31ox0ly8v81lbmys
       foreign key (user_id)
       references users
Hibernate:
    alter table if exists warehouse_operations
       add constraint FKja79uhrw7hxwklj2u3f3002vw
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists warehouse_operations
       add constraint FK8cat5e6dfmqrdncuwxw62mw
       foreign key (product_id)
       references materials
Hibernate:
    alter table if exists warehouse_operations
       add constraint FKervq6jvj70oe7lg17fw1w33f0
       foreign key (warehouse_id)
       references warehouses
Hibernate:
    alter table if exists warehouses
       add constraint FK49wpwtmstd4xidmnuux0a1cjp
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists warehouses_users
       add constraint FKn3ilqebpig3mqaxqqjx99p41e
       foreign key (users_id)
       references users
Hibernate:
    alter table if exists warehouses_users
       add constraint FKqn8wea4lk2l9yiawuxlc5mt82
       foreign key (warehouse_id)
       references warehouses
Hibernate:
    alter table if exists work_types
       add constraint FKdmiqyvtldl8t82rmch3i3v3lp
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists work_types
       add constraint FKsyg6v8jeoql6cvqvs9o7h7ev4
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists workers
       add constraint FKagsd3git2vs5coeevvct2x0mi
       foreign key (contragent_id)
       references contragents
Hibernate:
    alter table if exists works
       add constraint FK3qscfr9kh0siyx5gnt2wx9rb0
       foreign key (block_id)
       references blocks
Hibernate:
    alter table if exists works
       add constraint FKq2bgpd0wdsxg10e9oje9hv9mn
       foreign key (currency_id)
       references currencies
Hibernate:
    alter table if exists works
       add constraint FKlcit1y5qreemmsiwghc2b2o8k
       foreign key (project_id)
       references projects
Hibernate:
    alter table if exists works
       add constraint FKmwhy8mm74j7cw4t8fc9g6ovft
       foreign key (unit_id)
       references units
Hibernate:
    alter table if exists works
       add constraint FKq6fv1dvvc98iyvouvvsvlxx2g
       foreign key (work_type_id)
       references work_types
Hibernate:
    alter table if exists works
       add constraint FKjr4h8vtlv5r2litq2qhno5ri1
       foreign key (worker_id)
       references workers
2024-11-30T17:49:53.742+05:00  INFO 1 --- [txtgroup] [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'defaul                          t'
2024-11-30T17:49:53.883+05:00  INFO 1 --- [txtgroup] [           main] o.s.d.j.r.query.QueryEnhancerFactory     : Hibernate is in classpath; If applicable, HQL parser will be used                          .
2024-11-30T17:49:54.198+05:00  INFO 1 --- [txtgroup] [           main] r$InitializeUserDetailsManagerConfigurer : Global AuthenticationManager configured with UserDetailsService b                          ean with name userDetailsServiceImpl
2024-11-30T17:49:54.250+05:00  WARN 1 --- [txtgroup] [           main] JpaBaseConfiguration$JpaWebConfiguration : spring.jpa.open-in-view is enabled by default. Therefore, databas                          e queries may be performed during view rendering. Explicitly configure spring.jpa.open-in-view to disable this warning
2024-11-30T17:49:54.497+05:00  INFO 1 --- [txtgroup] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port 8080 (http) with context path '/'
2024-11-30T17:49:54.502+05:00  INFO 1 --- [txtgroup] [           main] uz.txtgroup.Application                  : Started Application in 3.435 seconds (process running for 3.652)
2024-11-30T17:49:54.535+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select r1_0.id,r1_0.creat                          ed_date,r1_0.description,r1_0.name,r1_0.updated_date from roles r1_0
Hibernate:
    select
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date
    from
        roles r1_0
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        roles
        (created_date, description, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
2024-11-30T17:49:54.567+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select r1_0.id,r1_0.creat                          ed_date,r1_0.description,r1_0.name,r1_0.updated_date from roles r1_0
Hibernate:
    select
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date
    from
        roles r1_0
2024-11-30T17:49:54.593+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select u1_0.id,u1_0.creat                          ed_date,u1_0.email,u1_0.first_name,u1_0.is_active,u1_0.last_name,u1_0.password,u1_0.patronymic,u1_0.phone,r1_0.id,r1_0.created_date,r1_0.description,r1_0.name,r1_0.updated_date,u1                          _0.updated_date,u1_0.username from users u1_0 left join roles r1_0 on r1_0.id=u1_0.role_id where u1_0.email=?
Hibernate:
    select
        u1_0.id,
        u1_0.created_date,
        u1_0.email,
        u1_0.first_name,
        u1_0.is_active,
        u1_0.last_name,
        u1_0.password,
        u1_0.patronymic,
        u1_0.phone,
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date,
        u1_0.updated_date,
        u1_0.username
    from
        users u1_0
    left join
        roles r1_0
            on r1_0.id=u1_0.role_id
    where
        u1_0.email=?
2024-11-30T17:49:54.596+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select u1_0.id,u1_0.creat                          ed_date,u1_0.email,u1_0.first_name,u1_0.is_active,u1_0.last_name,u1_0.password,u1_0.patronymic,u1_0.phone,r1_0.id,r1_0.created_date,r1_0.description,r1_0.name,r1_0.updated_date,u1                          _0.updated_date,u1_0.username from users u1_0 left join roles r1_0 on r1_0.id=u1_0.role_id where u1_0.email=?
Hibernate:
    select
        u1_0.id,
        u1_0.created_date,
        u1_0.email,
        u1_0.first_name,
        u1_0.is_active,
        u1_0.last_name,
        u1_0.password,
        u1_0.patronymic,
        u1_0.phone,
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date,
        u1_0.updated_date,
        u1_0.username
    from
        users u1_0
    left join
        roles r1_0
            on r1_0.id=u1_0.role_id
    where
        u1_0.email=?
2024-11-30T17:49:54.597+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select u1_0.id,u1_0.creat                          ed_date,u1_0.email,u1_0.first_name,u1_0.is_active,u1_0.last_name,u1_0.password,u1_0.patronymic,u1_0.phone,r1_0.id,r1_0.created_date,r1_0.description,r1_0.name,r1_0.updated_date,u1                          _0.updated_date,u1_0.username from users u1_0 left join roles r1_0 on r1_0.id=u1_0.role_id where u1_0.email=?
Hibernate:
    select
        u1_0.id,
        u1_0.created_date,
        u1_0.email,
        u1_0.first_name,
        u1_0.is_active,
        u1_0.last_name,
        u1_0.password,
        u1_0.patronymic,
        u1_0.phone,
        r1_0.id,
        r1_0.created_date,
        r1_0.description,
        r1_0.name,
        r1_0.updated_date,
        u1_0.updated_date,
        u1_0.username
    from
        users u1_0
    left join
        roles r1_0
            on r1_0.id=u1_0.role_id
    where
        u1_0.email=?
Hibernate:
    insert
    into
        users
        (created_date, email, first_name, is_active, last_name, password, patronymic, phone, role_id, updated_date, username)
    values
        (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        users
        (created_date, email, first_name, is_active, last_name, password, patronymic, phone, role_id, updated_date, username)
    values
        (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        users
        (created_date, email, first_name, is_active, last_name, password, patronymic, phone, role_id, updated_date, username)
    values
        (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)
    returning id
2024-11-30T17:49:54.754+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select c1_0.id,c1_0.creat                          ed_date,c1_0.is_active,c1_0.name,c1_0.updated_date from currencies c1_0 where c1_0.name=?
Hibernate:
    select
        c1_0.id,
        c1_0.created_date,
        c1_0.is_active,
        c1_0.name,
        c1_0.updated_date
    from
        currencies c1_0
    where
        c1_0.name=?
2024-11-30T17:49:54.756+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select c1_0.id,c1_0.creat                          ed_date,c1_0.name,c1_0.type,c1_0.updated_date from contragents c1_0 where c1_0.type=?
Hibernate:
    select
        c1_0.id,
        c1_0.created_date,
        c1_0.name,
        c1_0.type,
        c1_0.updated_date
    from
        contragents c1_0
    where
        c1_0.type=?
2024-11-30T17:49:54.757+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select c1_0.id,c1_0.creat                          ed_date,c1_0.description,c1_0.is_active,c1_0.name,c1_0.updated_date from categories c1_0 where c1_0.name=?
Hibernate:
    select
        c1_0.id,
        c1_0.created_date,
        c1_0.description,
        c1_0.is_active,
        c1_0.name,
        c1_0.updated_date
    from
        categories c1_0
    where
        c1_0.name=?
2024-11-30T17:49:54.758+05:00 TRACE 1 --- [txtgroup] [           main] o.h.s.r.j.i.DeferredResultSetAccess      : Executing query to retrieve ResultSet : select pm1_0.id,pm1_0.cre                          ated_date,pm1_0.description,pm1_0.is_active,pm1_0.name,pm1_0.updated_date from payment_methods pm1_0 where pm1_0.name=?
Hibernate:
    select
        pm1_0.id,
        pm1_0.created_date,
        pm1_0.description,
        pm1_0.is_active,
        pm1_0.name,
        pm1_0.updated_date
    from
        payment_methods pm1_0
    where
        pm1_0.name=?
Hibernate:
    insert
    into
        payment_methods
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        payment_methods
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        currencies
        (created_date, is_active, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        currencies
        (created_date, is_active, name, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        contragents
        (created_date, name, type, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        contragents
        (created_date, name, type, updated_date)
    values
        (?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        categories
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
Hibernate:
    insert
    into
        categories
        (created_date, description, is_active, name, updated_date)
    values
        (?, ?, ?, ?, ?)
    returning id
root@txtserver:~#
