# python

TODO: Enter the cookbook description here.

Packer is an open source tool for creating identical machine images for multiple platforms from a single source configuration

Advantages of Using Packer:

Super fast infrastructure deployment: Packer images allow you to launch completely provisioned and configured machines in seconds, rather than several minutes or hours.

Multi-provider portability: Because Packer creates identical images for multiple platforms, you can run production in AWS, GCP, Azure, staging/QA in a private cloud like OpenStack, and development in desktop virtualization solutions such as VMware or VirtualBox. Each environment is running an identical machine image, giving ultimate portability.

Improved stability: Packer installs and configures all the software for a machine at the time the image is built. If there are bugs in these scripts, they’ll be caught early, rather than several minutes after a machine is launched.

Greater testability: After a machine image is built, that machine image can be quickly launched and smoke tested to verify that things appear to be working. If they are, you can be confident that any other machines launched from that image will function properly.


An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an AMI when you launch an instance. You can launch multiple instances from a single AMI when you need multiple instances with the same configuration. You can use different AMIs to launch instances when you need instances with different configurations.
