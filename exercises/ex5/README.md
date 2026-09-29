# Exercise 5 - Run the agent

In this exercise, you will trigger EMA with an application job.

EMA does not run on its own. An application job triggers it for one planning area and one alert subscription.

## Exercise 5.1: Schedule the application job

After completing these steps you will have run EMA on the Capacity Overload alerts.

1. Open the app **Application Jobs** and choose **Create**.
2. As **Job Template**, select **Trigger Exception Management AI Agent**.
3. Change the **Job Name** to *EMA run XX*.
4. Under **Scheduling Options**, keep **Start Immediately** and the recurrence pattern **Single Run**.
5. Under **Parameters**, set:
    - **Planning area**: Integrated Business Planning (HPAEMAGENT)
    - **Alert subscription ID**: Capacity Overload Subscription
6. Choose **Schedule**.
7. In the job list, find *EMA run XX* and refresh until the job is finished.

<!-- TODO: add the expected run time, and confirm whether it is one insight per alert or grouped per resource. -->

**Expected result:** The job finishes successfully. Insights are written for the 9 Capacity Overload alerts.

> [!NOTE]
> **Why it matters:** In production you schedule this job to recur, for example after every supply planning run, so insights are ready when the planner starts the day.

## Summary

Now that the agent has run, you will look at what it found.

Continue to - [Exercise 6 - Review the insights](../ex6/README.md)
