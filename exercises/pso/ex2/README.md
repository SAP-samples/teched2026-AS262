# Exercise 2 - Run sanity checks and enrich the BOM

In this exercise, you will let the agent check the BOM for gaps, predict the missing components and their values, and add them to the BOM.

The suggested starting point for this exercise is the end of Exercise 1, with your BOM created and the agent showing options for next steps.

## Exercise 2.1: Predict missing components and values

After completing these steps you will have seen the agent's proposals for the components and values that are missing from your BOM.

<!-- TODO: confirm the exact wording of the options and quick replies, and add screenshots to exercises/pso/ex2/images/. -->

1. From the next-step options, choose the quick reply **Sanity checks**, or type the prompt `Run sanity checks`.
2. The agent displays **2 options** for doing sanity checks. Choose the quick reply **Predict missing components**, or type the prompt `Predict missing components`.
3. The agent displays the **possible missing components** and options for next steps. Choose the quick reply **Predict missing values**, or type the prompt `Predict missing values`.
4. The agent displays the **recommended values** for the missing components and options for using the proposed components and values.

**Expected result:** The agent lists the components that are likely missing from your BOM and, for each, a recommended value, together with options to use the proposed components and values.

> [!NOTE]
> **Why it matters:** Sanity checks turn an incomplete BOM into a complete one. The agent predicts what is missing and what values fit, but the proposals stay proposals until you choose to apply them in the next step.

## Exercise 2.2: Add the missing components

After completing these steps you will have added the proposed components to your BOM.

1. From the options for using the proposed components and values, add the missing components. If a quick reply such as **Add missing components** is available, choose it; otherwise type the prompt `Add the missing components to the BOM`.
2. _(Optional)_ If the agent asks which components to add, enter the prompt `all high confidence`.
3. The agent asks how to apply the changes and offers the quick replies **Edit directly** and **Edit with change number**. Choose the quick reply **Edit directly**, or type the prompt `Edit directly`.

**Expected result:** The agent displays a **success message** with details about the **added BOM component data**, an **updated BOM summary**, and **options for next steps**.

> [!NOTE]
> **Why it matters:** The agent applies your proposals only after you choose to add them, so the predicted components and values stay proposals until you decide to write them to the BOM.

## Summary

Now that your BOM is complete and up to date, you will summarize it, explode it, and finally delete it.

Continue to - [Exercise 3 - Summarize, explode, and delete the BOM](../ex3/README.md)
