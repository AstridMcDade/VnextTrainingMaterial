---
date: 22/01/2025
uid: at_BusinessRules
---

# Business Rules

A **Business Rule** is a reusable set of instructions consisting of conditional and assignment statements. When properly implemented, business rules can simplify processes by reducing the need for complex scripts in the Script Editor. Due to their reusability, it is often beneficial to evaluate whether a business rule is a better solution than a script for specific requirements.

## Components of a Business Rule

1. **Parameters**

    These are the input values that the business rule receives when it is called through the Script Editor.

2. **Local Variables**

    Variables that exist only within the scope of the business rule. These cannot be accessed externally.

3. **Return Value**

    The output value returned by the business rule to the caller in the Script Editor. The return value must be one of the defined local variables.

4. **Predicates and Actions**

    These define the tasks performed by the business rule. A business rule can include multiple actions, where the order of execution is critical. The available actions are:

- **Assignment**

    Perform simple or complex calculations, assigning the result to a local variable.

  - Calculations can include local variables, parameters, and business rule variables.

  - Use the calculation text box for input or the provided buttons to edit the calculation.

  - The Clear button removes all input from the calculation field.

  - The Functions button opens the Functions Window, where predefined functions can be used. Each function includes a description and a list of parameters that require input values.
  - If ... Then

    Add complexity to the business rule with conditional logic.

  - Allows nested If ... Then actions or the inclusion of Assignment actions within the current condition.

### Functions Window

The **Functions Window** provides a variety of predefined functions that can be integrated into business rules. Descriptions and parameter details are displayed for each function, ensuring clarity in usage.

>[!NOTE]
>Placeholder for examples of business rule configurations and advanced scenarios.
