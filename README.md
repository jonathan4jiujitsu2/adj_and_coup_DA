# adj_and_coup_DA



vals, 1417 steps, improv/step: 0.320 (last = 0.2737), fitness=31906.046078859
DE modify state:
3.02 secs, 1977 evals, 1775 steps, improv/step: 0.305 (last = 0.2458), fitness=30636.854399042
DE modify state:

Optimization stopped after 2001 steps and 3.34 seconds
Termination reason: Max number of steps (2000) reached
Steps per second = 599.10
Function evals per second = 659.58
Improvements/step = 0.29200
Total function evaluations = 2203


Best candidate found: [1.14793, 1.15494, 14.6489, 4.68971, 8.51182, 7.54233, 0.00340924, 0.269201, 0.118898, 1.86806]

Fitness: 30636.854399042


--- Optimization Results ---
Best candidate found = [1.1479265362258007, 1.1549353955161363, 14.648901349419772, 4.689714889522715, 8.511822551863135, 7.542329805860531, 0.003409243070081197, 0.26920080316410155, 0.11889816023637954, 1.8680556268623807]
Fitness = 30636.854399041527
Parameters:
  k_c               = 1.1479265362258007
  k_v               = 1.1549353955161363
  k_loss_heated     = 14.648901349419772
  k_loss_unheated   = 4.689714889522715
  Q_scale_top       = 8.511822551863135
  Q_scale_bottom    = 7.542329805860531
  k_br3_extra       = 0.003409243070081197
  k_br4_extra       = 0.26920080316410155
  external_factor_br3 = 0.11889816023637954
  external_factor_br4 = 1.8680556268623807


--- R² for Top Rooms (filtered data) ---
TR1 R² = 0.47140836499430006
TR2 R² = 0.8553377144286392
TR3 R² = 0.9866060108010394
TR4 R² = 0.9893307385806906

--- R² for Bottom Rooms (filtered data) ---
BR1 R² = 0.9465656341108265
BR2 R² = 0.9302859825498959
BR3 R² = 0.8916522547274662
BR4 R² = 0.9040756457855855

--- Physical Interpretation ---
Horizontal/Vertical Coupling Ratio: k_c/k_v = 0.9939313841124391
Heated/Unheated Heat Loss Ratio: k_loss_heated/k_loss_unheated = 3.1236230121679376
Top/Bottom Heating Power Ratio: Q_scale_top/Q_scale_bottom = 1.1285402217825704

julia> ^C

julia> 
