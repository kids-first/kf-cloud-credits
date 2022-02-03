# Kids First Cloud Credit Program
## Managing Cloud Computing Costs
_Note: For an introduction to the principles of cloud computing, cost estimation, and the concept of __storage__ and __compute__, see our documentation on [Estimating Cloud Computing Costs](https://github.com/kids-first/kf-cloud-credits/blob/main/estimatingcosts.md#principles-of-cloud-computing-costs)._

### Managing Billing Groups on CAVATICA
Work in CAVATICA is organized around the concept of _projects_. Each project contains the files, workflows, and output that a set of collaborators have access to. Each project is also assigned to a ___billing group___. Any costs associated with storage or compute in that project are billed to the assigned billing group. Each project may only have one billing group, but a billing group can support multiple projects. For example, two users in the same research group could each have their own private workspace as well as a third, shared space for comparison, all under the single billing group.

Allocated cloud credits will be provided to you through a billing group established by the Kids First DRC. This billing group will have a limit at the amount you are allocated. Once that limit is reached, no further analyses can be submitted.

Users can review costs in the billing group by selecting `Payments` under the drop-down menu in the top right of the screen. New users can also be added to the billing group under this same menu - for example, a new collaborator joining a project.

<img src="https://github.com/kids-first/kf-cloud-credits/blob/main/assets/payments.png" width="400" align="center">


Detailed directions for managing billing groups on CAVATICA are available in [here within CAVATICA's support center](https://docs.cavatica.org/docs/manage-billing-groups).

---
### Cost-Saving Strategies
- Reduce storage costs by **archiving files** that you are not actively using. Select the files you wish to archive in the project and choose `Archive` under `More actions...`. Full details are included in [CAVATICA's support center](https://docs.sevenbridges.com/docs/file-archiving-overview).
- Use **spot instances** while running workflows. Using spot instances may require a waiting for resources to come available in the cloud, but the computational cost will be much reduced. Learn more about spot instances [**here**](http://docs.cavatica.org/docs/about-spot-instances).
Choose to run spot instances under the `Execution Settings` tab as you select the inputs for your task.
- Use the **suspend time** feature in the Data Cruncher. If you leave your analysis running, it will accrue costs, even if you aren't actively using it. This is analogous to leaving the lights on in a room with no one in it. Choose `Suspend Time` in the Compute Requirements. If your analysis is inactive for the length of time you set, it will automatically save everything and shut down.

---
### Further Reading on Cloud Costs
For further details on cloud infrastructure pricing, please see [this documentation in CAVATICA's support center](https://docs.cavatica.org/docs/cloud-infrastructure-pricing).
