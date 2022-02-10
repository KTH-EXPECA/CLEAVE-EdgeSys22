# Reviews

```
Dear Mr. Manuel Olguín Muñoz:

Thank you for submitting your paper #1570785524, titled 'Scalable and Edge-Native Benchmarking of Networked Control Systems' to CNERT 2022: Computer and Networking Experimental Research using Testbeds. We regret to inform you that your paper could not be accepted for inclusion in the technical program.

We have received a large number of high-quality papers out of which only a few could be accepted for publication.

The reviews for your paper are attached below and can be found in EDAS at <https://edas.info/showPaper.php?m=1570785524>.

Best regards,
Gaia Maselli, Anita Nikolich
CNERT 2022 TPC Chairs

======= Workshop Reviews 1 =======

*** Contributions: What are the major issues addressed in the paper? Do you consider them important? Comment on the novelty, creativity, impact, and technical depth in the paper.

Networked Control Systems can be tested virtually with a real networking environment.

*** Strengths: What are the major reasons to accept the paper? [Be brief.]

The system seems to be generic enough to support a wide variety of experiments.

*** Weaknesses: What are the major reasons NOT to accept the paper? [Be brief.]

The experiments and technical consideration seem to be too preliminary.

*** Detailed Comments: Please provide detailed comments that will help the TPC assess the paper and help provide feedback to the authors.

Although the reviewer believes the proposed system has a good potential for supporting various experimental scenarios, the paper almost lacks explanations about scalability. In addition, the authors should describe the technical issues more clearly and design the experiments more appropriately to show the proposed system provides good solutions for the issues.

*** Familiarity: Rate your familiarity with the topic of the paper.
Familiar (I am well aware of research work in this topic) (3)

*** Recommendation: Your overall rating (Please try giving as few borderlines as possible).
accept if there is room (3)

======= Workshop Reviews 2 =======

*** Contributions: What are the major issues addressed in the paper? Do you consider them important? Comment on the novelty, creativity, impact, and technical depth in the paper.

The paper "Scalable and Edge-Native Benchmarking of Networked Control Systems" contributes to the theme of cyber physical systems and software to control a number pf physical machines connected via a real network. They present a software framework for benchmarking these systems, called CLEAVE.

*** Strengths: What are the major reasons to accept the paper? [Be brief.]

They present an interesting control experiment that is sensing data using raspberry pis.
They discuss aspects of the sample rate, latency and other networking aspects that need to be studied.

*** Weaknesses: What are the major reasons NOT to accept the paper? [Be brief.]

It is unclear what they are testing. The experiment seems like a setup without any research questions being explored. What algorithms are being tested are not clear.

*** Detailed Comments: Please provide detailed comments that will help the TPC assess the paper and help provide feedback to the authors.

The paper is difficult to read. Here are detailed comments:

- In the introduction, there is no clear indication of what the research challenge is. It would be good to move the literature review to a literature review section and then talk about the challenge and motivations in introduction.
- What research questions are being tested. Are they improving the setup? what challenges did they face.

*** Familiarity: Rate your familiarity with the topic of the paper.
Expert (I conduct(ed) active research work in this topic) (4)

*** Recommendation: Your overall rating (Please try giving as few borderlines as possible).
weak reject (2)

======= Workshop Reviews 3 =======

*** Contributions: What are the major issues addressed in the paper? Do you consider them important? Comment on the novelty, creativity, impact, and technical depth in the paper.

In this paper, the authors present their CLEAVE (ControL bEnchmArking serVice on the Edge) solution aiming to simplify the repeatable and scalable benchmarking of networked control systems (NCSes). The contribution of the authors to NCS is very clear and relevant. The contribution to the use and experimentation on testbeds, which is central to CNERT, is however limited.

*** Strengths: What are the major reasons to accept the paper? [Be brief.]

The paper is very well written and organized. It is also very easy to follow and the authors' narrative is very convincing. The contribution to NCS is clear, as mentioned above when the authors deliver CLEAVE. CLEAVE itself is very convincing and a nice addition to the state-of-the-art.

*** Weaknesses: What are the major reasons NOT to accept the paper? [Be brief.]

From an experimental point of view, the paper is very interesting, but from a testbed workshop, which is the case of CNERT, the contribution of this paper is limited. The authors didn't use or delivered any testbed, although CLEAVE could be the basic software of a testbed devoted to NCS.

*** Detailed Comments: Please provide detailed comments that will help the TPC assess the paper and help provide feedback to the authors.

I liked this paper a lot. I found that the authors delivered a very good manuscript with a clear contribution to NCS. They did advance the state-of-the-art in my view. The paper is very well written, organized, and easy to follow. Although I fully recognize the value of CLEAVE to NCS, in the context of CNERT, the authors failed to provide any discussion of contribution with regard to testbeds, which is central to this workshop. CLEAVE could be, actually, a basic component of a testbed devoted to NCS. Nothing in that regard, however, is minimally discussed in the paper.

*** Familiarity: Rate your familiarity with the topic of the paper.
Familiar (I am well aware of research work in this topic) (3)

*** Recommendation: Your overall rating (Please try giving as few borderlines as possible).
accept if there is room (3)

======= Workshop Reviews 4 =======

*** Contributions: What are the major issues addressed in the paper? Do you consider them important? Comment on the novelty, creativity, impact, and technical depth in the paper.

CLEAVE is a framework for scalable and repeatable benchmarking of edge-native Networked Control Systems. It provides a mapping from abstract states, actors, and sensors to function implementations.
This work also presents two example usages of CLEAVE.
One example is a simulated experiment with an inverted pendulum system.
The other example is the same experiment with physical resources.
There has been a similar system called NCSbench. But NCSbench is not scalable in terms of the types of hardware.

*** Strengths: What are the major reasons to accept the paper? [Be brief.]

The structure is general. It abstracts the frequently used entities, like sensors, actuators, controllers, and states. Following the APIs, researchers can implement their experiments under this framework.
The paper evaluates an emulated NCS and a physical NCS. These are good examples of illustrating how researchers can make use of the system.
This work provides the code repository.

*** Weaknesses: What are the major reasons NOT to accept the paper? [Be brief.]

The abstraction can be more general, e.g. there can be multiple control loops (nested or cascaded) in more complex control applications.

Also, the setting can be more concrete. Similar to the scenario description in NCSBench, one can add details about network conditions, including dedicated resources or interference between signals that might affect the stability of the control loop(s).

*** Detailed Comments: Please provide detailed comments that will help the TPC assess the paper and help provide feedback to the authors.

Properly defining NCS experiments is an important topic. This paper looks into general and easy-to-use abstractions with the corresponding mapping to the implementation mechanism. It also provides a standardized design for experiments in general NCS. While the experiment description of CLEAVE can be more comprehensive, it is a good starting point for a more general approach.
In terms of writing, this paper is fluent and easy to understand.

*** Familiarity: Rate your familiarity with the topic of the paper.
Familiar (I am well aware of research work in this topic) (3)

*** Recommendation: Your overall rating (Please try giving as few borderlines as possible).
weak accept (4)
```

## James' comments

Hi guys,

that happens all the time, nothing to worry about. You should definitely, asap, read through the feedback. If you do so, you will recognize that all reviewers were pretty positive about the paper, and it appears more that the match of the paper to the workshop is not there in the view of the reviewers. The paper is really in the boundary ...

In summary, the reviewers critize:

- Experimental part of the paper is premature, unscientific, undirected
- Unclear research challenge addressed by the paper.
- Contribution to testbed literature is unclear
- how to integrate more complex scenarios into Cleave (multiple, connected loops etc.)

We should discuss asap what to do next. With a few more modifications the paper can for sure be improved much. We knew that we were rushing things towards the end ...
When can we talk?

Best,
James
