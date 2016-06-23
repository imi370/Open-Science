Using the Blockchain for Reproducible, Transparent and Trustworthy Science

Thesis Design
Ilias Elmzouri
Master Information Sciences VU University, Amsterdam Supervisor: Tobias Kuhn

ABSTRACT

Scientific studies are often not reproducible and trustworthy due to false or exaggerated research findings. This current issue creates a bias in which successful studies are often only published through the use of dishonest scientific practices. To approach this issue, a research project has been set up to investigate how the reproducibility and trustworthiness of scientific studies can be improved with the use of the blockchain technology. The blockchain technology has shown adequate results in terms of progressing and logging transactions for the Bitcoin protocol and will be examined within this project for the purpose of logging and tracking preannounced studies.

This is the thesis design for the master project ‘Using the Blockchain for Reproducible and Trustworthy Science’. First will be explained what the problem statement and context is and how the project is related to other work. Secondly, the research question and the subquestions will be defined, followed by a research methodology that will be used during the research phase. The last section introduces a planning, i.e. a roadmap, that is developed for the project.

PROBLEM STATEMENT & CONTEXT

Scientific studies are often not reproducible and trustworthy due to dishonest scientific practices. This often leads to only successful studies being published. It has been suggested by a recent study that the inability to replicate findings is due to a lack of research transparency (Iqbal et al., 2016). There is a growing movement however to encourage reproducibility and transparency practices in the scientific community. This includes public access to raw data and protocols, the conduct of replication studies, systematic integration of evidence in systematic reviews, and so forth.
In addition, a study published in 2014 states that many published research findings are false or exaggerated in which an estimated 85% of research resources are wasted (Ioannidis, 2014). Many new proposed associations and/or effects are, for example, incorrect or highly exaggerated, leading to slow and potentially inefficient translation of knowledge into useful applications. Nosek et al. argues that this bias is due to the intensely competitive job market in which the demands for publication seem to suggest a specific objective for the early-career scientist namely; publish as many articles as possible in the most prestigious journals that will accept them to boost their career and opportunities.
However, it should be stated that even if a researcher conducts studies competently, analyzes the data in an effective manner, and writes up the results understandable for everyone, there is no guarantee that the report will be published due to a part of the process (i.e. the peer review) being outside of the researcher’s control (Nosek et al., 2012).
Further, to make more published research true, Ioannidis mentions in his article ‘How to Make More Published Research True’ several promising practices that could be included to motivate the adoption of large-scale collaborative research. Such practices are:
 Registration of scientific studies and their progress;
 Sharing of reports and scientific results;
 Better standardization of definitions and analyses,
 Peer reviews;
 And dissemination of research.
Additionally, greater access to scientific inputs and outputs can improve the effectiveness and productivity of the scientific research system by (OECD, 2015):
 Reducing duplication costs in collecting, creating, transferring and reusing data and scientific material;
 Permitting more research from the same data;
 Multiplying opportunities for local and global involvement in the research process.
Scientific advice can also benefit from the meta-research offered by open science, as it allows more accurate verification of research results. With increased access to publications and data, firms and individuals may use and reuse scientific outputs to produce new products and services. Open science also allows the closer involvement and participation of citizens.

Open Science

The term open science is being used in the literature and studies to indicate a form of science based on open-source models and/or principles of open access, open archiving and open publishing to promote scientific communication (Peters, 2014). In addition, the concept of open science aims at open access to research data and publications that takes place at all stages of research. Moreover, the following factors are associated with openness in science and research and can be considered to be the most important within the context of this project (OECD, 2015):
 Increasing transparency and quality in the research validation process by allowing a greater extent of replication and validation of scientific results;
 Open science can reduce delays in the re-use of the results of scientific research including articles and data sets;
 Open science and open data approaches can promote collaborative efforts and faster knowledge transfer for a better understanding of scientific challenges;
 Open science and open data initiatives may promote awareness and trust in science among citizens.

The Blockchain Technology

