# Exercise 2 - Extend products to a plant and classify them

In this exercise, you will extend your newly created products to a plant and classify them against a classification class.

The suggested starting point for this exercise is the end of Exercise 1, with your products created and listed.

## Exercise 2.1: Extend all products to plant 001

After completing these steps you will have extended all newly created products to plant 001.

<!-- TODO: confirm the exact wording of the agent's responses and add screenshots to exercises/pdm/ex2/images/. -->

1. Enter: `Extend all products to plant 001`
2. The agent displays the **list of products** and their **planned extension to plant 001**.
3. Enter: `Yes, please proceed`
4. The agent displays the **list of products for plant 001**.

**Expected result:** The agent extends all newly created products to plant 001 and lists them with their plant assignment.

> [!NOTE]
> **Why it matters:** Extending a product to a plant makes it usable for planning and production at that location. The agent applies the extension in bulk, but only after you confirm the planned changes.

## Exercise 2.2: Classify the products with PUMP_TECH_DATA

After completing these steps you will have classified all newly created products using the class PUMP_TECH_DATA.

1. Enter: `Classify all newly created products from the Excel file using class PUMP_TECH_DATA`
2. The agent displays a **classification plan** for mapping file columns to characteristics and the characteristics to set per product.
3. Enter: `Yes, please proceed`
4. The agent displays the **classifications and characteristics** for the list of processed products and an **import summary**.

**Expected result:** The agent classifies all newly created products against PUMP_TECH_DATA, setting the characteristic values from the file, and shows an import summary.

> [!NOTE]
> **Why it matters:** Classification makes products findable and comparable by their technical characteristics (for example PUMP_TYPE and HOUSING_MATERIAL). The agent shows the mapping plan first, so you can check which characteristics will be set before it imports them.

## Summary

Now that your products are extended and classified, you will search them by classification and add German descriptions.

Continue to - [Exercise 3 - Search by classification, add German descriptions, and verify](../ex3/README.md)
