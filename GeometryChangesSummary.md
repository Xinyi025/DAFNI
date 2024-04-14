1. X = ['Oi_net_i_log', 'Oi_net_j_log', 'Dj_net_i', 'Dj_net_j', 'net_secs',neti_Oi_netj_Dj_log','IsBus','IsRail','IsRoad']
    y = ['SavedSecsRoad_log1p']
R-squared Score (R2) on test data: 0.6982205789905331
Mean Squared Error (MSE) on original data scale: 132988160334.00275
Mean Absolute Error (MAE) on original data scale: 25800.259457406584



2. X = ['Oi_net_i_log', 'Dj_net_j', 'neti_Oi_netj_Dj_log','net_secs','IsBus','IsRail','IsRoad']
   y = ['SavedSecsRoad_log1p']

R-squared Score (R2) on test data: 0.7001723298469008
Mean Squared Error (MSE) on original data scale: 132986862176.58238
Mean Absolute Error (MAE) on original data scale: 25791.256399406637



3. X =  ['Oi_net_i', 'Dj_net_i', 'Oi_net_j', 'Dj_net_j', 'neti_Oi_netj_Dj','SavedSecsRoad']
   y = ['SavedSecsRoad_log1p']

R-squared Score (R2) on test data: 0.6981121566005466
Mean Squared Error (MSE) on original data scale: 132986412701.09868
Mean Absolute Error (MAE) on original data scale: 25796.07302678718


4. X = ['neti_Oi_netj_Dj_log','net_secs','IsBus','IsRail','IsRoad']
   y = ['nMinusRail_log1p']

R-squared Score (R2) on test data: 0.979733514642011
Mean Squared Error (MSE) on original data scale: 731972073642.823
Mean Absolute Error (MAE) on original data scale: 243146.95871590523


5. X = ['Oi_net_i_log', 'Dj_net_j','neti_Oi_netj_Dj_log','net_secs','IsBus','IsRail','IsRoad']
   y = ['nMinusRail_log1p']

R-squared Score (R2) on test data: 0.9861895253390333
Mean Squared Error (MSE) on original data scale: 477970104117.1124
Mean Absolute Error (MAE) on original data scale: 193085.74104979105