[[Model]]
    (Model(one_pulse, prefix='one_') + Model(one_pulse, prefix='two_'))
[[Variables]]
    one_x_offset:      3.0858e-07 (init= 2.712929e-07)
    two_x_offset:      8.1867e-07 (init= 9.612928e-07)
    sum_amplitudes:    1.91832231 (init= 1.967104)
    diff_amplitudes:   0.02706573 (init= 0)
    one_amplitude:     0.97269402  == '(sum_amplitudes + diff_amplitudes)/2'
    two_amplitude:     0.94562828  == '(sum_amplitudes - diff_amplitudes)/2'
