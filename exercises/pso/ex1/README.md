# Exercise 1 - Create a BOM from a file

In this exercise, you will start a conversation with the Product Structure Optimizer Agent in Joule and create a Bill of Materials (BOM) from a file.

## Exercise 1.1: Create the BOM by uploading a file

After completing these steps you will have created a BOM from an uploaded file and seen the agent's summary of the result.

<!-- TODO: confirm the exact wording of the three options and the quick replies, and add screenshots to exercises/pso/ex1/images/ (naming pattern 01_01_0010.png). -->

1. Open **Joule**.
2. Start a **new conversation**.
3. Type `@Product Design Assistant` and select the **Product Design Assistant** from the suggestions so that it is added as a tag.
4. With the tag in place, enter your prompt: `Can you create a BOM?`
5. The agent displays **3 different options** for creating a BOM. Choose **Upload a file**, or type the prompt `Upload a file`.
6. **Drop the file** into the drop area. Use the predefined BOM file from the [`upload-data`](./upload-data/) folder that matches **your desk card number**. The files are named `Pump_assembly_Chemical - PCE Version 2 - 10xx.xlsx`, where `xx` is replaced by your desk card number. For example, if your desk card number is **07**, select `Pump_assembly_Chemical - PCE Version 2 - 1007.xlsx`.
   > [!IMPORTANT]
   > Make sure you use the file that matches your own desk card number so that each attendee creates a BOM with a unique header material (`PMP-10xx`).
7. Press the button with the **send** icon to submit the file content to the agent.
8. The agent displays the **extracted BOM data** and a quick reply to trigger the BOM creation. Choose the quick reply **Proceed to create BOM**, or type the prompt `Proceed to create BOM`.

**Expected result:** The agent displays a **success message**, a **summary of the created BOM data** (header and components), and **options for next steps**.

> [!NOTE]
> **Why it matters:** The agent extracts a structured BOM from an unstructured file for you, but it does not create anything until you confirm with **Proceed to create BOM**. You review the extracted data first, so nothing is written without your agreement.

## Summary

Now that you have created a BOM, you will check it for gaps and enrich it.

Continue to - [Exercise 2 - Run sanity checks and enrich the BOM](../ex2/README.md)