To improve the reproducibility and trustworthiness of open scientific studies, an announcement could be publicized beforehand through the use of the blockchain technology. From then on, progress of scientific studies could be logged and their results linked, all in a way that cannot be changed afterwards. Reviewers of papers, for example, could check how many experiments were announced, and how these progressed over time, which would give them more information to decide whether a study meets the scientific quality criteria.
The concept behind the blockchain technology is similar to that of a database. A blockchain is a place where semi-public data is stored in a block1, meaning that a part of the information stored — its “header” — is public. Anyone can verify that you have placed certain information, but only the owner (or a program) can unlock what is inside the block by using the private keys to that data. The semi-public data is stored in a block, one after the other, with later blocks each containing a pointer to the immediately prior. In essence, the blockchain practically behaves as a database. The data stored can be a token of value, or a crypto money balance.

THEORETICAL BACKGROUND

The Decentralized Setting

Each consecutive block contains a “hash” (a unique fingerprint) of the previous code. Cryptography (via hash codes) is used to secure the authentication of the transaction source and removes the need for an intermediary actor. The combination of cryptography and blockchain technology together ensures that there is never a duplicate recording of the same transaction (Mougayar, 2015). A decentralized system transfers authority and trust to a decentralized virtual network and enables its nodes to continuously and sequentially record transactions containing data on a public “block,” thereby creating a unique “chain”.

Proof of Work

The foundation on which the blockchain operates is the key concept called “proof-of-work”. The “proof of work” concept is a “right” to participate in the blockchain system. It is manifested as a barrier that prevents users from changing records on the blockchain without re-doing the proof of work. Additionally, the “proof-of-work” concept is secured through the tenacity of cryptographic hashes that ensure its authenticity. The steps in which the processing network and proof-of-work operates are as follows (Nakamoto, 2008):
1) New transactions are broadcast to all nodes;
2) Each node collects new transactions into a block;
3) Each node works on finding a difficult proof-of-work for its block;
4) When a node finds a proof-of-work, it broadcasts the block to all nodes;
5) Nodes accept the block only if all transactions in it are valid and not already spent;
6) Nodes express their acceptance of the block by working on creating the next block in the chain, using the hash of the accepted block as the previous hash.
In addition, nodes always consider the longest chain to be the correct one and will keep working on extending it. If two nodes broadcast different versions of the next block at the same time, some nodes may receive one or the other first. In that case, they work on the first one they received, but save the other branch in case it becomes longer. The tie will be broken when the next proof-of-work is found which results into one branch becoming longer than the other. The nodes that were working on the other branch will then switch to the longer one.
Furthermore, new transaction broadcasts do not necessarily need to reach all nodes. As long as they reach many nodes, they will get into a block sooner or later. Block broadcasts are also tolerant when it comes to dropped messages. If a node does not receive a block, it will request it when it receives the next block and realizes it missed one.

RESEARCH QUESTIONS

To increase the reproducibility, transparency and trustworthiness of scientific studies (and by this means reducing dishonest practices), this project investigates whether the blockchain technology can be used to ensure a level of trust in a decentralized fashion. Therefore, processes and descriptions of the blockchain technology will be described in this research project to log and track the progress of scientific studies.
To study these research questions, a prototype will be developed and accompanied by several walkthrough examples. A technical evaluation of the prototype will take place in a later stadium of this research project (see the proposed timeline for the project schedule in section 6). Moreover, taking these main activities as our stepping stone leads us to the following research question: How can the blockchain technology be used to improve the reproducibility, transparency, and trustworthiness of scientific studies?

To answer this research question, different subquestions are defined. The answers to these questions will be used to answer the main research question. The subquestions are as follows:
 Is the blockchain a suitable technology for pre-announcements of studies to eliminate or alleviate publication bias?
 Is the blockchain a suitable technology for an open and decentralized system of post-publication reviews?
 What are the limitations that arise from the blockchain technology in regards to the reproducibility and trustworthiness of scientific studies?

RESEARCH METHODOLOGY

Approach

For this research project, a literature study will be conducted first in which information about the operation of several blockchain technologies such as multichain, private and public blockchains etc. will be gathered (see Greenspan, G;Bitfury Group et al.). The literature study serves as a prominent research instrument when designing and developing a prototype later on as it will give more technical background information on blocks, transactions and so forth. Moreover, related processes of the blockchain technology (and the activities of author editors, reviewers of papers etc.) will be described and mapped to a system concept.

The Engineering Research Method

