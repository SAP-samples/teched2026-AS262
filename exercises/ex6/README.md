# Exercise 6 - Review the insights

In this exercise, you will review the agent's insights in your planner workspace and check them against the data.

## Exercise 6.1: Read and check the insight

After completing these steps you will have compared the agent's analysis with the worksheet data and with your own answer from Exercise 1.

1. Go back to **PWS for Supply Planner (TechEd 2026)** and open the workbook **Capacity**.
2. Set the filters **Time Periods** = *CW36 M9 2026* and **Resource ID** = *CN1310 ASSEMBLY*, then choose **Go**.
3. Find the **Exception Management** panel. It shows when the insights were generated and one card per insight.
4. Open the card **Assembly Capacity Overload CW36 2026** and read the mitigation.
5. Choose **Data Details** to see the data the agent used, and **Show Proposal Details** to see the proposed change.
6. Check the agent's numbers against the **Capacity** grid above the panel: Capacity Consumption (PDS) and Final Available Capacity (MIN) for CW36.
7. Compare the agent's analysis with your own answer from Exercise 1.
8. Give the proposal a thumbs up or thumbs down.

**Expected result:** The card states that CN1310 ASSEMBLY is at 164.19% in CW36, with 1,600 minutes of available capacity against 2,627 minutes of consumption. The capacity gap to close is 1,027 minutes (2,627 - 1,600).

> [!NOTE]
> **Why it matters:** The planner stays in control. EMA removes the searching and correlating, but the decision to accept a proposal is yours, and your feedback helps improve future proposals.

## Summary

Now that you have reviewed the insight, you will trace how the agent produced it.

Continue to - [Exercise 7 - Trace the run](../ex7/README.md)
