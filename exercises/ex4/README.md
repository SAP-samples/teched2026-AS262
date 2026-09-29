# Exercise 4 - What went wrong?

In this exercise, you will find and fix an error in a set of agent instructions using the validation report.

<!-- TODO: author note - proposed exercise, modelled on the "What went wrong / Fix the configuration" arc of the Cloud Integration session. Seeded error, file name and exact validation message are still TBD. -->

## Exercise 4.1: Find and fix the error

A colleague wrote a second version of the instructions. It looks fine, but it does not validate. Find out why and fix it.

After completing these steps you will have used the validation report to locate a faulty step and corrected it.

1. In EMA_XX, create a second set of agent instructions and upload `capacity_overload_instructions_v2.json`.
2. Choose **Validate**.
3. Open the validation report and find the step that failed.
4. Read the error message. It should tell you which key figure could not be read.
   <!-- TODO: add the exact validation message. -->
5. Open the JSON file in a text editor, correct the key figure ID, and upload the file again.
6. Validate again.

**Expected result:** The first validation fails on the step that reads capacity data, because the key figure ID in the file does not exist in HPAEMAGENT. After the fix, validation passes and the test data analysis shows values for CN1310 ASSEMBLY.

> [!NOTE]
> **Why it matters:** Validation catches errors at design time, before the agent runs on real alerts. This is the same pattern as a field mapping error in an integration flow: the fix is in the configuration, not in the code.

## Summary

Now that your instructions are correct, you are ready to run the agent on the real alerts.

Continue to - [Exercise 5 - Run the agent](../ex5/README.md)
