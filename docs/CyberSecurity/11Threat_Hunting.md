# Threat Hunting
Threat hunting is a proactive cybersecurity technique that involves detecting the presence of threats that have not been discovered by regular security monitoring. This approach is different from incident response, which is reactive and involves responding to threats after they have been detected.

To start the threat hunting process, we begin by establishing a hypothesis based on threat modeling. This involves identifying potential events with higher likelihood and higher impact if they were to occur. By going through threat intelligence, we can create a hypothesis about the type of campaign or adversary group that might want to attack us.

Once we have our hypothesis, we move on to profiling threat actors and their activities. We rely heavily on threat intelligence to create scenarios that show how a prospective attacker might attempt an intrusion and what their objectives might be. This includes identifying the tactics, techniques, and procedures (TTPs) that the attacker might use, as well as their motivations and potential targets.

With our hypothesis and threat actor profile in hand, we can begin the actual threat hunting process. We use a variety of tactics and tools to detect and identify threats, including analyzing logs, process information, file system and registry changes from all the different hosts. This data is often consolidated in a security information and event management (SIEM) system to help us quickly correlate information and identify potential threats.

It's important to note that when threat hunting, we assume that existing rules have failed. This means that we're looking for threats that have bypassed existing monitoring systems, or that are not being detected by regular queries or rules. By doing so, we can identify previously undetected threats and take proactive measures to prevent them from causing harm.


Additional Source:
```
 https://www.youtube.com/watch?v=Ob9kSzk6gdY
```