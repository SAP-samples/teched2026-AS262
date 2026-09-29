# Exercise 2 - Configure your agent

In this exercise, you will create your own agent and connect it to the planning area and the alert subscription.

## Exercise 2.1: Create the agent in Manage AI Agents

After completing these steps you will have an active agent EMA_XX that is linked to HPAEMAGENT and the Capacity Overload subscription.

1. Open the app **Manage AI Agents** and choose **Create**.
2. Enter the agent name **EMA_XX** (your number).
3. As **Agent User**, select the business user that is subscribed to the Capacity Overload alert.
   <!-- TODO: confirm whether participants select their own PLANNER_XX user or a shared agent user. -->
4. Set **Expiry of Mitigation Proposals (Days)** to 30.
5. On the **Planning Area** tab, add **HPAEMAGENT**.
6. On the **Alert Subscription** tab, add **Capacity Overload Subscription** (alert name: Capacity Overload).
7. Save and activate the agent.

**Expected result:** EMA_XX appears in the AI Agents list with status **Active**, one planning area (HPAEMAGENT) and one alert subscription. The **Agent Instruction** section is still empty; you fill it in Exercise 3.

> [!NOTE]
> **Why it matters:** The agent can only see alerts that its agent user is subscribed to, in the planning areas you assign. If the user, planning area and alert subscription do not line up, the agent finds nothing to work on.

## Summary

Now that you have an active agent, you will tell it how to analyse the alert.

Continue to - [Exercise 3 - Upload and validate the agent instructions](../ex3/README.md)
