# Exercise 3 - Summarize, explode, and delete the BOM

In this exercise, you will ask the agent to summarize and explode your BOM, and then delete it with a human-in-the-loop confirmation.

The suggested starting point for this exercise is the end of Exercise 2, with your enriched BOM and the agent showing options for next steps.

## Exercise 3.1: Summarize and explode the BOM

After completing these steps you will have seen a summary of your BOM and its exploded structure.

<!-- TODO: confirm the exact wording of the quick replies, and add screenshots to exercises/pso/ex3/images/. -->

1. From the next-step options, choose the quick reply **Summarize this BOM**.
2. The agent displays a **summary of BOM header and component data** and options for next steps.
3. Choose the quick reply **Explode BOM**.
4. The agent displays the **exploded BOM** and options for next steps.

**Expected result:** The agent shows the BOM header and component summary, and then the fully exploded BOM structure, each with options for next steps.

> [!NOTE]
> **Why it matters:** Summarize gives you a quick overview of the header and components, while Explode shows the full multi-level structure. Both are read-only, so you can inspect the BOM as often as you like without changing it.

## Exercise 3.2: Delete the BOM with a human-in-the-loop confirmation

After completing these steps you will have deleted your BOM and confirmed the deletion explicitly.

1. Enter: `delete this BOM`
2. The agent displays a **human-in-the-loop confirmation** message.
3. Enter `Yes` to confirm the deletion request.

**Expected result:** The agent displays a **success message** for the BOM deletion and **options for next steps**.

> [!IMPORTANT]
> **Why it matters:** Deletion is a destructive action, so the agent never performs it on its own. It asks for an explicit confirmation first (human in the loop), and only deletes the BOM after you answer `Yes`.

## Summary

You have now created, enriched, summarized, exploded and deleted a BOM entirely through a conversation with the Product Structure Optimizer Agent, with the human in control at every step.

Back to the [overview](../../../README.md)
