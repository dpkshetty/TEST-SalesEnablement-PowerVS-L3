??? Important "Important information about the demonstration environment!"
    In this demonstration environment, full access to the IBM Cloud account is NOT provided. In the steps that follow, you will NOT have the ability to create, edit, or delete resources in the IBM Technology Zone environment. Steps are provided to get familiarity with different PowerVS feature(s).
    
A shared processor pool (SPP) is a pool of processor capacity that is shared between a group of virtual server instances. Unlike a virtual server instance that has a dedicated and defined maximum amount of processing capacity, you can set the reserved cores in SPP that is available at the pool level. SPPs are used to control software licensing costs by limiting the number of processors an uncapped VSI can use.

Learn more about SPPs <a href="https://cloud.ibm.com/docs/power-iaas?topic=power-iaas-manage-SPP" target="_blank">here</a>.

1. Click the **Shared processor pools** (**A**) option in the side menu under the {{powerVS.serviceInstanceName}} workspace.

    ![image](https://github.com/user-attachments/assets/dbfecb8a-9c0f-4591-8fe8-9cf9ebcee9e4)

2. Click **Create pool +** (**A**).

    ![image](https://github.com/user-attachments/assets/87fbafcf-6fe6-42e3-aa53-6bd6b8f55262)

3. Enter a name in the **Name** (**A**) field and then click **Continue** (**B**).

    ![image](https://github.com/user-attachments/assets/a757051d-a6a1-4dde-87c4-26f0c7db4e7a)

4. Select a **machine type** (**A**) and specify the number of **reserved cores** (**B**). Reserved cores is the total number of cores reserved for the processor pool's usage. Click **Finish** (**C**).

    ![image](https://github.com/user-attachments/assets/f855755b-02f3-4684-a387-98d113c611cf)
    
When actually provisioning an SPP, you would next accept the terms and conditions and create the SPP. After the SPP is provisioned, clients specify the SPP when a new VSI is created. 

7. Click **Cancel**.

    ![](_attachments/SPPProvision5.png)

8. Click the **Pool placement groups** tab.

    ![](_attachments/SPPtablePPGtab.png)

    Pool placement groups are a set of shared processor pools with a single colocation policy. The policy determines the host in which an SPP in the group is deployed in relation to others in the group.

    Learn more about pool placement groups <a href="https://cloud.ibm.com/docs/power-iaas?topic=power-iaas-manage-SPP#configure-SPP-PG" target="_blank">here</a>.

9.  Click **Create group +**.

    ![](_attachments/SPP-PPG.png)

10. Enter a **Name** for the pool placement group.

    ![](_attachments/SPP-PPG-1.png)

11. Select the colocation policy of either **same server** or **different server**.

    The **same server** option specifies that all VSIs in this placement group are placed on the same server. This is known as an **affinity** policy.

    The **different server** option specifies that all VSIs in this placement group are placed on different servers. This is also known as an **anti-affinity** policy.

    ![](_attachments/SPP-PPG-2.png)

12. Click **Cancel**

    ![](_attachments/SPP-PPG-3.png)
    
Affinity and anti-affinity policies are used to help build high availability (HA) and disaster recovery (DR) deployments. Learn more about High Availability (HA) and Disaster Recovery (DR) options in PowerVS <a href="https://cloud.ibm.com/docs/power-iaas?topic=power-iaas-ha-dr" target="_blank">here</a>.
