(02:01:56 PM) profcorey: Ok, starting a quick meeting for the unofficial project cascade

(02:02:35 PM) profcorey: This is the 2nd meeting and I'll quickly cover one of the open issues regarding architecture for cascade

(02:03:24 PM) profcorey: Here's a high-level definition of Cascade: Cascade is an open source project for designing, deploying, and administering virtual contact centers and internal communications using OpenStack infrastructure. 

(02:04:52 PM) profcorey: I created a generic OpenStack Arch diagram for creating a baseline deployment for Cascade: https://github.com/profcorey/cascade/blob/main/images/generic_openstack_architecture.png

(02:05:51 PM) profcorey: The initial proof of concept deployment will incorporate Asterisk, the open source PBX/VOIP software, https://github.com/profcorey/cascade/blob/main/images/cascade_cloud_architecture.png

(02:06:23 PM) profcorey: This deployment uses a cloud provider such as AWS, Google Cloud, etc.

(02:07:07 PM) profcorey: Another PoC is simply deploying Cascade w/ Asterisk using VirtualBox locally, https://github.com/profcorey/cascade/blob/main/images/cascade_virtualbox_architecture.png

(02:07:40 PM) profcorey: And then finally the last PoC would be on bare metal https://github.com/profcorey/cascade/blob/main/images/cascade_baremetal_architecture.png

(02:08:22 PM) profcorey: The next issue is to create a timeline for testing these deployments

(02:09:09 PM) profcorey: I hope to have a timeline in 2 weeks for our next meeting on the 18th

(02:10:14 PM) profcorey: I'm also working on the cookie cutter code for starting an OpenStack project: https://github.com/openstack/cookiecutter

(02:10:29 PM) profcorey: I hope to have all of the default files in the repo by the 18th as well

(02:11:05 PM) profcorey: Future work will involve a diagram of the Asterisk deployment and which modules will be deployed

(02:11:29 PM) profcorey: Also, a testing system will be needed to test each deployment for functionality

(02:12:18 PM) profcorey: I recently attended the FreePBX conference in Denver and learned about the frontend FreePBX

(02:12:55 PM) profcorey: I'll need to research FreePBX more on how to access within Cascade for administering Asterisk using a UI

(02:13:17 PM) profcorey: That's all I had for today. Since it's a holiday, I wanted to keep this short.

(02:13:38 PM) profcorey: Next meeting for Project Cascade will by July 18th same time same place, thanks!
