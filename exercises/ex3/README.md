# Exercise 3 - Upload and validate the agent instructions

In this exercise, you will give your agent its instructions and validate them at design time.

Agent instructions tell EMA, step by step, how to analyse one alert. Each step does one thing: read key figure data, compute a value, or reason about the result.

## Exercise 3.1: Upload and validate

After completing these steps you will have a validated, active set of agent instructions for the Capacity Overload subscription.

<!-- TODO: confirm the final file name and where participants find it. -->

1. In your agent EMA_XX, go to the **Agent Instruction** section and create a new set of agent instructions for **Capacity Overload Subscription**.
2. Upload the instructions file from your desktop: `capacity_overload_instructions.json`.
3. Choose **Validate** and wait until validation is complete.
4. Open the **validation report** and look at its three parts:
    - **Flowchart**: the steps of your instructions and their order.
    - **Test data analysis**: a test run of the instructions against a real alert in HPAEMAGENT.
    - **Generated ABAP class**: the code EMA generated from your instructions.

**Expected result:** Validation completes without errors and the instructions show status **Active** next to Capacity Overload Subscription. The flowchart has one node per step in the JSON file.

> [!NOTE]
> **Why it matters:** Counts, sums and utilisation figures are computed by the generated ABAP code, not by the language model. The model is only used to reason about the computed results and to write the insight. That is why EMA's numbers can be checked against your worksheet.

## Summary

Now that you have validated instructions, you will see what happens when instructions contain a mistake.

Continue to - [Exercise 4 - What went wrong?](../ex4/README.md)
