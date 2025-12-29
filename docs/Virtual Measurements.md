# VIRTUAL MEASUREMENTS

The Virtual Measurements window can be used to create complex values that take into account multiple measurements. Once defined, these parameters can be used in gauges and graphs as if they were output from a sensor or other measurement.
>**NOTE:** In VCM Scanner, measurements of this type are called "Math Parameters".

To open this window, select **Log** > **Virtual Measurements**.
![](add_virtual1.png)

The most commonly used virtual measurements are built in (predefined). The software also allows you to add up to 10 user defined measurements.

## Defining Virtual Measurements

1. Click the ![](add_chart_signal_icon.png) icon.

2. In the left column, select the new virtual measurement.

3. On the right side of the window, enter the **Display Name** for this measurement. This is the name you will see displayed on screen.

4. In the Name box, enter the internal parameter name used by the software.
>**NOTE:** This is typically just the Display Name with spaces and other special characters removed. It can be used to include this calculation in other virtual measurements.

5. Enter the **Math Expression** for this measurement. This is the formula that will be used to calculate the new measurement. See *Defining Expressions* below.

6. Click **Ok**.

## Defining Expressions

An expression is the mathematical formula that is used to calculate the virtual measurement's value. The expression can include measurements, such as the output of sensors or calculated outputs. These are inserted into the expression as variables.

The process for defining an expression is as follows:

1. Insert [variables](Expression Variables.md) that represent the measurements that will be included in the calculation.
>**NOTE:** In the Math Expression box, the names of inserted variables will appear in brackets.

2. Add [supported math operations](Supported Math Operations and Functions.md) to complete the desired calculation.
> **NOTE:**There are two types of expression:

    > - Calculated
    > - Conditional

## Calculated Expressions

A calculated expression applies mathematical operations to the output of the sensors or PIDs identified in the expression in order to provide a modified signal or a signal that is derived from multiple inputs.

Examples:

- 	[lambdaSetpoint] - [lambdaSensor1]
>**NOTE:** Lambda bank 1 error

- 	([intakeAirTemperature.K] * ([primaryInjectorFlowRate.g/s] / 1000) * [primaryPulseWidth.ms] * [lambdaSetpoint]) / [manifoldAbsolutePressure.kPa]
>**NOTE:** Airmass per cylinder using IAT, primary injector flow rate, primary injector pulse width, lambda setpoint, and MAP.

## Conditional Expressions

A conditional expression specifies a function that tests the output data stream of the measurements identified in the expression and produces a TRUE or FALSE result for each frame of the output.

Conditional expressions must return either 1 (TRUE) or 0 (FALSE).

Example:

- 	[massAirflow.g/s] > 100

<a href="#" class="top-button" title="Return to top">↑</a>