The blockchain driven system will be developed through mockups and use cases to identify, clarify, and organize system requirements3. In addition, the system will be developed as a prototype by using the JustInMind prototype tool. The prototyping tool is an engineering tool for web and mobile app prototypes and high-fidelity website wireframes. It offers capabilities found in diagramming tools such as drag and drop placement, re-sizing, formatting and export/import of widgets. In addition, it has features for annotating widgets and defining interactions such as database simulation with real data, linking, animations, conditional linking, show/hide elements, and so forth (Wikipedia, 2015).

The Qualitative Research Method

After the development of the prototype, the user acceptance will be measured through evaluation. The evaluation results will be acquired by sending out questionnaires in a mailing list with the target group which mainly consists of academics. Additionally, the acquired data based on the questionnaires will be analyzed to see whether there are limitations w.r.t. the blockchain driven system. A qualitative case study will also be performed to find out how the blockchain technology could be applied to a particular situation given the published data of a scientific study.

PLAN: PROPOSED TIMELINE

The proposed timeline of this master project can be seen in Appendix A - Table 1. The tasks mentioned in Table 1 are clarified in Table 2 of Appendix B. Next to the project there will be two courses of 6 ECTS, given in period four and five. Moreover, a meeting with the master supervisor is scheduled for each week. However, meetings will take place every two weeks in the beginning of the research project. If more meetings are necessary, an extra appointment will be made by e-mail. Lastly, meetings will also take place on Skype due to the absence of the supervisor in March.
_______________________________
ACKNOWLEDGMENTS

I would like to express my gratitude to assistant professor Tobias Kuhn who was responsible for the feedback when writing this report. The feedback contained several creative insights and remarks to complete the final report.

REFERENCES

Iqbal SA, Wallach JD, Khoury MJ, Schully SD, Ioannidis JPA. 2016. Reproducible Research Practices and Transparency across the Biomedical Literature. PLoS Biol 14(1): e1002333. doi:10.1371/journal.pbio.1002333
Ioannidis JPA (2014) How to Make More Published Research True. PLoS Med 11(10): e1001747. doi:10.1371/journal.pmed.1001747
Nosek BA, Spies JR, Motyl M. 2012. Scientific Utopia: II. Restructuring Incentives and Practices to Promote Truth Over Publishability. Perspectives on Psychological Science 7(6) 615–631: DOI: 10.1177/1745691612459058
OECD (2015). “Making Open Science a Reality”. OECD Science. Technology and Industry Policy Papers, No. 25. OECD Publishing, Paris. http://dx.doi.org/10.1787/5jrs2f963zs1 en
Peters MA. Open Science, Philosophy and Peer Review (Editorial). Educational Philosophy and Theory. 2014. Vol. 46, No.3, 215-219, http://dx.doi.org/10.1080/00131857.2013.7812 96
Nielsen M. How the Bitcoin Protocol Actually Works. 2013. http://www.michaelnielsen.org/ddi/how-the-bitcoin- protocol-actually-works/
Mougayar W. Understanding the Blockchain. 2015. http://radar.oreilly.com/2015/01/understanding-the- blockchain.html
Nakamoto S. “Bitcoin: A peer-to-peer electronic cash system. 2008. [Online]. Available: http://www.bitcoin.org/bitcoin .pdf
Wikipedia. 2015. Justinmind Prototyper. Retrieved 19th of January 2016 from https://en.wikipedia.org/wiki/Justinmind_ Prototyper
Pathak A, Intratat C. 2012. Use of Semi-Structured Interviews to Investigate Teacher Perceptions of Student Collaboration. Malaysian Journal of ELT Research 8 (1), 1-10.
Greenspan G. 2015. Multichain Private Blockchain – White Paper. DOI=http://www.multichain.com/download/MultiChain- White-Paper.pdf
Charlon, F. 2016. Openchain Documentation. DOI= https://media.readthedocs.org/pdf/openchain/latest/ openchain.pdf
Bitfury Group, Garzik, J. 2015. Public versus Private Blockchains DOI (part 1 and 2)=http://bitfury.com/content/5-white- papers-research/public-vs-private-pt1-1.pdf and http:// bitfury.com/content/5-white-papers-research/public-vs- private-pt2-1.pdf
