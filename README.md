# IaaC-DevDesktop
Development Desktop for Infrastructure as a Code. The purpose of this is to create a CentOS desktop as a development environment for Infrastructure as a code.

tools are like KVM, vagrant, packer, visual studio code, github for now

workflow is currently manual and first step is to store source code in github, do the source code edit in visual studion code and once tested successfully on the development environment, the image will be uploaded to vagrant cloud (as a storage for artifact)

Build artifact can be used in any public cloud and private cloud (openstack) as long as they are using kvm images
