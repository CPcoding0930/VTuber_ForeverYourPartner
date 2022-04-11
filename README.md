# VTuber_ForeverYourPartner
This is on the research (Final Year Project) topic "Supporting Immersive Viewer Engagement with Virtual YouTubers", under the supervision of Dr LU Zhicong

## Project Description
<img src="https://github.com/CPcoding0930/VTuber_ForeverYourPartner/blob/58c5a96e7add2c9f73fc596cde841291a9c7e53b/3Dagent/pose.png"  width="200" height="400" />

Since late 2016, the public launch of virtual influencers foreshadows sensation soon after its release, receiving critical acclaim worldwide. Recently, one of the remarkable VTuber, Kizuna AI was selected as one of Asia’s top 60 influencers. This highlights the potentiality of this field with the advancements of skyrocketing technology. Influenced by the big market share of ACGN (anime, comic, game, novel) culture, VTubers’ behaviors are more acceptable than real-person YouTubers. Many audiences are motivated to engage with virtual Youtubers (VTubers) as they would like to interact with favorite anime characters. In consequence, VTubers can provide relaxation and entertainment for viewers. Yet, a higher sense of distance is found between viewers and virtual avatars contrary to the variety of video genres in traditional streamers. Whereas VTubing has limited genre and content diversity under its performing style, Nakanohitos can hardly build unintuitive content under identity management. These directly affect the performance and quality of VTubing. This bottleneck leaves unsolved consequences for supporting immersive viewer engagement with VTuber. This paper proposes a novel design in creating agents to share the workload of Nakanohitos and an innovative user interface in virtual reality. Significantly, possible measurements and functionalities in virtual live streaming are designed for assisting the management of characters’ persona in order to match the viewers’ expectations. The bucket testing conducted further reveals viewers’ satisfaction in adopting immersive virtual reality application on VTubing industry. Writer views the potential of relevant designs.

## Structure
There are two designs to form the portrayal of the system: user interface for VTuber or streamers; and an agent that can provide responsive interaction.  
Belows are the Work Breakdown Structure and Flowchat of the project:

<img src="https://github.com/CPcoding0930/VTuber_ForeverYourPartner/blob/5e70c9836bbc70875b064bfbe0192cc9f86dd55c/FIG.1.3_WBS.png "  width="300" height="200" />
<img src="https://github.com/CPcoding0930/VTuber_ForeverYourPartner/blob/5e70c9836bbc70875b064bfbe0192cc9f86dd55c/FIG.1.4_Flowchart.png "  width="300" height="200" />

## Installation and Implementation
In this repositary, you will find several components and folders. Here in this part, the relative functionalities are described:
1. User Interface: please refer to the user-interface.pdf in the folder. It is generated and designed via Adobe XD.
2. 2Davatar folder: the Live2D and design folders, layers can be found here in this folder. With the .moc3 and .json files attached, you can import the model into Live2D and perform the 2D Forever Your Partner (FYP) avatar.
![alt text](https://github.com/CPcoding0930/VTuber_ForeverYourPartner/blob/3156fd6af8b2af898ac5ff97d133834ffc03dde5/2Dimplementation.png "The Live2D interface with FYP demo")
3. 3Dagent folder: Screenshots and Unity folder are here in this folder. The 3D animation and responsive agent implementation can be found here and open in Unity. For user with Oculus Quest or any other VR applications, please feel free to open it via Oculus Link. 
    To open the Unity file, you can either use sidequest/Oculus Link as review with the demo.apk, or (perferable) use Unity3D in playing the saved scene. Here are the procedures:
    * Please download Unity if you do not have one from [Unity Official] (https://unity.com/). For those who have the application, download this repositary and open that with Unity project.
    * Open the scene "InteractiveFYP". Please confirm the assets and its relevant hierarchy.
    * Please refer to the Official Manual https://docs.unity3d.com/Manual/VROverview.html to see the instruction and open it according to your own settings (i.e. IOS and Android)
    * Build and Run the scene (File --> Project Setting --> Open Scene & Switch Platform & Build and Run Scene). Hence, play the scene.
    * Say Hello to trigger and activate FYP. Nod or Shake your head with the VR headset to react and respond FYP.
4. Others: the performed modified version of song United in the Sky by Unity Chan and the UniVRM asset can be found. 

## Improvement
In this project, Forever Your Partner (FYP), a 3D interactive agent for supporting immersive viewer engagement is built. A possible interface of system is proposed and demonstrated. To the best of our knowledge, this adoption of AI-driven agent in VTubing is the first attempt as a method and assistance in virtual character industry. By the evaluation we had, use of immersive environment and agent can increase immersiveness by limiting the sense of distance and enhancing sense of presence. It provides multiple ways in enhancing the engagement. While the use of agent is the key session in this part of group project, the interaction between streamers (or Nakanohitos) and viewers is particularly highlighted in this report. The study views the potential and possibilities in more interactive engagements on VTubers category under the immersive environment. More comprehensive testing should also be organized when this project is able to continue.

## Citations
The character model of FYP is implemented with VRoid Studio. To import the character model into Unity, UniVRM is used as the asset. Please refer to https://github.com/vrm-c/UniVRM for detail implementation.
