---
title: "Decentralized Governance and Voting"
permalink: /blockchain-basics/decentralized-governance-voting/
excerpt: ""
last_modified_at: 2018-11-25T22:21:33-05:00
sidebar:
  nav: "book"
toc: true
---

# Decentralized Governance and Voting

People have been self-organizing since before recorded human history, but until the Bitcoin network was launched, there had been limited successful attempts to build communities agreeing on rules and incentives without relying on central organization. With the blockchain, once theoretical forms of governance that removed central organization or that required a certain amount of frictionless transactions to occur are now in experimentation.

## **How is Decentralized Governance Possible?**

Readers may be familiar with the standard types of governments and governance - a monarch ruling a country, a parliament or congress, a military with its hierarchy of commanding officers. All of these examples are a different form of governance, and are replicated in religious organizations, companies, athletic clubs, hobby groups, and schools across the globe. Nearly every one of these models require the establishment of a hierarchy, where certain individuals have or are endowed with power in order to make decisions or carry out specific actions on behalf of the whole. That power may come from votes of members of the organization, or come from an individual or group of individuals who have found a means to obtain that power from the group. Without getting into a full history of the philosophy of government, hierarchies tend to bring order and speed to governance, while compromising individual participation in decision-making.

As communication networks have evolved, it has become easier to gauge the opinion of those who choose the decision makers or the policies. This is particularly true for democratic systems of government, and most true for systems where the philosophy of "one person, one vote" is adhered to. When communication networks were slower, under a democratic "one person, one vote" system, the fastest way to get everyone's opinion in a town of 300, would be to call a town meeting and ask for everyone to voice their opinion or vote on a matter - like the budget for the local school. If someone was sick, or away on business, they would either have to have known the information ahead of time and passed on their vote to another citizen of the town, or abstain from the voting. Over a certain count of individuals, the process of collecting everyone's vote became very difficult and time consuming, preventing more than a certain number of questions to be asked at a time.

Imagine that we keep the model of the town meeting, where everyone comes together to legislate via direct democracy. Getting everyone on Earth in the same room at the same time would be impossible. Above a certain number of individuals we would soon find ourselves unable to make decisions - we wouldn't be able to solicit everyone's opinion, and thus would be limited to giving everyone prepared information that we would ask them to vote on. And we would have to decide who would be given the power to organize and prepare the motions that we were voting on. Fortunately, since communication networks are now much faster, we can use the Internet to secure everyone's vote \(provided they have access to the internet\), though soliciting opinion would still require some pre-arranged parameters of when individuals can submit proposals, how those proposals would be prioritized, and who would be responsible for the collection of these proposals to vote on. But we can see how a direct form of democracy could be possible on a potentially global scale - that is if we could trust the central authority counting our votes to be fair and honest. Depending on which country you currently reside in, you may have reservations about the ability for a fair election, even on the internet, due to a regime that may have a history of voter manipulation, or malicious actors who would be able to hack the system and change the results, making the outcome look as if it were the will of the people.

This is where the blockchain enters the equation, providing cryptographic protocols, decentralized governance, and economic incentives to answer some of these questions. We will tackle each issue, and introduce what new forms of governance that it allows if that form of governance is something that has been defined.

## **Problem 1: Trust**

In this scenario, our central government becomes a blockchain, which is stood up and a nodes are placed on computers around the world.

Say we are a multi-national charity and we decide that we want every person within our corporation to have an equal vote on how and where we spend our funds. There are many good projects we could spend our funds, so deciding how our pooled resources should be apportioned is going to be necessary to increase our impact while respecting the wishes of the group. Anyone who wants to join our charity would be given access to a smart contract on it, where they could deposit their money. When it comes time to vote on how we spend that money, we each submit a vote.

How can we trust that the votes are what we say they are? If everyone had a public and private key, they could sign their vote with their private key and submit that transaction to the blockchain. All of the votes would be distributed across all nodes, so that the entire public could see the votes. Then the public keys could be used to unlock them, count the votes, and declare a winner. The added benefit is that everyone can verify the votes were counted correctly. What has just been described is a form of **commit-reveal voting**, where votes are committed to a location and then revealed for all to see and verify.

Just because the votes are public does not mean that the identities have to be. As indicated in the previous section, Self Sovereign Identity and Reputation, it is possible to just verify that the individual who voted is allowed to vote in this election, and not identify who they are.

## **Problem 2: Knowlegeability of the Electorate**

If our non-profit was debating whether to use our funds to help with a chemical waste cleanup project or carbon recapture, I might not have any idea of how to vote. The proposals might outline the amount of funds needed and be specific as possible, but I may not be an expert in this area, and instead would look to a knowledgeable source to inform me.

What if one of my friends were an environmental engineer and was very knowledgeable about what is required for both of these projects, and was also extremely interested in taking the time to dig into the details? Well, it would be great if I could delegate my vote to her, so once she digs into the details and makes a decision about the best project, she can vote for me. I want to borrow on her knowledge and expertise in the area, but only for this specific vote.

With the blockchain, I could pass my voting authority over to her for this vote via a token \(essentially a tokenized vote\), which would allow her to cast a vote for me. I could give her this token for other similar votes, or decide that after this vote, I want to ensure that I vote the next time.

What is described above is often called [**Liquid Democracy**](https://en.wikipedia.org/wiki/Delegative_democracy), essentially a flux state between direct democracy and representative democracy that is constantly evolving.

## **Problem 3: Adapting the Rules of Governance**

A government or organization that gives power to some set of individuals that comprise it typically writes up its rules for governing - this can be using Robert's Rules of Order to run a recurring meeting, a charter, or a constitution. Similarly, the rules and procedures used for governance on the blockchain can be written, and those written rules could be put into code and enforced through the structure of a smart contract.

Now let's say that that our non-profit has a group of individuals that decide they would prefer to only use their money for projects that help clean up oil spills. It would be painful to untangle all of the finances and voting procedures, right? Well, we could institute a **hard fork**, where starting at a certain block number, the group of investors who want to only donate their money to cleaning up oil spills would be able to do so, and keep the prior history of the transactions up to this point. And the original group would continue on, but without those individuals who decided to break off. In a hard fork, the miners would only accept transactions from certain addresses, thus forking the blockchain. This would allow both new groups to keep the historical records of the group and the current voting mechanisms, but change the membership.

## The Big Idea

It is assumed that most models of governance and voting can be moved to the blockchain, though we have not specifically confirmed this claim. One of these models - Futarchy - we will cover in more detail in the next section \(Prediction Markets\). However, the general idea is that prediction markets can be used as part of a governance structure. The blockchain is not part of the model, but as a platform, it allows for a Futarchy to be build on top of it. Similar ideas are in place for liquid democracy and other forms of governance, which did not seem possible to do on a large, distributed scale until blockchain technology had grown in its adoption. New governance structures and voting paradigms are emerging, both from historical works on governance that were theoretical in nature, as well as new forms that have evolved out of prior experiments. This is just a cursory overview of these governance models and voting mechanism that can occur on the blockchain. A key takeaway is that decentralized governance via the blockchain is at the intersection of philosophy and technology, where the potential for individuals to have a greater voice in governance is possible.

