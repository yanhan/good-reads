# About

Sysadmin stuff.


## War stories

- https://www.reddit.com/r/sysadmin/comments/r6zfv/we_are_sysadmins_reddit_ask_us_anything/ (Read; note down the interesting stuff)
- https://stripe.com/blog/game-day-exercises-at-stripe
- https://community.monzo.com/t/resolved-current-account-payments-may-fail-major-outage-27-10-2017/26296/95


## Load Testing

- https://github.com/fortio/fortio


## GitLab

- https://about.gitlab.com/2016/07/29/the-basics-of-gitlab-ci/
- https://about.gitlab.com/2016/08/26/ci-deployment-and-environments/


## iptables

- https://www.digitalocean.com/community/tutorials/how-the-iptables-firewall-works
- https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-using-iptables-on-ubuntu-14-04
- https://www.digitalocean.com/community/tutorials/iptables-essentials-common-firewall-rules-and-commands
- https://www.digitalocean.com/community/tutorials/how-to-list-and-delete-iptables-firewall-rules
- https://www.digitalocean.com/community/tutorials/how-to-choose-an-effective-firewall-policy-to-secure-your-servers (Covers connection and rate limiting)
- https://www.digitalocean.com/community/tutorials/a-deep-dive-into-iptables-and-netfilter-architecture
- https://www.digitalocean.com/community/tutorials/how-to-implement-a-basic-firewall-template-with-iptables-on-ubuntu-14-04
- https://www.digitalocean.com/community/tutorials/how-to-set-up-an-iptables-firewall-to-protect-traffic-between-your-servers
- https://www.digitalocean.com/community/tutorials/how-to-forward-ports-through-a-linux-gateway-with-iptables
- https://www.digitalocean.com/community/tutorials/how-to-test-your-firewall-configuration-with-nmap-and-tcpdump
- https://askubuntu.com/questions/579231/whats-the-difference-between-prerouting-and-forward-in-iptables
- https://two-wrongs.com/securing-a-debian-laptop-with-a-firewall.html
- https://making.pusher.com/per-ip-rate-limiting-with-iptables/


## SSH

- https://vimeo.com/54505525  (The Black Magic of SSH / SSH can do that?)
- http://matt.might.net/articles/ssh-hacks/
- https://www.cyberciti.biz/tips/linux-unix-bsd-openssh-server-best-practices.html
- https://blog.trackets.com/2014/05/17/ssh-tunnel-local-and-remote-port-forwarding-explained-with-examples.html


## Monitoring and Alerting

- https://www.datadoghq.com/blog/monitoring-101-collecting-data/ (very good 3 part series)
- http://www.brendangregg.com/usemethod.html (Classic piece which teaches you what to monitor on infra level)
- https://docs.google.com/document/d/199PqyG3UsyXlwieHaqbGiWVa8eMWi8zzAn0YfcApr8Q/edit# (Rob Ewaschuk - My Philosophy on Alerting. Classic piece like Brendan Gregg's USE method, teaches you to monitor symptions, not causes)
- http://www.brendangregg.com/USEmethod/use-linux.html
- https://www.dashdigital.com.au/blog/item/how-to-receive-aws-cloudwatch-alerts-instantly-in-slack.html
- https://medium.com/cohealo-engineering/how-set-up-a-slack-channel-to-be-an-aws-sns-subscriber-63b4d57ad3ea
- https://www.datadoghq.com/blog/the-power-of-tagged-metrics/
- https://www.cyberciti.biz/tips/top-linux-monitoring-tools.html
- http://www.brendangregg.com/tsamethod.html
- https://www.digitalocean.com/community/tutorials/an-introduction-to-metrics-monitoring-and-alerting
- https://www.digitalocean.com/community/tutorials/gathering-metrics-from-your-infrastructure-and-applications


## On-call

- https://codywilbourn.com/2018/03/22/sustainable-on-call/


## Logging

- http://blog.scalyr.com/2017/10/kind-log-file-reading/
- http://blog.scalyr.com/2017/10/application-logging-practices-adopt/


## Datadog

- https://www.datadoghq.com/blog/live-process-monitoring/
- https://www.datadoghq.com/blog/introducing-live-container-monitoring/
- https://docs.datadoghq.com/integrations/docker_daemon/
- https://docs.datadoghq.com/tracing/visualization/trace/


## Canary deployments

- https://medium.com/netflix-techblog/automated-canary-analysis-at-netflix-with-kayenta-3260bc7acc69


## Immutable Infrastructure

- https://www.powerdown.io/blog/posts/stories/immutable-infrastructure-can-be-dramatically-more-secure.html


## Empowering engineers

- https://medium.com/netflix-techblog/full-cycle-developers-at-netflix-a08c31f83249


## Ansible

