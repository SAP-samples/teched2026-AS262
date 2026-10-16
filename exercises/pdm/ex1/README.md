# Exercise 1 - Discover capabilities and create products from a file

In this exercise, you will ask the Product Data Maintenance Agent what it can do, and then create products in bulk from an Excel file.

## Exercise 1.1: Discover the agent's capabilities

After completing these steps you will know what the Product Data Maintenance Agent can do for you.

<!-- TODO: confirm the exact wording of the agent's responses and add screenshots to exercises/pdm/ex1/images/ (naming pattern 01_01_0010.png). -->

1. Open **Joule**.
2. Start a **new conversation**.
3. Type `@Product Design Assistant` and select the **Product Design Assistant** from the suggestions so that it is added as a tag.
4. With the tag in place, enter your prompt: `What can the Product Data Maintenance Agent do?`
5. The agent displays **information about its capabilities**.

**Expected result:** The agent describes what it can do, such as creating products from a file, extending them to plants, classifying them, searching by classification, and maintaining descriptions.

> [!NOTE]
> **Why it matters:** Asking the agent about its capabilities is the quickest way to learn what is possible in the current conversation, without leaving Joule.

## Exercise 1.2: Create products from an Excel file

After completing these steps you will have created a list of products from an uploaded Excel file.

1. Enter: `create products from a file`
2. **Drop the file** [`pump_tech_data_products.xlsx`](./pump_tech_data_products.xlsx) (located in this exercise folder) into the drop area. The file does not require any change and can be uploaded directly.
3. The agent displays the **extracted product data field mappings** (the mapping of file columns to product fields).
4. Enter: `Yes, please proceed`
5. The agent displays the **extracted products**, their **classification status**, and possible next steps.
6. Enter: `Yes, please proceed`
7. The agent displays the **list of created products**.

**Expected result:** The agent creates the products from the Excel file and lists them, showing that they now exist in the system.

> [!NOTE]
> **Why it matters:** The agent shows you the field mappings and the extracted products *before* it creates anything. You confirm with `Yes, please proceed` at each step, so nothing is written until you agree.

## Summary

Now that you have created the products, you will extend them to a plant and classify them.

Continue to - [Exercise 2 - Extend products to a plant and classify them](../ex2/README.md)
