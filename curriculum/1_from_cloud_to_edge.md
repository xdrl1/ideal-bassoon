# 1. From Cloud to Edge

> **Pre-requirements**: None.
>
> **Learning Objective**: Students will be familiar with topics including cloud computing, Internet of Things (IoT) and edge computing, understand the motivations, advantages, and challenges of leveraging edge computing.
>
> **Comments**:

Cloud computing aims to pack computing resources into services empowering users to access high-performance servers for data processing that is usually overburdened or inconvenient to handle on local devices, and pay for exactly what they consume on demand. However, network infrastructure highly restricts the application scope of cloud computing, especially for tasks with latency (returning results on time) and usability (processing big data) concerns. Hence, we offload part of the computation to user devices. In other words, computation occurs partially at network edges instead of completely at network centers (cloud). This new computation paradigm is termed as *edge computing*. In this chapter, we first provide a brief introduction to cloud computing, and then discuss its limitations. Next, we give explanations on edge computing, discuss why it can address the issues of cloud computing, and list additional advantages and current challenges when computing happens at edges.

## 1.1 Cloud Computing

## 1.2 Constraints of Cloud Computing

## 1.3 Edge Computing

## 1.X Wrap-up

*Cloud computing* combines data center hardware and software to provide elastic computing resource allocation as services, pricing in a pay-as-you-go manner [^1]. The benefits of such technologies are two-fold. On the one hand, end users can easily access high-performance servers and obtain processed data in a short time for their occasional but huge computation demand. On the other hand, cloud providers leverage virtualization to multiplex their servers for a large number of users, increasing equipment utilization and profitability. Therefore, commercial services based on cloud computing have flourished in the 2010s, giving birth to many famous products, including Microsoft Azure, AWS, DigitalOcean, Google Cloud, etc.

However, cloud computing relies heavily on network that is hard to ensure fast and stable responses for latency-sensitive tasks. Consequently, real-time systems (e.g., visual guiding service, autonomous cars) meet challenges to utilize computing resources on cloud [^2]. Worse still, network infrastructure is built much slower than data growth, making it increasingly time-consuming to transfer big data to cloud servers for common data-intensive tasks [^3].

Therefore, compared with *cloud* locates at the network *center*, processing data (partially) at the network *edges* could address both latency and usability issues discussed above. We term this new paradigm as *edge computing*. The emergence of edge computing is benefited from the continuous energy efficiency improvement of embedded devices. Edge devices with sufficient computing power could push processed intermediate data to cloud to save bandwidth, or even complete data processing entirely locally. Moreover, users can also keep/process sensitive data entirely on their own edge devices, such as personal health data on wearable electronics, to ensure privacy.

Nevertheless, edge devices are usually resource-constrained w.r.t. energy supply, storage, computational capability, and battery life. Hence, we need a series of optimization technologies to make computation tasks suitable for edge computing.

***Bibliography***

[^1]: Fox, A., Griffith, R., Joseph, A., Katz, R., Konwinski, A., Lee, G., Patterson, D., Rabkin, A., Stoica, I., & others. (2009). Above the clouds: A berkeley view of cloud computing. In Dept. Electrical Eng. And Comput. Sciences, University of California, Berkeley, Rep. UCB/EECS (Vol. 28, Issue 13, p. 2009).
    
[^2]: Varghese, B., Wang, N., Barbhuiya, S., Kilpatrick, P., & Nikolopoulos, D. S. (2016). Challenges and Opportunities in Edge Computing. 2016 IEEE International Conference on Smart Cloud (SmartCloud). https://doi.org/10.1109/SmartCloud.2016.18
    
[^3]: Shi, W., Cao, J., Zhang, Q., Li, Y., & Xu, L. (2016). Edge Computing: Vision and Challenges. In IEEE Internet of Things Journal (Vol. 3, Issue 5, pp. 637–646). IEEE. https://doi.org/10.1109/JIOT.2016.2579198
