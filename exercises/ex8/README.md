# Exercise 8 - Bonus exercises

In this exercise, you will change how the agent analyses the alert and compare insights across resources.

The suggested starting point for the bonus exercises is the end of Exercise 7.

## Exercise 8.1: Change how the alert is analysed

The same alert can be resolved in different ways by different organisations. Change the instructions so the agent also looks at which products drive the overload.

After completing these steps you will have extended the instructions and seen the effect in the insight.

<!-- TODO: provide the extra step as a snippet (on the desktop or in this repo), and confirm the units in the Capacity by Product table. -->

1. Open your instructions JSON and add a step that reads Capacity Consumption Planned by product for the overloaded resource and week.
2. Upload, validate, and check that the flowchart now has the extra step.
3. Run the job from Exercise 5 again.
4. Open the insight card for CN1310 ASSEMBLY, CW36 2026.

**Expected result:** The insight now names the products behind the overload. The **Capacity by Product** table in the workbook shows the same products (for CW36: IBP2-100 with 18, IBP2-120 with 4, IBP2-200 with 7, IBP2-110 with 1).

## Exercise 8.2: The packing line

After completing these steps you will have seen the same instructions applied to a second resource.

1. In the Exception Management panel, switch the filter to **CN1310 PACK** and CW37 2026.
2. Compare the insight for the packing line with the one for assembly.

**Expected result:** The packing line is overloaded at about 132%, a smaller gap than assembly. The agent applies the same instructions to both resources and gives each its own numbers.

## Summary

Now that you have changed the instructions and compared resources, you have seen how one agent can be adapted to the way your organisation resolves an alert.

Back to the [overview](../../README.md)
