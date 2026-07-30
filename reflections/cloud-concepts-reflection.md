# Cloud Concepts Reflection

## Cloud Services I Use & Identifying the Models

In my daily routine, I frequently rely on cloud-based applications for communication, storage, and digital transactions:

* **Messenger**: Classified as **Software as a Service (SaaS)** and deployed on a **Public Cloud**. It provides a complete, ready-to-use application for real-time messaging hosted on Meta's public infrastructure, requiring no management of underlying databases or servers on my end.
* **Google Drive**: Classified as **Software as a Service (SaaS)** and deployed on a **Public Cloud**. It serves as a fully hosted solution for cloud storage and document sharing managed entirely by Google.
* **GCash**: Classified as **Software as a Service (SaaS)** and deployed on a **Public/Hybrid Cloud** setup. It operates as an end-user fintech application accessible over the internet to perform financial transactions, with backend infrastructure, security, and payment gateways managed entirely by the service provider.

---

## Git & GitHub for Cloud Projects

Version control platforms like Git and GitHub are critical when managing cloud infrastructure because modern cloud setups are frequently defined, configured, and managed through code. Because cloud configurations directly impact server deployments, network security, and database access, maintaining precise control over this code is essential. GitHub allows teams to collaborate smoothly through branches, where developers can build and test infrastructure updates independently before opening pull requests for team review. This process ensures every change is thoroughly inspected before being applied to live environments. Additionally, GitHub maintains a detailed, time-stamped history of all modifications, making it easy to track changes and identify who introduced specific configurations. Most importantly, if a bad setting or bug causes system downtime, version control enables engineers to instantly roll back cloud resources to a previous stable commit, preventing prolonged outages and protecting vital infrastructure.
