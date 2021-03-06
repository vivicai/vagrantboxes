vagrantboxes
============

**Handcrafted** Vagrant Base Boxes for [vagrantbox.es](http://vagrantbox.es).

List of boxes

- Arch Linux x86_64
- Oracle Linux 7.6 x86_64
- ~~Oracle Linux 6.9 x86_64~~
- ~~Oracle Linux 5.11 x86_64~~

Veewee definitions are in [`veewee/definitions`](https://github.com/terrywang/vagrantboxes/tree/master/veewee/definitions) to automate the building of Vagrant Base Boxes;-) Check its [README.md](https://github.com/terrywang/vagrantboxes/blob/master/veewee/README.md) for usage.

Additional list of places where you can get all sorts of vagrant base boxes for different purposes: development, testing, or even production.

- [**vagrantbox.es**](http://vagrantbox.es)

 A List of vagrant base boxes. Initiated by Gareth Rushgrove `@garethr` hosted on Heroku using Nginx. See the story here: [**The Vagrantbox.es Story**](http://www.morethanseven.net/2012/07/01/The-vagrantbox.es-story/).

- [**Official Oracle Linux Vagrant Boxes**](https://yum.oracle.com/boxes)

Now that Oracle provides official Vagrant Boxes, we should simply leverage those.

- **Chef** [**bento**](https://github.com/chef/bento)

 We all know what **bento** means in Japanese, right? In this case, they are **NOT** lunch boxes **BUT** handy base boxes which can be used to test cookbooks or anything you want. Distributions included: Ubuntu Server, Debian, CentOS and Fedora.

 Packer definitions: https://github.com/chef/bento
 
 > NOTE: To find hidden bento boxes, access the context root of the AWS S3 server.

- [**Official Puppet Vagrant Boxes**](https://app.vagrantup.com/puppetlabs)
 
 Pre-rolled vagrant boxes, ready for use. Made by the folks at Puppet Labs.
 
 Veewee definitions: https://github.com/puppetlabs/puppet-vagrant-boxes

- [**Ubuntu Cloud Images**](https://cloud-images.ubuntu.com)

 It's been there since Jan, 2013. To get latest LTS, 18.04 bionic in this case, simply use the URL: [https://cloud-images.ubuntu.com/bionic/current/bionic-server-cloudimg-amd64-vagrant.box](https://cloud-images.ubuntu.com/bionic/current/bionic-server-cloudimg-amd64-vagrant.box)

> NOTE: OVA, Azure/Hyper-V VHD, VMware VMDK, KVM img, LXD images are also available for supported architectures.
 
If you are looking for Virtual Machines with server applications (e.g. GitLab, Discourse, WordPress, Redmine, Ruby Stack, Joomla!, Drupal etc…) pre-installed and configured, try Bitnami Stacks.
