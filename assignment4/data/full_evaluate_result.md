winning rate matrix:

|                         |   compute_action_function |   RANDOM |   WEAK |   MEDIUM |   STRONG |   RULE_BASED |   ALPHA_PONG |
|:------------------------|--------------------------:|---------:|-------:|---------:|---------:|-------------:|-------------:|
| compute_action_function |                         1 |        1 |      1 |        1 |        1 |            1 |            1 |
| RANDOM                  |                         0 |        1 |      0 |        0 |        0 |            0 |            0 |
| WEAK                    |                         0 |        1 |      0 |        0 |        1 |            1 |            0 |
| MEDIUM                  |                         0 |        1 |      1 |        1 |        1 |            1 |            0 |
| STRONG                  |                         0 |        1 |      0 |        0 |        0 |            1 |            0 |
| RULE_BASED              |                         0 |        1 |      0 |        0 |        0 |            0 |            0 |
| ALPHA_PONG              |                         0 |        1 |      1 |        1 |        1 |            1 |            1 |




reward matrix

|                         |   compute_action_function |   RANDOM |   WEAK |   MEDIUM |   STRONG |   RULE_BASED |   ALPHA_PONG |
|:------------------------|--------------------------:|---------:|-------:|---------:|---------:|-------------:|-------------:|
| compute_action_function |                         3 |       19 |     11 |       11 |        9 |            3 |           13 |
| RANDOM                  |                       -19 |        9 |     -7 |      -15 |      -15 |          -19 |          -19 |
| WEAK                    |                       -11 |        7 |     -1 |       -1 |        1 |            3 |           -3 |
| MEDIUM                  |                       -11 |       15 |      1 |        1 |        1 |           13 |           -1 |
| STRONG                  |                        -9 |       15 |     -1 |       -1 |       -5 |            3 |           -5 |
| RULE_BASED              |                        -3 |       19 |     -3 |      -13 |       -3 |          -11 |          -15 |
| ALPHA_PONG              |                       -13 |       19 |      3 |        1 |        5 |           15 |            5 |