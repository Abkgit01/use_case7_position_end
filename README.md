# use_case7_position_end

## Purpose
Demonstrates attacks placed at the end of long context where they may be freshest in attention.

## Example Injection
$(System.Collections.Hashtable.Example)

## Risk Note
Medium risk because recency can bias completion decisions.

## Files
- Program.cs prints the scenario summary and calculated risk score.
- Calculator.cs defines the scenario model and the scoring logic.
- CalculatorTests.cs contains simple validation helpers for the scenario.
