# GAUGE PARAMETERS

The parameters for gauges can be broken down into three groups:

- Basic Parameters

- Gauge Numbering

- Ranges (Color Bars)

## Basic Parameters

| Parameter | Description |
| ----------- | ----------- |
| Label | The gauge name that will be displayed on screen. It appears at the bottom of round and value gauges and along the left edge bar gauges. When you select a Measurement to be displayed by the gauge, the name of the selected measurement will be entered here automatically. But, the name can be changed if desired.|
| Type | Select the type of gauge: Dial (round), Bar, or Numeric. |
| Measurement | Click this link to select the signal whose output the gauge will display. |
| Unit | Once the Measurement is selected, use this dropdown to select the units for this measurement. For example, a speedometer can display mph or km/h.|
| Decimels | This specifies the number of decimal places used when displaying the digital readout of the gauge reading. |

## Gauge Numbering

To set up the numbering on the face of the gauge, configure the following parameters:

| Parameter | Description |
| ----------- | ----------- |
| Min Value | The lowest value that the gauge will be able to display.|
| Max Value | The highest value that the gauge will be able to display.|

![](Gauge_Page108.png)

For round gauges, the following additional parameters can be configured:

| Parameter | Description |
| ----------- | ----------- |
| Divisions | How many numbers appear on the outside of the gauge? Both gauges above have five.|
| Factor | The raw value will be divided by this number to produce the numbers on the gauge face. For example, you could divide the numbers around the edge of the gauge on the left by 1000 to make them read 2, 4, 8, 10.|
| Arc Sweep | How far around the edge of the gauge (in degrees) does the numbering go? At 40 degrees, the gauge will look like a narrow slice of pie. At 260, it's almost the whole pie. Both of the gauges above use 260. |

## Ranges (Color Bars)

Some gauges have color bars along the outer edge. For example, it's common for gauges to have a red zone to indicate that operating the engine in that range may be risky.

To configure a color bar:

1. In the **Range Start** box, specify the lowest value in the range covered by the color bar.
>**NOTE:** The range end is set automatically to the Max Value of the gauge. When additional bars are defined, the range end changes to the Range Start defined for the next bar

2. Select the desired color from the color dropdown to the right.

3. If additional color bars are desired, click the Add New Range button and repeat steps 1 and 2.

<a href="#" class="top-button" title="Return to top">↑</a>