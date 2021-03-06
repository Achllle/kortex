# Enum CommandMode

This page describes the C++ Kinova::Api::ActuatorConfig::CommandMode enumeration.

## Overview / Purpose

List of admissible command modes

## Enumeration definition

|Enumerator|Value|Description|
|----------|-----|-----------|
|CYCLIC|0|Cyclic data only|
|ASYNC\_CYCLIC\_FLAGS|1|Not supported|
|ASYNC|2|Config messages only|
|CYCLIC\_JITTERCOMPENSATED\_POSITION|3|Smoothing using only position inputs|
|CYCLIC\_JITTERCOMPENSATED\_VELOCITY|4|Smoothing using position and velocity inputs|
|CYCLIC\_JITTERCOMPENSATED\_ACCELERATION|5|Smoothing using position, velocity and acceleration inputs \(not supported\)|

**Parent topic:** [ActuatorConfig](../references/summary_ActuatorConfig.md)

