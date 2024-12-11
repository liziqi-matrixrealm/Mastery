# Mastery——The Ultimate Solution for 3D Hand Interaction Controllers with Low-Cost Glove Design
### Li ZiQi | liziqi@matrixrealm.com

&nbsp;

[![video link](https://github.com/liziqi-matrixrealm/Mastery/blob/main/cover_0.png)](https://youtu.be/a5aWQXh2FL0)

[↑↑↑ Please click to see the demo video ↑↑↑](https://youtu.be/a5aWQXh2FL0)

Note: the display hardware itself is limited to a maximum refresh rate of 60Hz.

Overview
========
Built on 6-axis IMU along with proprietary hardware and software algorithms, this solution captures nearly all detailed movements of the human hand with high precision, all while keeping manufacturing costs low. It enables users to interact in VR environments in the most natural, effortless, and comfortable way possible, approaching the ideal for VR hand interaction control.

Weight
======
Approximately 100g per glove (excluding battery)

Power Consumption
=================
Approximately 83mA @ 5.1V per glove (with significant room for improvement)

Features
========

   * [High Degree of Freedom](#Degrees-of-Freedom)
   * [Precision](#Precision)
   * [Low Latency](#Latency)
   * [Self-Calibration](#Self-Calibration)
   * [Pinch Detection](#Pinch-Detection)
   * [High Stability](#Stability)
   * [Easy to Wear](#Wearability)
   * [Low Cost](#Cost)

## Degrees of Freedom
Academically, the full range of motion of the hand is generally categorized as having 21 degrees of freedom (excluding the wrist) or 27 degrees of freedom (including the wrist). This solution truly encompasses the complete range of motion of the human hand, including numerous joint degrees of freedom often simplified or ignored in academic studies, resulting in unmatched detail-tracking capabilities.

## Precision
Hand motion capture is an extremely complex system, and currently, no standard method exists to quantitatively measure error or to compare this solution quantitatively with others. By qualitatively analyzing the rendering results alongside recordings of real movements, it is apparent that this solution achieves a level of precision that far surpasses any known alternatives.

## Latency
| Process                      | Time        |
| ---------------------------- | ----------- |
| Computation                  | <1ms        |
| Wireless (BLE 5.2 protocol)  | 7.5-12.5ms  |
| Wired (USB 2.0 protocol)     | <1ms        |

Note: Video demonstrations use USB wired transmission, and the display hardware itself is limited to a maximum refresh rate of 60Hz.

## Self-Calibration
In theory, users do not need to perform any manual calibration after purchase. Mastery can self-calibrate during regular use through adaptive algorithms. This approach differs from most known wearable hand-tracking devices, which require users to perform specific gestures—such as making a fist or spreading fingers—before each use (and sometimes even before every startup).

## Pinch Detection
With the support of dedicated hardware, this technology enables accurate single-hand pinch detection at key points, such as the touch of two fingertips. Based on this, it can achieve millimeter-level precision, allowing accurate triggering of functions like button presses or sliding motions within a movement scale of 1 millimeter.

Compared to vision-based solutions that require the hand to stay within the camera's field of view and involve relatively larger pinch movements, this solution significantly enhances user experience and reduces user fatigue.

## Stability
Unlike 9-axis IMU solutions, this solution is not affected by magnetic field-related factors.

## Wearability
Only two steps are needed: put on the glove and secure the velcro around the wrist. 

To accommodate different hand sizes, several standard elastic glove sizes are available. Finger thickness does not affect the fit; instead, the glove aims to match different finger lengths as closely as possible.

## Cost
Based on a single glove

| Categories                          | Price (USD) |  Note                        |
| ----------------------------------- | ----------- |------------------------------|
| IMU Chips                           | 9.3         | Based on Taobao retail price |
| MCU, BLE Chips                      | 2.5         | Based on Taobao retail price |
| Other ICs and Electronic Components | 3.5         | Estimated                    |
| PCB, FPC                            | 2.0         | Estimated                    |
| Enclosure and Protective Structure  | 2.8         | Estimated                    |
| Specialized Fabric Gloves           | 4.2         | Estimated                    |
| Assembly                            | 0.7         | Estimated                    |
| Total                               | 25.0        |                              |

Note: The values are calculated in RMB and then converted into USD based on the information and exchange rate as of November 1, 2024.
