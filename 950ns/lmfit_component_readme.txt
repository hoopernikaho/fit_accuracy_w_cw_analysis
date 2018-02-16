[[Model]]
    (Model(one_pulse, prefix='one_') + Model(one_pulse, prefix='two_'))
[[Variables]]
    one_x_offset:      3.1161e-07 (init= 2.796004e-07)
    two_x_offset:      3.1292e-07 (init= 6.196004e-07)
    sum_amplitudes:    1.87890603 (init= 1.963569)
    diff_amplitudes:   0.24045268 (init= 0)
    one_amplitude:     1.05967936  == '(sum_amplitudes + diff_amplitudes)/2'
    two_amplitude:     0.81922667  == '(sum_amplitudes - diff_amplitudes)/2'
