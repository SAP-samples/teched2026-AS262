# Exercise 1 - Meet the alert

In this exercise, you will look at the Capacity Overload alert that EMA will analyse, and see it the way a planner does.

## Exercise 1.1: Check the alert definition and the alert list

After completing these steps you will have seen the alert rule, your subscription, and the open alerts in your planner workspace.

1. Log on to SAP IBP with your user PLANNER_XX.
2. Open the app **Define and Subscribe to Custom Alerts** and open the alert definition **Capacity Overload**.
3. On the **Definition Information** tab, look at **Alert Rules**. The rule is *Capacity Consumption (%)/Time Series greater than 100, Absolute*.
4. Scroll to **Sharing**. Check that your user is listed, or that you are a member of the user group **EMAGENT**.
5. Open the app **Planner Workspaces** and open **PWS for Supply Planner (TechEd 2026)** (planning area HPAEMAGENT).
6. Open the workbook **Capacity**.
7. On the left, click the **Alerts** icon (the bell) and open **Capacity Overload Subscription**.

**Expected result:** The alert list shows resource CN1310 ASSEMBLY with 6 alerts (CW36 to CW41 2026, between 164% and 176%) and CN1310 PACK with 3 alerts (CW37 to CW39 2026, around 130%).

> [!TIP]
> **Think about it:** Pick CN1310 ASSEMBLY in CW36. How many minutes of capacity are missing, and what would you check first to explain it? Note your answer; you will compare it with the agent's answer in Exercise 6.

## Summary

Now that you have seen the alert and its data, you are ready to set up an agent to analyse it.

Continue to - [Exercise 2 - Configure your agent](../ex2/README.md)
