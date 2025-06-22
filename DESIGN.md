## Functions

`one_step_elo(R_a: float, R_b: float, S_a: float,  K: float, W_mv: float)` - Progresses the elo ranking by one step after one match for each team.

`prob_win_A(R_a: float, R_b: float)` - Calculates the probability that team A wins a match between team A and team B, based on inputted elo scores.

### WIP
WIP indicates that implementation and necessary parameters for each function are as of yet undecided/not finalized.

`start_elo()` -  Sets the starting elo scores for each team.

`calculate_K()` - Calculates K parameter for use in `one_step_elo`.

`calculate_W_mv()` - Calculates margin of victory multipler for a singular match.