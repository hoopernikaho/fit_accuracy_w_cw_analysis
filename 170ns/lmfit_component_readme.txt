[[Model]]
    (Model(one_pulse, prefix='one_') + Model(one_pulse, prefix='two_'))
[[Variables]]
    one_x_offset:      3.0315e-07 (init= 1.52083e-07)
    two_x_offset:      4.8198e-07 (init= 7.40083e-07)
    sum_amplitudes:    1.81300070 (init= 1.963791)
    diff_amplitudes:  -0.15372066 (init= 0)
    one_amplitude:     0.82964002  == '(sum_amplitudes + diff_amplitudes)/2'
    two_amplitude:     0.98336068  == '(sum_amplitudes - diff_amplitudes)/2'
