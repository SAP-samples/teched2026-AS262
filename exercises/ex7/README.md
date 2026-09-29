# Exercise 7 - Trace the run

In this exercise, you will follow the agent's run in the application log.

## Exercise 7.1: Follow the run in the application log

After completing these steps you will know where to look when an insight is missing or looks wrong.

<!-- TODO: confirm the navigation path, the object and subobject to filter on, and the exact log messages. -->

1. In **Application Jobs**, select *EMA run XX* and open its **Application Log**.
2. Find the entries for the alert CN1310 ASSEMBLY, CW36 2026.
3. Follow the run from start to end: which alerts were picked up, which instruction steps ran, and when the insight was stored.

**Expected result:** The log shows 9 alerts picked up for Capacity Overload Subscription, the instruction steps executed for each, and a success message when the insights were stored in IBP.

> [!NOTE]
> **Why it matters:** When an insight is missing or looks wrong, the application log is the first place to look. It tells you whether the alert was picked up, which step failed, and what data the agent saw.

## Summary

You have now configured, validated, run and traced EMA end to end.

Continue to - [Exercise 8 - Bonus exercises](../ex8/README.md)
