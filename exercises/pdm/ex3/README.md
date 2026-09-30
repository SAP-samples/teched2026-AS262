# Exercise 3 - Search by classification, add German descriptions, and verify

In this exercise, you will find products by their classification values, add German descriptions to your newly created products, and verify everything in the Fiori launchpad (FLP).

The suggested starting point for this exercise is the end of Exercise 2, with your products created, extended and classified.

## Exercise 3.1: Find products by their classification

After completing these steps you will have found the products that match a combination of classification values.

<!-- TODO: confirm the exact wording of the agent's responses and add screenshots to exercises/pdm/ex3/images/. -->

1. Enter: `Find all products where PUMP_TYPE is Centrifugal and HOUSING_MATERIAL is Cast Iron.`
2. The agent displays the products that match **both** classifications.

**Expected result:** The agent lists only the products whose PUMP_TYPE is *Centrifugal* and whose HOUSING_MATERIAL is *Cast Iron*.

> [!NOTE]
> **Why it matters:** Because you classified the products in Exercise 2, you can now find them by their technical characteristics instead of by product number. This is only possible when the classification data is complete.

## Exercise 3.2: Add German descriptions

After completing these steps you will have added proposed German descriptions to all newly created products.

1. Enter: `Add German descriptions for all newly created products`
2. For the newly created products, the agent displays the **English descriptions** and the **proposal for German descriptions**, and asks if they shall be added to the products.
3. Enter: `Yes, please proceed`
4. The agent lists all **updated products** and their **German descriptions**.

**Expected result:** The agent adds the proposed German descriptions to all newly created products and lists them with both the English and German text.

> [!NOTE]
> **Why it matters:** The agent proposes translations and shows them next to the English text before writing anything, so you can review the proposal. Nothing is added until you confirm with `Yes, please proceed`.

## Exercise 3.3: Verify the results in the Fiori launchpad

After completing these steps you will have confirmed, in the source app, everything the agent created and changed.

1. Open the **Fiori launchpad (FLP)**.
2. Open **any of the new products** and review:
    - the created **header data**,
    - the **descriptions** (English and German),
    - the **classifications** and characteristic values,
    - the **plant assignments** (plant 001).
   <!-- TODO: confirm the FLP app used to display the product (for example Manage Product Master Data) and the navigation path. -->

**Expected result:** The product in FLP shows the header data, the English and German descriptions, the PUMP_TECH_DATA classification with its characteristic values, and the extension to plant 001 - exactly as the agent reported in the conversation.

> [!NOTE]
> **Why it matters:** Verifying in the source app closes the loop: the agent worked entirely in Joule, but the data it created is real product master data that any other app or user can now see and use.

## Summary

You have now discovered the agent's capabilities and used it to create products from a file, extend them to a plant, classify them, search them, translate their descriptions and verify the result in FLP - all through a conversation, with the human in control at every step.

Back to the [overview](../../../README.md)