- https://stackoverflow.com/a/50526489 (Override ansible SSH private key file)
- https://github.com/ansible/ansible/issues/33052#issuecomment-354709302 (`ec2_ami` module Failed to import the required Python library (botocore or boto3))


## Hashicorp Vault

- https://www.vaultproject.io/docs/concepts/pgp-gpg-keybase.html
- https://learn.hashicorp.com/vault/developer/iam-authentication (AppRole Pull Authentication)


## fail2ban

- https://fail2ban.readthedocs.io/en/latest/filters.html#date-time (datetime needs to start at beginning of each line of log)


## systemd

- https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system_administrators_guide/sect-managing_services_with_systemd-unit_files


## sudo

- https://unix.stackexchange.com/a/18880 (syntax to allow user to run multiple selected commands)


## Increase number of open file descriptors

- https://www.cyberciti.biz/tips/linux-procfs-file-descriptors.html
- https://easyengine.io/tutorials/linux/increase-open-files-limit/
- https://askubuntu.com/a/162230


## SSL

- https://blog.cloudflare.com/keyless-ssl-the-nitty-gritty-technical-details/
- https://scotthelme.co.uk/debunking-the-fallacy-that-paid-certificates-are-better-than-free-certificates-and-other-related-nonsense/
- https://scotthelme.co.uk/are-ev-certificates-worth-the-paper-theyre-written-on/
- https://scotthelme.co.uk/revocation-is-broken/


## Securing stuff

### HTTPS for localhost

- https://news.ycombinator.com/item?id=17358339 (Certificates for localhost)
- https://news.ycombinator.com/item?id=17360525
- https://blog.filippo.io/how-plex-is-doing-https-for-all-its-users/ (very very nice)


## Terraform

- https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca
- https://github.com/hashicorp/terraform/issues/1178#issuecomment-207369534 (trick to create a dependency on a module to finish running)
- https://github.com/arminc/terraform-ecs
- https://www.reddit.com/r/Terraform/comments/a3qr3i/using_data_statementfilter_to_pull_amazon_linux_2/
- https://medium.com/@aniket10051994/inter-module-resource-dependency-in-terraform-9291070133f3
- https://github.com/hashicorp/terraform/issues/2114#issuecomment-433482161 (object types)

### Loops

- https://serverfault.com/questions/833810/terraform-use-nested-loops-with-count/962845
- https://blog.gruntwork.io/terraform-tips-tricks-loops-if-statements-and-gotchas-f739bbae55f9

### Remote state

- https://www.terraform.io/docs/providers/terraform/d/remote_state.html#root-outputs-only (Accessing output from modules in remote state)

### Templating

- https://www.terraform.io/docs/configuration/functions/templatefile.html (Use jsonencode to generate list in template file)


## aws-vault

- https://github.com/hashicorp/terraform/issues/2972#issuecomment-365768283 (aws-vault exec --no-session)


## Vagrant

- https://stackoverflow.com/a/12938524/732396 (How to SSH into Vagrant without running "vagrant ssh")


## Computer Networks

- http://jvns.ca/networking-zine.pdf (Julia Evans Networking Zine)
- https://openvpn.net/index.php/open-source/documentation/howto.html
- http://sites.inka.de/bigred/devel/tcp-tcp.html
- https://en.wikipedia.org/wiki/SRV_record
- https://www.cisco.com/c/en/us/support/docs/ip/dynamic-address-allocation-resolution/13711-40.html
- https://aws.amazon.com/blogs/security/how-to-add-dns-filtering-to-your-nat-instance-with-squid/
- http://packetlife.net/blog/2010/jun/7/understanding-tcp-sequence-acknowledgment-numbers/
- https://blog.benjojo.co.uk/post/bgp-battleships
- https://serverfault.com/questions/279482/what-is-the-difference-between-unicast-anycast-broadcast-and-multicast-traffic

### Add network latency artificially / slow down network

- https://jvns.ca/blog/2017/04/01/slow-down-your-internet-with-tc/
- https://bencane.com/2012/07/16/tc-adding-simulated-network-latency-to-your-linux-server/

### Hardcore Network Engineering

- https://engineering.riotgames.com/news/fixing-internet-real-time-applications-part-ii
- https://engineering.riotgames.com/news/fixing-internet-real-time-applications-part-iii

### DNS

- https://zwischenzugs.com/2018/01/26/how-and-why-i-run-my-own-dns-servers/
- https://wiki.gandi.net/en/glossary/glue-record
- https://blog.cloudflare.com/dns-resolver-1-1-1-1/
- https://medium.com/@nykolas.z/dns-resolvers-performance-compared-cloudflare-x-google-x-quad9-x-opendns-149e803734e5
- https://zwischenzugs.com/2018/01/26/how-and-why-i-run-my-own-dns-servers/


