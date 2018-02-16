[[Model]]
    (Model(one_pulse, prefix='one_') + Model(one_pulse, prefix='two_'))
[[Variables]]
    one_x_offset:      3.0553e-07 (init= 2.93188e-07)
    two_x_offset:      3.5278e-07 (init= 9.69188e-07)
    sum_amplitudes:    1.72604540 (init= 1.964059)
    diff_amplitudes:   0.45504349 (init= 0)
    one_amplitude:     1.09054444  == '(sum_amplitudes + diff_amplitudes)/2'
    two_amplitude:     0.63550095  == '(sum_amplitudes - diff_amplitudes)/2'
