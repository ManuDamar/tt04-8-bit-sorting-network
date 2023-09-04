![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg)

# 4 data 8-bit Sorting Network

##How it works
Sorting networks can be visualized as combinatorial circuits where a set of denoted
compare-swap (CS) circuits can be connected in accordance to a specific network
topology. This way the CS circuit is formed by a full adder configured as a subtractor
and a pair of multiplexers, the carry of the subtractor is used for the selection of the
multiplexer.

##How to test
1. Reset signal.
2. Enter the 4 8-bit inputs (8 clock positive flanks).
3. Enable the control/load signal for 8 clock positive flanks.
4. See the results.


## Pinout
| # | Inputs   | Outputs        |  bidirectional  |
| - | -------- | -------------- | --------------- |
| 0 | Number 1 | Highest number | none            |
| 1 | Number 2 | Second highest number | none     |
| 2 | Number 3 | Third highest number | none      |
| 3 | Number 4 | Fourth highest number | none     |
| 4 | None     | Not used       | none            |
| 5 | None     | Not used       | none            |
| 6 | None     | Not used       | none            |
| 7 | Control  | Not used       | none            |

