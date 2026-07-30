# Cloud Concepts & Version Control Reflection

## 1. Cloud Services and Classifications

In my daily routine, I frequently rely on cloud-based applications for communication, storage, and digital transactions:

* **Messenger**: Classified as **Software as a Service (SaaS)** and deployed on a **Public Cloud**. It provides a complete, ready-to-use application for real-time messaging hosted on Meta's public infrastructure, requiring no management of underlying databases or servers on my end[cite: 1].
* **Google Drive**: Classified as **Software as a Service (SaaS)** and deployed on a **Public Cloud**[cite: 1]. It serves as a fully hosted solution for cloud storage and document sharing managed entirely by Google[cite: 1].
* **GCash**: Classified as **Software as a Service (SaaS)** and deployed on a **Public/Hybrid Cloud** setup[cite: 1]. It operates as an end-user fintech application accessible over the internet to perform financial transactions, with backend infrastructure, security, and payment gateways managed entirely by the service provider[cite: 1].

---

## 2. Importance of Git & GitHub in Cloud Projects

Version control platforms like Git and GitHub are critical when managing cloud infrastructure because modern cloud setups are frequently defined, configured, and managed through code[cite: 1]. Because cloud configurations directly impact server deployments, network security, and database access, maintaining precise control over this code is essential[cite: 1]. GitHub allows teams to collaborate smoothly through branches, where developers can build and test infrastructure updates independently before opening pull requests for team review[cite: 1]. This process ensures every change is thoroughly inspected before being applied to live environments[cite: 1]. Additionally, GitHub maintains a detailed, time-stamped history of all modifications, making it easy to track changes and identify who introduced specific configurations[cite: 1]. Most importantly, if a bad setting or bug causes system downtime, version control enables engineers to instantly roll back cloud resources to a previous stable commit, preventing prolonged outages and protecting vital infrastructure[cite: 1].
