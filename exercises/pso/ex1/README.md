# Exercise 1 - Create a BOM from a file

In this exercise, you will start a conversation with the Product Structure Optimizer Agent in Joule and create a Bill of Materials (BOM) from a file.

## Exercise 1.1: Create the BOM by uploading a file

After completing these steps you will have created a BOM from an uploaded file and seen the agent's summary of the result.

<!-- TODO: confirm the exact wording of the three options and the quick replies, and add screenshots to exercises/pso/ex1/images/ (naming pattern 01_01_0010.png). -->

1. Open **Joule**.
2. Start a **new conversation**.
3. Enter: `@Product Design Assistant Can you create a BOM?`
4. The agent displays **3 different options** for creating a BOM. Choose **Upload a file**.
5. **Drop the file** into the drop area.
   <!-- TODO: confirm the file name and format of the sample BOM file provided for the session. -->
6. Press the button with the **send** icon to submit the file content to the agent.
7. The agent displays the **extracted BOM data** and a quick reply to trigger the BOM creation. Choose the quick reply **Proceed to create BOM**.

**Expected result:** The agent displays a **success message**, a **summary of the created BOM data** (header and components), and **options for next steps**.

> [!NOTE]
> **Why it matters:** The agent extracts a structured BOM from an unstructured file for you, but it does not create anything until you confirm with **Proceed to create BOM**. You review the extracted data first, so nothing is written without your agreement.

## Summary

Now that you have created a BOM, you will check it for gaps and enrich it.

Continue to - [Exercise 2 - Run sanity checks and enrich the BOM](../ex2/README.md)
