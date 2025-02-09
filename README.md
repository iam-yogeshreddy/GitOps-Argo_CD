# GITOPS-ARGO-CD

𝐖𝐡𝐚𝐭 𝐢𝐬 𝐆𝐢𝐭𝐎𝐩𝐬 :

GitOps is a set of practices that uses GIT as a single source of truth to deliver applications and infrastructure.

𝙋𝙧𝙞𝙣𝙘𝙞𝙥𝙡𝙚𝙨 𝙤𝙛 𝙂𝙞𝙩𝙊𝙥𝙨 :

1.𝘿𝙚𝙘𝙡𝙖𝙧𝙖𝙩𝙞𝙫𝙚 : 

A system managed by GitOps must have its desired state expressed declaratiely.

2. 𝐕𝐞𝐫𝐬𝐢𝐨𝐧𝐞𝐝 𝐚𝐧𝐝 𝐈𝐦𝐦𝐮𝐭𝐚𝐛𝐥𝐞 :

Desired state is stored in a way that enforces immutability, versioning and retains a complete version history.

3. 𝗣𝘂𝗹𝗹𝗲𝗱 𝗔𝘂𝘁𝗼𝗺𝗮𝘁𝗶𝗰𝗮𝗹𝗹𝘆 :

Software agents automatically pull the desired state declarations from the source.

4. 𝗖𝗼𝗻𝘁𝗶𝗻𝘂𝗼𝘀𝗹𝘆 𝗥𝗲𝗰𝗼𝗻𝗰𝗶𝗹𝗲𝗱 :

Software agents continuosly observe actual system state and attempt to apply the desired state.



𝐀𝐝𝐯𝐚𝐧𝐭𝐚𝐠𝐞𝐬 𝐨𝐟  𝐆𝐢𝐭𝐎𝐩𝐬 :

-> Security

-> Versioning (track of changes)

-> Auto Upgrades 

-> Auto Healing of any unwanted changes

-> Continuos Reconcillation


𝐀𝐫𝐠𝐨𝐂𝐃 :

Argo CD is a declarative, GitOps-based continuous delivery tool for Kubernetes. It ensures that applications running in a cluster match the desired state defined in a Git repository.

𝘼𝙧𝙘𝙝𝙞𝙩𝙚𝙘𝙩𝙪𝙧𝙚 𝙤𝙛 𝘼𝙧𝙜𝙤 𝘾𝘿 :

𝗔𝗿𝗴𝗼𝗖𝗗 𝗖𝗼𝗺𝗽𝗼𝗻𝗲𝗻𝘁𝘀 :

1. API Server: Exposes the API used by the Web UI, CLI, and CI/CD systems.

2. Repository Server : Connect to git and get the state

3. Application Controller : Connect to kubernetes and get the state

4. Redis : It's used for caching API responses, managing authentication sessions, handling events, and improving performance in large-scale deployments

5. Dex : Provides Single Sign-On (SSO) using OAuth, LDAP, SAML, or GitHub. And manages Role-Based Access Control (RBAC) for Argo CD users.


𝗔𝗿𝗰𝗵𝗶𝘁𝗲𝗰𝘁𝘂𝗿𝗲 :


![image](https://github.com/user-attachments/assets/b4031d80-2426-4fc9-a531-afdd49f7c2e2)


![image](https://github.com/user-attachments/assets/4184a98f-4193-47e7-b392-541335da3375)
