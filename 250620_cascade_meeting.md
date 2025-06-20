(2:00:50 PM) profcorey: It's the top of the hour. Anyone interested in Project Cascade please feel free to join in this discussion.

(2:01:36 PM) profcorey: Project Cascade is not an official OpenStack. However, the goal is to present it to the TC at the next NA event for accepting as an official project.

(2:02:07 PM) profcorey: We have created a project charter to kickoff the project: https://github.com/profcorey/cascade/blob/main/README.md

(2:02:45 PM) profcorey: I'll allow time for anyone to review and make any comments if any...

(2:03:47 PM) profcorey: As you can see, the project charter follows the 4 opens per the foundation's reqs.
(2:06:04 PM) profcorey: Under Project Mission, line 5 there's a typo at the end, I'll fix that.
(2:06:55 PM) profcorey: We've adopted the Apache v2.0 license for licensing purposes.
(2:08:52 PM) profcorey: Until the project is official, we'll continue to develop the project's code on github in the same repo as the project charter
(2:09:06 PM) azlan: Thank you, Professor Corey. I’ve reviewed the project charter and it’s well-structured and aligns nicely with the 4 Opens principles. 
(2:09:22 PM) profcorey: Thank you azlan!
(2:09:41 PM) azlan: But can you kindly elaborate what language will be used in the project
(2:09:54 PM) profcorey: We will create a high-level architectural diagram under Architecture next
(2:10:46 PM) profcorey: For language, we will use Python since most of the other OpenStack projects use Python as well
(2:11:16 PM) azlan: Would you say the MVP should only focus on Chat + PBX + basic UI, or should we try to include auditing and analytics early on too?
(2:11:53 PM) profcorey: Help me MVP?
(2:12:22 PM) profcorey: Auditing and analytics can be future features
(2:12:47 PM) azlan: Sorry! By MVP I meant “Minimum Viable Product” — like the first working version of Cascade.
(2:13:01 PM) profcorey: Ahh, gotcha!
(2:13:28 PM) profcorey: Absolutely, minimal services to get a first version up and runing
(2:13:56 PM) azlan: Are we focusing on just a few features for now, like chat and calling, or building everything together step by step?
(2:14:05 PM) profcorey: A goal would be a working version perhaps alpha version for presenting to the TC at the next OpenInfra Days NA event
(2:14:22 PM) profcorey: Just a few MVP features
(2:14:53 PM) azlan:  Got it! So for the alpha, we’ll stick to the core — probably chat, basic PBX integration, and a simple UI. I’ll start organizing it in that direction.
(2:15:27 PM) profcorey: Agree, and the simple UI would FreePBX, I believe
(2:16:23 PM) profcorey: I'll need to research Open Source chat server/clients
(2:16:28 PM) azlan: Got it — so FreePBX will handle the PBX UI side, and we can focus on integrating chat and connecting everything behind the scenes.
(2:16:31 PM) profcorey: What did you think of Asterisk?
(2:17:05 PM) azlan:  I think Asterisk is solid — powerful and flexible
(2:17:12 PM) profcorey: I'm sure there's a stable version we can work with to intergrate into our arch
(2:17:15 PM) profcorey: Cool!
(2:17:30 PM) azlan: since FreePBX is built on top of it, it makes sense to use it as the backend. We just need to make sure we understand how to interface with it properly, maybe through AMI or ARI?
(2:17:58 PM) profcorey: Agreed, AMI? ARI?
(2:18:42 PM) azlan: Yes, definitely — I’ll look into the latest stable Asterisk version that's reliable for integration and check its compatibility with FreePBX and our planned architecture(once finalized).
(2:18:59 PM) profcorey: The alpha version will be an All-in-1 deployment at first. I have extra machines in one of my labs at my campus that I can use
(2:19:14 PM) profcorey: Fantastic azlan!
(2:19:50 PM) profcorey: But we should also try deploying alpha version in a cloud, a CCaaS in a cloud deployment.
(2:20:01 PM) azlan:  From what I’ve read, ARIis better if we want more control and plan to build our own logic for call handling. AMI is good for basic monitoring and issuing commands.
(2:20:25 PM) profcorey: Good researching! I haven't read the docs yet
(2:20:38 PM) profcorey: Good to know
(2:20:59 PM) azlan: Agreed — deploying the alpha as a cloud-based CCaaS setup would really help demonstrate the real-world use case.
(2:21:17 PM) azlan:  I can start looking into how we could package and deploy it on an OpenStack cloud
(2:21:22 PM) profcorey: So, I'll add all of our "alpha" version to a doc in GitHub for public viewing
(2:21:37 PM) azlan: okay sure
(2:21:42 PM) profcorey: Fantastic!
(2:22:05 PM) profcorey: And I'll research different IM open source tools
(2:22:22 PM) profcorey: We can the take a look through those next meeting
(2:22:44 PM) profcorey: Speaking of next meeting, let's host these bi-weekly if that's ok
(2:22:54 PM) azlan: Yes sure I will be waiting.
(2:23:18 PM) profcorey: Anything else for our next meeting?
(2:23:35 PM) azlan: Sounds good! Bi-weekly works perfectly for me.
(2:24:00 PM) profcorey: Excellent! Same time same place in 2 weeks 
(2:24:16 PM) profcorey: Alright anything else?
(2:24:28 PM) azlan: Nothing else from my side right now — unless you had anything else in mind that you'd like me to look into before our next meeting?
(2:24:47 PM) profcorey: I think the Asterisk research is plenty
(2:25:15 PM) profcorey: I'm going to copy this meeting's notes and publicly keep them in the github repo for anyone to view
(2:25:31 PM) profcorey: Ok, let's end here then
(2:25:42 PM) azlan: Got it! I’ll focus on Asterisk and come prepared with some integration details and a draft flow
(2:25:45 PM) profcorey: Thanks for attending and see you in 2 weeks!
(2:25:51 PM) profcorey: Fantastic!
