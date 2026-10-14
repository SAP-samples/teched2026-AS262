# Exercise 2 - Run sanity checks and enrich the BOM

In this exercise, you will let the agent check the BOM for gaps, predict the missing components and their values, and add them to the BOM with a change number.

The suggested starting point for this exercise is the end of Exercise 1, with your BOM created and the agent showing options for next steps.

## Exercise 2.1: Predict missing components and values

After completing these steps you will have seen the agent's proposals for the components and values that are missing from your BOM.

<!-- TODO: confirm the exact wording of the options and quick replies, and add screenshots to exercises/pso/ex2/images/. -->

1. From the next-step options, choose the quick reply **Sanity checks**.
2. The agent displays **2 options** for doing sanity checks. Choose the quick reply **Predict missing components**.
3. The agent displays the **possible missing components** and options for next steps. Choose the quick reply **Predict missing values**.
4. The agent displays the **recommended values** for the missing components and options for using the proposed components and values.

**Expected result:** The agent lists the components that are likely missing from your BOM and, for each, a recommended value, together with options to use the proposed components and values.

> [!NOTE]
> **Why it matters:** Sanity checks turn an incomplete BOM into a complete one. The agent predicts what is missing and what values fit, but the proposals stay proposals until you choose to apply them in the next step.

## Exercise 2.2: Add the missing components with a change number

After completing these steps you will have added the proposed components to your BOM under a proper change number.

1. From the options for using the proposed components and values, choose the quick reply **Add missing components**.
2. The agent displays options for adding the missing components to the BOM. Choose the quick reply **Edit with change number**.
3. The agent asks for the **change number** to be used. Enter the change number.
   <!-- TODO: confirm the change number to use in the session; the test script uses the placeholder xyz. -->

**Expected result:** The agent displays a **success message** with details about the **added BOM component data**, an **updated BOM summary**, and **options for next steps**.

> [!NOTE]
> **Why it matters:** Changes to a BOM are tracked against a change number, so every edit is traceable. The agent applies your proposals only after you provide a valid change number.

## Summary

Now that your BOM is complete and up to date, you will summarize it, explode it, and finally delete it.

Continue to - [Exercise 3 - Summarize, explode, and delete the BOM](../ex3/README.md)
