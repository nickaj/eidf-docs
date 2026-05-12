# EIDF Portal

## An explainer for users used to working with SAFE.

There can be some confusion for users and PI's who have been used to using EPCCs [SAFE](https://safe.epcc.ed.ac.uk) system. Both the EIDF Portal and SAFE are interfaces to the same account and machine management systems.

- In SAFE users request to join a project, request an account on a machine and a preferred username in one step. This is because most HPC projects have a low number of machines available (often just one) and sudo permission can never be given. This simplifies things for the PI.
- In the EIDF Portal, users request to join a project and it is up to the PI to approve that request, then create the account for the user and map it to the relevant machine, plus make a choice over sudo permission for VMs. This is because the variety of machines and machine types in EIDF is much greater, some projects have tens of VMs, plus access to the Cerebras and GPU clusters, which the PI may wish to make available only to certain users.

## How to request to join a project

Log in to the [EIDF Portal](https://portal.eidf.ac.uk/) and navigate to "Projects" and choose "Request access".

Select the project that you want to join in the "Project" dropdown list - you can search for the project name or the project code, e.g. "eidf0123".

Now you have to wait for your PI or project manager to accept your request to join.

Once your request is accepted, the project manager creates an account for you and enables access to the machines that you require in your project.
You cannot request accounts, this has to be done by your project manager.
If you cannot see any accounts in the project after joining please get in touch with the PI or a project manager and ask them to create one for you.