## OpenVPN

- https://openvpn.net/index.php/open-source/documentation/howto.html
- https://community.openvpn.net/openvpn/wiki/BridgingAndRouting
- https://serverfault.com/a/376228
- https://arashmilani.com/post?id=53
- https://www.bestvpn.com/vpns-beginners-need-know/
- https://www.bestvpn.com/vpn-encryption-the-complete-guide/#summaries
- https://serverfault.com/questions/483941/generate-an-openvpn-profile-for-client-user-to-import
- https://forums.openvpn.net/viewtopic.php?t=23683  (OpenVPN on AWS using routing instead of NATing; source/dest checks is the problem)
- https://forums.openvpn.net/viewtopic.php?t=21784
- https://stackoverflow.com/questions/31315073/static-routing-in-aws-ec2
- https://forums.aws.amazon.com/thread.jspa?messageID=570840  (Seems like AWS VPC Peering Connection does something like src / dest checking and we may not be able to disable it. Hence VPN is stuck in a VPC and we have to use NATing. But this is just a maybe; need to verify)
- https://community.openvpn.net/openvpn/wiki/UnprivilegedUser
- https://serverfault.com/questions/638575/connecting-an-ec2-vpc-with-openvpn-all-routed-traffic-being-lost
- https://community.openvpn.net/openvpn/wiki/Hardening
- https://openvpn.net/vpn-server-resources/troubleshooting-reaching-systems-over-the-vpn-tunnel/

## IPSec

- https://www.youtube.com/watch?v=tuDVWQOG0C0  (What is IPSec?)

## General VPN

- https://www.youtube.com/watch?v=4BfL0UHrzDY  (What is a VPN?)
- http://www.nimlabs.org/dirtynat.html   (Dirty NAT tricks to get a VPN to work with clients also numbered in the private address space)


## Docker

- https://docs.docker.com/engine/reference/run/#runtime-privilege-and-linux-capabilities (Docker runtime default capabilities)
- https://stackoverflow.com/a/41021336 (devmapper: thin pool has N free data blocks which is less than minimum required .... Create more free space in thin pool or use `dm.min_free_space` to change behavior) [Basically running out of space for Docker images]
- https://forums.docker.com/t/is-it-possible-to-ssh-to-the-xhyve-machine/17426/3
- https://medium.com/devopsion/life-and-death-of-a-container-146dfc62f808
- https://stackoverflow.com/a/41176677 (Get list of dependent child images)
- https://stackoverflow.com/a/43473861 (cron - cannot make/remove an entry for the specified session)
- https://stackoverflow.com/a/32723127 (prune images)

### Docker Monitoring

- https://stackoverflow.com/a/41578148 (See memory usage of container)
- https://www.datadoghq.com/blog/the-docker-monitoring-problem/


## Jenkins

- https://github.com/jenkinsci/winstone/blob/master/src/main/java/winstone/accesslog/SimpleAccessLogger.java (provides insight on changing the log format)


## Chaos Engineering

- http://queue.acm.org/detail.cfm?id=2353017 (Fault injection in Production)


## General

- http://blog.scoutapp.com/articles/2014/11/04/restricting-process-cpu-usage-using-nice-cpulimit-and-cgroups


## Kerberos

- https://www.oreilly.com/library/view/hadoop-security/9781491900970/ch04.html
- https://gist.github.com/ashrithr/4767927948eca70845db
- https://www.theurbanpenguin.com/configuring-a-centos-7-kerberos-kdc/
- https://www.howtoforge.com/tutorial/how-to-setup-kerberos-server-and-client-on-ubuntu-1804-lts/
- https://wiki.ubuntu.com/Enterprise/Authentication/KerberosServices
- https://www.learningjournal.guru/article/hadoop/hadoop-security-using-kerberos/
- http://hadoopexam.com/do1111/index.php/free-tutorial/hadoop-security-keberos-tutorial
- https://stackoverflow.com/a/45318625 (kadmin: automate addprinc)
- https://steveloughran.gitbooks.io/kerberos_and_hadoop/
- https://ambari.apache.org/1.2.5/installing-hadoop-using-ambari/content/ambari-kerb-1-4.html (Good Hadoop & Kerberos docs)
- https://microdevsys.com/wp/org-apache-hadoop-security-accesscontrolexception-client-cannot-authenticate-viatoken-kerberos/ (org.apache.hadoop.security.AccessControlException: Client cannot authenticate via: [TOKEN, KERBEROS])
- https://www.ibm.com/support/knowledgecenter/en/SSPT3X_4.2.0/com.ibm.swg.im.infosphere.biginsights.admin.doc/doc/admin_ssl_hbase_mr_yarn_hdfs_web.html (Setting up Data Node SASL)
