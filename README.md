# k8study
Kubernetes, Vagrant, Ansible and Helm Case Study meant for CentOS7.
A basic configuration from scratch - vagrant setting up VM's for Kubernetes and KubeCTL to manage, 
and Ansible to automate deployment by playbooks.
Additional guest of the episode - Helm, because installing Wordpress by hand would be a pain.

There are four parts:
1) initial-install - getting VirtualBox + Guest Additions, and Vagrant.
2) install-continue-ansible-kubectl - getting Ansible, Kubernetes, Kubectl, and doing some tweaks to ease out everything
coming.
3)vagrantfile - sole vagrantfile used in getting the cluster pre-set-up. 
4) wordpress-automation - this file contains nearly pure wordpress install automation with Helm - it is meant
to deploy 4 standalone "pods" with MySQL, Apache, and WP pre-configured. 

Please don't mind my comments that you'll find inside files - i'm the type of person that likes to gibber to
myself, often describe some processes to myself, to understand them better. My rubber duck currently is on
vacation, and the frog figure i'm using to debug instead of rubber ducky, kinda dissapeared. Smart frog,
he probably knew i'll be doing things i didn't fully understood yet, vanished to get some peace of mind. Damn you, frog.


This is not meant to be used in production environments - i had zero knowledge about each of the mentioned technologies
when i started - so be warned, don't let hell loose, and don't even try to run it on production.
I'm noob-ish enough to produce high quality errors, you know, brainlessly copy-pasting it is 
quite a fine thing to do when you want to see if Kubernetes is flammable or if it can explode.

You've been warned.

If you want to learn without repeating my mistakes, check out fi. theese guys - they surely do know better.
https://github.com/learnitguide/kubernetes-and-ansible - i couldn't do it without them.
Also, keep in mind, that Google is your best friend. Whole world's knowledge at a fingertip. Just ask the magic question, and answer you shall receive.
