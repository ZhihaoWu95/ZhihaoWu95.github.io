---
title: "Multi-Modal Spoofing Attacks on 3D Face Liveness Detection via a Single 2D Photo"
collection: publications
category: manuscripts
permalink: /publication/DepthfakePro
excerpt: 'This paper introduce a pratical adversarial patch that can fool the commercial face athentication systems.'
date: 2024-8-19
venue: 'IEEE Transactions on Dependable and Secure Computing'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10639356'
citation: 'Wu Z, Cheng Y, Ji X, et al. Multi-Modal Spoofing Attacks on 3D Face Liveness Detection via a Single 2D Photo[J]. IEEE Transactions on Dependable and Secure Computing, 2025, 22(2): 1551-1566.'
---

Face authentication technology has been widely used in physical access control to critical infrastructures. The security of a face authentication system has been threatened by photo replay attacks and thus the 3D liveness detection techniques have been deployed to safeguard such systems. In this paper, we conduct a comprehensive analysis of the security aspects pertaining to 3D liveness detection systems that employ structured light depth camera, and propose a novel attack surface targeting 3D face authentication systems involving multiple modalities such as Depth, RGB and IR. We propose the DepthFake attack, a multi-modal spoofing attack against real-world 3D face authentication using only a single 2D photo. To achieve it, DepthFake first reconstruct the depth information of the victim's face from his 2D photo. Then, DepthFake actively projects a carefully-crafted scatter patterns embedded with the face depth information, in order to empower the 2D photo with 3D authentication properties. We address a range of practical challenges, including mitigating depth estimation errors, achieving depth images forgery techniques based on structured light, ensuring accurate alignment between various modalities of face images, and effectively implementing DepthFake in real world. We validated DepthFake on 5 commercial face authentication systems (i.e., Tencent Cloud, Baidu Cloud, 3DiVi, Ali Cloud and ArcSoft) and two commercial access control devices. The results over 50 users demonstrate that DepthFake achieves an overall Depth attack success rate of 79.4%, RGB-D attack success rate of 59.4%, IR-D attack success rate of 79.4%, and RGB-IR attack success rate of 83.8% in the real world.
